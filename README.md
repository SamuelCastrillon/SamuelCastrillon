## Hi, I'm Samuel Castrillón 👋

> 🇪🇸 ¿Buscas la versión en español? → [README-es.md](./README-es.md)

**Software developer · Open-source creator · Architecture-first**

I build production web and mobile applications with clean architecture, domain-driven design, and practical AI-augmented workflows.

### Now

- **Open to work** — seeking part-time remote full-stack roles (TypeScript, React, Next.js, Node.js)
- Building [Sechel](https://sechel.vercel.app/) — open-source MCP memory server for AI coding agents (CLI published, deployable server in progress)
- Exploring Go, MCP ecosystems, and architecture patterns

### How I build

I practice **Domain-Driven Design**, **Hexagonal Architecture**, and **Screaming Architecture** — where the folder structure alone documents what the application does. Framework code lives in adapters; domain logic stays pure, isolated, and testable. I believe foundations matter more than frameworks.

### Open source

**[OrbisPrismMCP](https://github.com/OrbisFactory/OrbisPrismMCP)** — Creator and maintainer.

MCP server that indexes decompiled Java codebases for AI-agent navigation. Replaces context-window burnout from file reads with structured SQLite queries.

- [2,500+ downloads on PyPI](https://pypi.org/project/orbis-prism-mcp/) · ~86/month and growing
- Hexagonal architecture with domain/application/infrastructure/ports layers
- 14 MCP tools: FTS5 search (unicode61 + trigram), class hierarchy, call flow analysis, pattern detection, and more
- Dual transport: stdio for local agents, SSE for remote/network use
- CI/CD with GitHub Actions

**[Sechel](https://github.com/SamuelCastrillon/Sechel)** — MCP memory server for AI coding agents.

Monorepo with a published local CLI (SQLite), a standalone deployable MCP server (in progress, Turso), and an admin panel. Presentation SPA at [sechel.vercel.app](https://sechel.vercel.app/) ([source](https://github.com/SamuelCastrillon/Sechel-spa)).

- 97 tests · Open source
- Designed for cross-session agent context recovery
- Serverless-first by design (also Docker-deployable)
- Admin panel framework TBD (evaluating Preact, Nuxt, or alternatives)

### Experience

| Period | Role | Project |
|--------|------|---------|
| Sep 2024 – Jul 2026 | Web Developer / Technical Owner | **Jodify** — Next.js 15 platform serving ~10k weekly users. Led React-to-Next.js migration, Screaming Architecture rebuild, authentication, design system, and SEO. Also contributed to the NestJS API (PostgreSQL, AWS Lambda) and React Native mobile app. |
| Jun 2025 – Present | Sole Developer & Architect | **MesaFlow / Reddere** — Multi-tenant SaaS POS for restaurants. Hexagonal architecture with Nuxt 3, NestJS, PostgreSQL, Drizzle ORM. Argon2id auth, tenant isolation, integration testing with PGlite. |
| 2025 – Present | Creator & Developer | **OrbisPrismMCP** — 2,500+ PyPI downloads, MCP server for codebase navigation. |

### Stack

| Area | Technologies |
|------|-------------|
| **Web** | Next.js, React, Nuxt 3, Vue, TypeScript, Tailwind CSS |
| **Backend** | NestJS, Node.js, Go, PostgreSQL, Drizzle ORM |
| **Architecture** | DDD, Hexagonal, Screaming Architecture, Clean Architecture |
| **Mobile** | Expo, React Native |
| **AI & MCP** | MCP Server design, LLM orchestration, agent tooling |
| **Cloud** | AWS Lambda, S3, Cloudflare, Vercel, Turso |
| **Testing** | Vitest, PGlite, Supertest, integration testing discipline |

### Contact

[Email](mailto:samcastj@gmail.com) · [LinkedIn](https://www.linkedin.com/in/samuel-castrill%C3%B3n/) · [Sechel](https://sechel.vercel.app/)

If you're building developer tools, MCP ecosystems, or SaaS products — I'd love to hear what you're working on.
