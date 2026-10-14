## Jeremy Kwon

Full-stack product engineer in South Korea. I own production systems end to end — from the first commit to the midnight incident report — across SSO, payments, mobile apps and zero-downtime migrations. I've also founded and shipped products of my own.

**Taking on contract projects:** new builds, takeovers of live systems, and long-term maintenance. Also open to full-time product engineering roles. Working in Korean and English.

![AWS SAA](https://img.shields.io/badge/AWS-Solutions%20Architect%20Associate-232F3E?style=flat-square&logo=amazonwebservices&logoColor=FF9900)

**2+ years** running public-sector web and SSO systems · a conference platform for **~300 papers and ~2,000 participants**, live **40 days** after kickoff · **zero-downtime** migrations

### Case studies

Client names and confidential project details are left out of the case studies below.

<details>
<summary><b>Taking over live public-sector websites</b> · 2024–2026</summary>

- **Problem:** A main website and two affiliated sites needed someone to take over development and operations.
- **My role:** Owned all development of the main website and its admin CMS for 2+ years, plus the two affiliated sites.
- **What I did:** Took over the running systems, brought the source code and release process under control, automated deployments, and migrated the two affiliated sites without service interruption.
- **Result:** The sites have stayed in operation throughout. Wrote the migration plan, test and data-verification reports, and an incident manual.

</details>

<details>
<summary><b>Single sign-on for a local government</b> · 2024–2026</summary>

- **Problem:** Affiliated sites built on different stacks needed one login.
- **My role:** Built the platform's auth server and admin console, and have maintained it for 2 years, along with the citizen apps.
- **What I did:** One sign-in with 4 social logins and 2 identity-verification providers. Integration samples and guides so affiliated sites could connect. An admin console for login history, audit logs and usage statistics. A move to public cloud.
- **Result:** Affiliated sites sign in through one account, and the platform has stayed in operation for 2 years.

</details>

<details>
<summary><b>Two native apps → one React Native app</b> · e-commerce · 2024–2026</summary>

- **Problem:** Separate Android and iOS apps were hard to maintain.
- **My role:** Owned the app end to end, from the rebuild through store releases.
- **What I did:** Rebuilt both apps as a single React Native app, released it in stages, and set up over-the-air updates so eligible fixes ship without waiting for store review.
- **Result:** One codebase for both platforms, with regular store releases, store policy updates and written incident reports.

</details>

<details>
<summary><b>Conference platform for ~300 papers and ~2,000 participants, live 40 days after kickoff</b> · 2026, ongoing</summary>

- **Problem:** Paper submission, registration and payment were spread across separate tools.
- **My role:** Planned, built and run it end to end.
- **What I did:** One platform for submission, registration and payment, with SSO into the open-source paper review system (OJS). A pipeline that runs checks, regression tests, packaging, deploy and smoke tests on every push, with unit, shell, PHP and browser (E2E) tests from day one. Role-based user guides and runbooks for deploy and recovery.
- **Result:** Nightly automated checks that backups contain the latest submissions and can actually be restored. During the submission period, I walked through the author flow end to end and fixed a blocking bug the same day, before any author reported it.

</details>

<details>
<summary><b>Secure pull-print product, from planning to on-site rollout</b> · 2026, ongoing</summary>

- **Problem:** Printed documents sat in shared printer trays where anyone could pick them up.
- **My role:** Planned, designed, built and deployed it end to end, working directly with the printer manufacturer (HP), rental-company staff and the client's team.
- **What I did:** A Windows PC agent and a printer-side Android app that talk to each other without a central server. Documents sent to a virtual printer stay on the user's PC until the user signs in at the printer with a card or PIN. A Windows installer that sets up the printer and firewall automatically, with code signing and per-device licensing. An admin console for users, printers and policies, with CSV bulk import.
- **Result:** Field-tested and shipped v1.0–v1.1 to client sites, with an on-site installation runbook.

</details>

### How I work

- Scope and done criteria are agreed before work starts.
- Working builds are shipped in stages; progress is shared weekly.
- Extra requests get a one-page estimate (scope, hours, cost) and start only after approval.
- Incidents get a written report: impact, cause, fix, and steps to prevent a repeat.
- Code, docs, servers and accounts are handed over in the client's name.
- I lead and build every project myself, and bring in design or dev partners when the scope needs it.

### More client work

- **Bidding & quotation platform** (2025–2026) — launched v1 and led development through the v2 rebuild, with automated testing, deployment and scheduled backups.
- **Event ticketing** (2025) — 11 ticket tiers, KR/EN checkout with overseas payments, QR entry, and on-site support during the event.
- **Security work** — fixed web vulnerability findings on legacy systems, and built a file encryption module for personal data with Java / .NET integration guides.

### Products I founded and shipped

- **Rife** — a café subscription service. Took it from idea to launch and built both the frontend and the backend myself. Grand Prize, Sejong Univ. Startup Item Competition (2022).
- **[SmartCycle](https://github.com/MODORIAPPS/SmartCycle-Sort_up_Trash_by_Oneshot)** — an app that tells you how to sort your trash from a single photo. Shipped to users; won the STAC 2019 Grand Prize (Minister of SMEs and Startups Award).

### Stack

![Java](https://img.shields.io/badge/Java%20%2F%20Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Next.js](https://img.shields.io/badge/React%20%2F%20Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React Native](https://img.shields.io/badge/React%20Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

Also: eGovFrame · PHP / WordPress · C# / .NET · MySQL · Redis · Nginx · GitHub Actions / CI/CD

### Awards & Certifications

- AWS Certified Solutions Architect – Associate · Linux Master Level 2
- **STAC 2019 Grand Prize, Future Industry** — Minister of SMEs and Startups Award (SmartCycle)
- Sejong Univ. Startup Item Competition — Grand Prize (2022-1, Rife), Excellence Award (2022-2) · Pitching & Mentoring Day Grand Prize (2022-2)
- Asan Nanum Foundation Entrepreneurship Excellence Award (2020) · NIPA SW Development Contest Honorable Mention (2023)

### Contact

📮 **kwonkiseok7@gmail.com** — for a new build, a takeover or maintenance, send your current setup, scope and target timeline.
