<!--
  Frank Jáuregui — GitHub profile README
  Design principles: plain Markdown first, one stats widget max,
  no banners/GIFs/trophies. Whitespace and hierarchy do the work.
-->

# Frank Jáuregui

Full-stack developer from Lima, Perú. Computer Engineering student at Universidad Peruana Cayetano Heredia and co-founder of **Hanan Technology Group**, where I lead development of B2B platforms for the automotive parts industry.

I work mostly with **Django** on the backend and **SvelteKit / React** on the frontend, and I care about the parts of software that don't show up in screenshots: architecture, testing, and code the next person can actually read.

**Currently:** building [ECOMPARTS](#ecomparts), preparing for the GitHub Copilot certification (GH-300), and looking for internship and remote opportunities.

<br/>

## Featured projects

### ECOMPARTS
**B2B marketplace for automotive parts distributors in Perú.**

Most distributors here still run sales through phone calls and spreadsheets. ECOMPARTS gives them a catalog, ordering, and account management platform built on top of a real ERP.

- **Stack:** Django · Odoo 18 · SvelteKit · PostgreSQL · Redis · Celery · Docker
- **Architecture:** Odoo as the ERP core with a custom Django API layer and a decoupled SvelteKit frontend; async jobs handled by Celery workers over Redis
- **My role:** lead developer — backend, frontend architecture, Git workflow for the team
- **Status:** in active development, validating with distributors from Expomecánica

### EcoWatt — NILM energy monitor
**Real-time appliance-level energy monitoring from a single sensor.** Built as team lead for the EcoWatt 2026 Hackathon at UNI.

Non-Intrusive Load Monitoring: one ESP32 measures the household's aggregate consumption, and a neural network figures out which appliances are running.

- **Stack:** ESP32 (C++) · MQTT over TLS (HiveMQ Cloud) · Django + Daphne (ASGI/WebSockets) · PostgreSQL (Supabase) · PyTorch · React
- **Architecture:** firmware publishes readings over MQTT → Django backend streams them to the dashboard via WebSockets → an SGN model disaggregates consumption per appliance
- **Highlights:** end-to-end pipeline from firmware to ML inference to live dashboard, deployed on Render
- **Status:** functional prototype

### HSPP — Hiraoka Services Portal
**QA lead across the full lifecycle of a ticket-management platform** (Docker microservices on AWS EC2), over 9 sprints.

- **Work:** Postman API test suites, k6 load testing (200 concurrent users), UAT design and execution, regression testing, Go/No-Go reporting
- **Result:** 12+ defects registered and tracked to resolution in Jira — project closed with **zero open defects**
- **Deliverable:** 14-page formal testing report

<br/>

## Tech stack

| | |
|---|---|
| **Languages** | Python, TypeScript, JavaScript, SQL |
| **Backend** | Django, Django REST Framework, Celery, ASGI/WebSockets (Daphne) |
| **Frontend** | SvelteKit, React, Tailwind CSS |
| **Databases** | PostgreSQL, Redis, Supabase |
| **Cloud & DevOps** | AWS (EC2, Route 53), Docker, Render, Git/GitHub |
| **Testing & QA** | Postman, k6, Jira, UAT design |
| **ML & IoT** | PyTorch, scikit-learn, ESP32, MQTT |

<br/>

## GitHub activity

<!-- Single stats card, transparent background, neutral accent. -->
<img src="https://github-readme-stats.vercel.app/api?username=FRANKEVIN25&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=00000000&title_color=58a6ff&icon_color=58a6ff&text_color=8b949e" height="165" alt="GitHub stats"/>

<br/>

## Contact

- **LinkedIn:** [linkedin.com/in/frank-jauregui](https://linkedin.com/in/frank-jauregui)
- **Email:** [frankjaureguibendezu81@gmail.com](mailto:frankjaureguibendezu81@gmail.com)

Open to internships, remote work, and interesting problems.
