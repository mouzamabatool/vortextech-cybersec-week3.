# vortextech-cybersec-week3.
Track: Cyber Security Target: OWASP Juice Shop (local Docker instance)

What this is

A structured, beginner-level security audit of OWASP Juice Shop, a deliberately vulnerable web app built for legal practice. The full

write-up is in AUDIT_REPORT.md.

It documents 7 findings across 5 OWASP Top 10 (2021) categories, each with: what was found, how it was found, potential

impact, and a remediation.

Repository layout

README.md

AUDIT_REPORT.md

screenshots/

browser)

<- this file

<- full audit

<- evidence (DevTools / ZAP

How to reproduce

1. Install Docker Desktop.

2. Run the practice target (local only):

docker pull bkimminich/juice-shop
docker run -d -p 3000:3000 bkimminich/juice-shop

3. Open http://localhost:3000

4. Follow the steps in each finding of AUDIT_REPORT.md

5. (Optional) Run OWASP ZAP (zaproxy.org) → Automated Scan → http://localhost:3000

Scope & ethics

Only a local, intentionally vulnerable practice instance was tested. No real production system was touched.

# vortextech-cybersec-week3.
