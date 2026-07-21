## Hola, soy Samuel Castrillón 👋

> 🇬🇧 Read this in English → [README.md](./README.md)

**Desarrollador de software · Creador de código abierto · Enfoque en arquitectura**

Construyo aplicaciones web y mobile en producción con arquitectura limpia, domain-driven design y flujos prácticos asistidos por IA.

### Ahora

- **Buscando trabajo** — ofertas part-time remoto como full-stack (TypeScript, React, Next.js, Node.js)
- Desarrollando [Sechel](https://sechel.vercel.app/) — servidor MCP open-source para memoria de agentes de IA (CLI publicado, servidor desplegable en desarrollo)
- Explorando Go, ecosistemas MCP y patrones de arquitectura

### Cómo construyo

Practico **Domain-Driven Design**, **Arquitectura Hexagonal** y **Screaming Architecture** — donde la estructura de carpetas por sí sola documenta lo que la aplicación hace. El código de framework vive en adaptadores; la lógica de dominio se mantiene pura, aislada y testeable. Creo que los fundamentos importan más que los frameworks.

### Código abierto

**[OrbisPrismMCP](https://github.com/OrbisFactory/OrbisPrismMCP)** — Creador y mantenedor.

Servidor MCP que indexa codebases Java decompilados para navegación asistida por IA. Elimina la saturación de contexto reemplazando lecturas de archivo con consultas estructuradas a SQLite.

- [2,072 descargas en PyPI](https://pypi.org/project/orbis-prism-mcp/) · ~200/mes y creciendo
- Arquitectura hexagonal con capas de dominio/aplicación/infraestructura/puertos
- 14 herramientas MCP: búsqueda FTS5 (unicode61 + trigram), jerarquía de clases, análisis de flujo de llamadas, detección de patrones y más
- Transporte dual: stdio para agentes locales, SSE para uso remoto
- CI/CD con GitHub Actions

**[Sechel](https://github.com/SamuelCastrillon/Sechel)** — Servidor MCP para memoria de agentes de IA.

Monorepo con un CLI local publicado (SQLite), un servidor MCP standalone desplegable (en desarrollo, Turso) y un panel de administración. SPA de presentación en [sechel.vercel.app](https://sechel.vercel.app/) ([source](https://github.com/SamuelCastrillon/Sechel-spa)).

- 97 tests · Código abierto
- Diseñado para recuperación de contexto entre sesiones de agente
- Diseñado serverless-first (también desplegable en Docker)
- Framework del panel de admin por decidir (evaluando Preact, Nuxt u otras opciones)

### Experiencia

| Período | Rol | Proyecto |
|---------|-----|----------|
| Sep 2024 – Jul 2026 | Web Developer / Technical Owner | **Jodify** — Plataforma Next.js 15 con ~10k usuarios semanales. Lideré la migración React-a-Next.js, la re-arquitectura a Screaming Architecture, autenticación, design system y SEO. También contribuí a la API NestJS (PostgreSQL, AWS Lambda) y la app móvil React Native. |
| Jun 2025 – Presente | Sole Developer & Architect | **MesaFlow / Reddere** — SaaS POS multi-tenant para restaurantes. Arquitectura hexagonal con Nuxt 3, NestJS, PostgreSQL, Drizzle ORM. Autenticación con Argon2id, aislamiento multi-tenant, tests de integración con PGlite. |
| 2025 – Presente | Creador & Developer | **OrbisPrismMCP** — 2,500+ descargas PyPI, servidor MCP para navegación de codebases. |

### Stack

| Área | Tecnologías |
|------|-------------|
| **Web** | Next.js, React, Nuxt 3, Vue, TypeScript, Tailwind CSS |
| **Backend** | NestJS, Node.js, Go, PostgreSQL, Drizzle ORM |
| **Arquitectura** | DDD, Hexagonal, Screaming Architecture, Clean Architecture |
| **Mobile** | Expo, React Native |
| **IA y MCP** | Diseño de servidores MCP, orquestación de LLMs, tooling para agentes |
| **Cloud** | AWS Lambda, S3, Cloudflare, Vercel, Turso |
| **Testing** | Vitest, PGlite, Supertest, disciplina de integración |

### Contacto

[Email](mailto:samcastj@gmail.com) · [LinkedIn](https://www.linkedin.com/in/samuel-castrill%C3%B3n/) · [Sechel](https://sechel.vercel.app/)

Si estás construyendo developer tools, ecosistemas MCP o productos SaaS — me encantaría saber en qué estás trabajando.
