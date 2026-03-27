# FUTURE_CS_01 — Vulnerability Assessment Report

**Intern:** Idowu Popoola  
**Track:** Cyber Security  
**Organization:** Future Interns  
**Date:** March 2026  

### Website Tested
* **African Freefire Community** — `https://africanfreefirecommunity.com`
* **Authorization:** Written permission obtained from the site owner prior to testing. See `/permission/authorization_email.png`

### Scope
Passive, read-only assessment of the primary public-facing domain only. No login bypass, exploitation, brute force, or denial-of-service was performed at any point.

### Tools Used
* OWASP ZAP (passive scan)
* Browser DevTools (header & attribute inspection)
* Nmap / Zenmap (port enumeration)

### Findings Summary

| # | Finding | Risk |
|---|---|---|
| 01 | Content Security Policy (CSP) Header Not Set | Medium |
| 02 | Sub Resource Integrity Attribute Missing | Medium |
| 03 | Server Leaks Information (via HTTP Responses) | Low |
| 04 | X-Content-Type-Options Header Missing | Low |
| 05 | Strict-Transport-Security (HSTS) Header Not Set | Low |

### Deliverables
* `report.pdf` — Full vulnerability assessment report
* `permission/` — Written authorization from site owner
* `evidence/` — Screenshots supporting each Medium-risk finding

### Disclaimer
This assessment was conducted strictly for educational purposes as part of the Future Interns Cyber Security internship program. All testing was authorized and passive.