# 🛡️ SecurAI Audit Tool

**Security audit for AI-built web apps.** Run 31 checks in your browser,
get a risk score, and see exactly how to fix what's broken.

👉 **[Try it live](https://elhambidarigh.github.io/securai/)**

## Why

AI coding tools (Cursor, Copilot, v0) generate working code — but not
secure code. SecurAI catches the gaps before hackers do.

## What it checks

- 🔑 **Secrets & Credentials** — hardcoded keys, .env leaks, git history
- 🔐 **Authentication** — bcrypt, session flags, MFA, JWT validation
- 🧱 **Input Validation** — SQLi, XSS, CSRF, file uploads
- 🤖 **AI-Specific Risks** — prompt injection, LLM output sanitization, vector DB
- 🛡️ **API & Data** — HTTPS, CORS, rate limits, error leakage
- ⚙️ **Infrastructure** — CSP, CVEs, least privilege, backups

## Privacy

Runs entirely in your browser. Nothing is uploaded. No account needed.

## The full SecurAI toolkit

| Tool | Type | Link |
|------|------|------|
| 🛡️ **Audit Tool** | Self-assessment (browser) | [Live demo](https://elhambidarigh.github.io/securai/) |
| 🔬 **Vuln Lab** | Educational (PHP/MySQL) | [Repo](https://github.com/ElhamBidarigh/securAI-vuln-lab) |
| ⚙️ **Security Action** | CI/CD (GitHub Actions) | [Workflow](https://github.com/ElhamBidarigh/securAI-vuln-lab/tree/main/.github/workflows) |
| 🔍 **Active Scanner** | Live URL scanner (PHP) | [Repo](https://github.com/ElhamBidarigh/securAI-active-scanner) |

## Related projects

- 🔬 **[SecurAI Vuln Lab](https://github.com/ElhamBidarigh/securAI-vuln-lab)** —
  A deliberately vulnerable PHP/MySQL app demonstrating 5 OWASP Top 10
  issues, each with a working PoC exploit and a fixed counterpart.
- 🔍 **[SecurAI Active Scanner](https://github.com/ElhamBidarigh/securAI-active-scanner)** —
  A PHP tool that fetches a live URL and runs 11 non-destructive checks
  (headers, cookies, CORS, exposed .env / .git, open redirects, HTTP methods).

## Pricing (coming soon)

- **Free:** 5 audits/day
- **Starter ($9/mo):** Unlimited audits + PDF export
- **Pro ($19/mo):** + CI integration + AI deep checks

## License

MIT
