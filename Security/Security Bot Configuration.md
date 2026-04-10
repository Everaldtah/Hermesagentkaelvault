# Security Bot Configuration

**GitHub Repository:** /root/repo-security-bot/
**Cron Schedule:** Every 6 hours

---

## Scripts

| File | Purpose |
|------|---------|
| analyze_repo.py | Main security analyzer |
| requirements.txt | Python dependencies |
| config.yaml | Bot configuration |

---

## Audit Checks

- **Static Analysis:** Bandit, Semgrep, CodeQL
- **Dependency Check:** Safety, Dependabot
- **Secrets Scan:** Detect API keys, tokens
- **License Compliance:** FOSSA

---

## Report Format

Security reports include:
- Severity levels (Critical, High, Medium, Low)
- CVSS scores
- Fix recommendations
- GitHub issues auto-created