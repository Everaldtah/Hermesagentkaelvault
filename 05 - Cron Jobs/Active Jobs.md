# Active Cron Jobs

**Total:** 3 jobs
**Time Format:** UTC

---

## Job 1: GitHub Security Hardening Bot
| Field | Value |
|-------|-------|
| **ID** | 7c9fb811bdc5 |
| **Schedule** | Every 6 hours |
| **Skill** | github-auth |
| **Next Run** | 2026-04-10 12:00:00 UTC |
| **Deliver** | origin |

**Purpose:** Scans GitHub repositories for security issues

## Job 2: repo-security-bot
| Field | Value |
|-------|-------|
| **ID** | 997f89804cb0 |
| **Schedule** | Every 6 hours |
| **Script** | /root/repo-security-bot/analyze_repo.py |
| **Next Run** | 2026-04-10 12:00:00 UTC |
| **Deliver** | telegram |

**Purpose:** Automated security analysis with reports

## Job 3: Daily Dropshipping Pipeline
| Field | Value |
|-------|-------|
| **ID** | 523a65ad4991 |
| **Schedule** | Daily at 8:00 AM |
| **Skill** | dropshipping-core |
| **Next Run** | 2026-04-10 08:00:00 UTC |
| **Deliver** | telegram |

**Purpose:** Runs products provided

---

## Sync Times (UTC)
- Security audits: 00:00, 06:00, 12:00, 18:00
- Dropshipping: 08:00 daily

---

## Vault Sync
Run: ~/vault-sync.sh