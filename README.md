# Zé Delivery Backend Challenge

This repository contains a **production-ready starter solution** for the Zé Delivery Backend Challenge, focused on **correctness, performance, testability, and clean architecture**.

---

## Tech Stack

- **Node.js + TypeScript**
- **PostgreSQL + PostGIS** (GIS operations)
- **Express** (HTTP API)
- **Jest + Supertest** (testing)
- **Docker & Docker Compose** (local execution)

---

## Project Structure

.
├── docker-compose.yml
├── Dockerfile
├── package.json
├── tsconfig.json
├── README.md
└── src
├── domain
│   └── partner.ts
├── application
│   ├── create-partner.usecase.ts
│   ├── get-partner.usecase.ts
│   └── search-partner.usecase.ts
├── infrastructure
│   ├── db
│   │   ├── connection.ts
│   │   └── partner.repository.ts
│   └── http
│       ├── partner.controller.ts
│       └── routes.ts
├── main
│   └── server.ts
└── tests
├── unit
└── integration
