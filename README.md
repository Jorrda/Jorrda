# Hi, I'm Jordan 👋

Software engineer (2 years) who ships production systems end to end. I work deepest in **backend architecture, databases, and cloud infrastructure** (reactive Kotlin/Spring services, Python serverless on AWS, and PostgreSQL), and I'm comfortable carrying a feature from a schema migration all the way to the UI.

- 🔭 Going deep on distributed systems, PostgreSQL internals, and AWS infrastructure
- 🛠️ Range: Angular web apps, Flutter mobile, and embedded / computer-vision pipelines (OAK cameras, Raspberry Pi, Arduino)
- ✍️ I tend to write the architecture docs and runbooks the rest of the team onboards from
- 📫 Jordan D. Rom(https://www.linkedin.com/in/jordaa/) · jordan@alvanos.co(mailto:your-email@example.com)

---

### Core stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**Also work with:**
![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white) ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)

---

### Selected work

**Serverless data platform + reactive backend:** Designed a reusable API-driven async-job orchestrator and ~8 net-new AWS Lambda services (SAM IaC, CircleCI dev/prod pipelines), fronted by a Kotlin / Spring WebFlux + R2DBC service over PostgreSQL, with Testcontainers integration tests pinning the persistence contract.

**A distributed IoT system, architected solo:** A complete, implementable design spanning an embedded Arduino rig, a Python edge agent, AWS serverless (SQS / Lambda / EventBridge), Postgres / Flyway, and a Spring API, with idempotency at every layer, dead-letter queues, and full failure-recovery runbooks.

**Database performance and correctness:** `EXPLAIN`-driven tuning (cut an N+1 from 250+ round-trips to 3 queries; fixed a 4.8M-row scan), audit / event-sourced history tables written atomically, and batched idempotent upserts that protect RDS under load.

**Production hardening:** Found and fixed a fail-open authorization bug that had silently disabled access control, authored a 37-finding security audit, and regularly parachute in to land tested, documented root-cause fixes in large unfamiliar codebases.

---

### GitHub Stats

![Stats](https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&hide_border=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&hide_border=true)
