# Hermes Agent System Overview

## What is Hermes Agent?

Hermes Agent by Nous Research is an autonomous AI system with:
- **40+ built-in tools** (browser, code exec, web search, file ops)
- **Persistent memory** across sessions
- **Subagent spawning** for parallel tasks
- **Cron scheduler** for automation
- **Skill creation** that auto-refines over time

## Key Features

| Feature | Description |
|---------|-------------|
| Skills | Auto-generated Markdown in ~/.hermes/skills/ |
| Memory | FTS5 search + Honcho user models |
| Tools | Terminal, browser, file, web, code execution |
| Cron | Natural language scheduling |
| Gateways | Telegram, Discord, Slack, Email, SMS |

## Architecture

```
User Message → Parse → Load Skills → Execute Tools → Store Results → Memory Update
                    ↓
            Subagents (parallel)
            Cron Jobs (scheduled)
```

## Commands

```bash
hermes setup          # Configure
hermes cron add       # Schedule job
hermes skills list    # View skills
```

## Memory Locations

- `~/.hermes/skills/` - Custom skills
- `~/.hermes/memory.db` - Conversation history
- `~/.hermes/.env` - Environment variables