# Hi, I'm Heron Amaral 👋

**Backend developer.** I build APIs and real-time systems in NestJS and TypeScript, take care of the infrastructure they run on, and write down why each decision was made. Based in Belém, Brazil, working remotely.

Before changing code, I measure. Before trusting data, I query the database.

[![Portfolio](https://img.shields.io/badge/heronoa.com.br-15131D?style=for-the-badge&logoColor=white)](https://heronoa.com.br)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/heron-amaral-49a9a1179/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:heron.amaral@gmail.com)

## Now

- 🎮 **[eldritch-alley](https://github.com/heronoa/eldritch-alley)**: browser-based, turn-based tactics game on isometric city maps with elevation. *Early development, built in public.*
  - Deterministic battle engine in plain TypeScript: seeded RNG, integer-only math, matches as event streams (replays and reconnection by replaying events)
  - Server-authoritative multiplayer with Colyseus; NestJS platform API for accounts, rating and match history; rating-based matchmaking on Redis
  - Phaser client with pixel art; backend on AWS (ECS behind a load balancer), frontend on Cloudflare
- 🌐 **[heronoa.com.br](https://heronoa.com.br)**: my portfolio, with case studies told as replays. Static site on Cloudflare, deployed by GitHub Actions ([source](https://github.com/heronoa/heron-portfolio)).

## Selected projects

| Project | What it shows |
|---|---|
| [kanban-api](https://github.com/heronoa/kanban-api) | NestJS, Prisma and PostgreSQL organized in use cases and repositories, with integration tests against a real PostgreSQL in CI |
| [ait-manager](https://github.com/heronoa/ait-manager) | NestJS API with an SQS producer and consumer |
| [turnbased-pvp-colyseus](https://github.com/heronoa/turnbased-pvp-colyseus) | Real-time turn-based battle server with matchmaking and a bot fallback, plus a [Vue client](https://github.com/heronoa/vuejs-turnbased-game) |
| [payments-api](https://github.com/heronoa/payments-api) | Express and MongoDB with scheduled jobs, S3 uploads and email and WhatsApp notifications |

The 2024 projects were written as study projects, without AI assistance.

## In short

- Backend and infrastructure for a SaaS platform used by public school networks: single sign-on with Keycloak, load testing with k6, 110+ end-to-end tests, Terraform on GCP.
- Three and a half years at a Web3 games company, from junior to mid-level: real-time game backends, Redis, AWS.
- Studying Systems Analysis and Development, after CS50 and Zero To Mastery.

## Stack

**Backend:** Node.js, TypeScript, NestJS, Express, REST, WebSockets

**Data:** PostgreSQL, Redis, MongoDB, TypeORM, Prisma

**Messaging:** AWS SQS and SNS, RabbitMQ

**Infrastructure:** Docker, Terraform, AWS, GCP, Cloudflare, GitHub Actions, Grafana

**Testing:** Jest, Vitest, Cypress, k6
