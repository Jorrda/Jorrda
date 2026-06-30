# Hi, Jordan here 👋

Software Engineer (2 years) shipping production systems end to end, from schema and infrastructure through the API to the UI. I'm comfortable across the whole stack and tend to go wherever the hard problem is, whether that's a reactive Kotlin/Spring backend, a PostgreSQL query plan, an Angular app, or an embedded computer-vision rig.

- 🔭 Going deep on distributed systems, PostgreSQL internals, and AWS infrastructure
- 🏗️ I design the APIs and the service contracts between them, and write the architecture specs before the code
- 🤖 Heavy AI-augmented workflow (Claude Code, with a spec-and-plan-first loop before I implement)
- 🛠️ Range from web (Angular) to mobile (Flutter) to embedded and computer vision (OAK, Raspberry Pi, Arduino)
- 📫 https://www.linkedin.com/in/jordaa/

---

### Tech

**Languages:** ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat&logo=gnubash&logoColor=white)

**Frontend:** ![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white) ![NgRx](https://img.shields.io/badge/NgRx-BA2BD2?style=flat) ![RxJS](https://img.shields.io/badge/RxJS-B7178C?style=flat&logo=reactivex&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)

**Backend:** ![Spring](https://img.shields.io/badge/Spring-6DB33F?style=flat&logo=spring&logoColor=white) ![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white) ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)

**Mobile:** ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart&logoColor=white)

**Data:** ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat&logo=flyway&logoColor=white)

**Cloud & DevOps:** ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white) ![CircleCI](https://img.shields.io/badge/CircleCI-343434?style=flat&logo=circleci&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**Embedded & Computer Vision:** ![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-A22846?style=flat&logo=raspberrypi&logoColor=white) ![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat&logo=arduino&logoColor=white) ![OAK / DepthAI](https://img.shields.io/badge/OAK%20%2F%20DepthAI-FF6A00?style=flat) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)

---

### Selected work

**Serverless data platform + reactive backend:** Designed a reusable, API-driven async-job orchestrator and ~8 net-new AWS Lambda services (SAM IaC, CircleCI dev/prod pipelines), fronted by a Kotlin / Spring WebFlux + R2DBC service over PostgreSQL, with Testcontainers integration tests pinning the persistence contract.

**A distributed IoT system, architected solo:** A complete, implementable design spanning an embedded Arduino rig, a Python edge agent, AWS serverless (SQS, Lambda, EventBridge), Postgres with Flyway migrations, and a Spring API. Idempotency at every layer, dead-letter queues, explicit service contracts, and a full failure-recovery runbook.

**Embedded and computer vision:** Brought up OAK (DepthAI) cameras and a custom Arduino XY scanning rig, including a safety state machine I re-architected after diagnosing a motor-damaging failure mode, autofocus calibration with a brightness-robust sharpness metric, and from-zero deployment runbooks for the edge-device fleet (Raspberry Pi and Compute Module, on Tailscale).

**Database performance and correctness:** `EXPLAIN`-driven tuning (cut an N+1 from 250+ round-trips to 3 queries; fixed a 4.8M-row scan), audit and event-sourced history tables written atomically, and batched idempotent upserts that protect RDS under load.

**Production hardening:** Found and fixed a fail-open authorization bug that had silently disabled access control, authored a 37-finding security audit, and regularly parachute into large unfamiliar codebases to land tested, documented root-cause fixes.

---

### GitHub Stats

![Stats](https://github-readme-stats.vercel.app/api?username=Jorrda&show_icons=true&hide_border=true&count_private=true&include_all_commits=true)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=Jorrda&layout=compact&hide_border=true)
