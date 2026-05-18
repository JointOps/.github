# JointOps

**We build open source developer infrastructure — fast, minimal, and production-ready.**

JointOps is an open source organization building tools that Node.js and Bun developers actually want to use. We obsess over performance, zero-dependency design, and developer experience.

---

## Open Source Projects

### ⚡ [hitlimit](https://github.com/JointOps/hitlimit-monorepo) — Rate Limiting for Node.js & Bun

> The fastest rate limiter for Node.js & Bun. A modern alternative to `express-rate-limit`.

- **7M+ ops/sec** on Bun, **5.96M+ ops/sec** on Node.js
- 8 built-in storage backends (Memory, Redis, SQLite, Postgres, MongoDB, MySQL, Valkey, DragonflyDB)
- Supports Express, Fastify, Hono, NestJS, Bun.serve, Elysia — one API across all frameworks
- Built-in tiered limits for SaaS (Free / Pro / Enterprise in one config)
- ~8KB core, zero dependencies

```bash
npm i @joint-ops/hitlimit       # Node.js
bun add @joint-ops/hitlimit-bun  # Bun
```

[![Docs](https://img.shields.io/badge/Docs-hitlimit.jointops.dev-000000?style=flat-square)](https://hitlimit.jointops.dev) [![npm](https://img.shields.io/npm/v/@joint-ops/hitlimit?style=flat-square&logo=npm&logoColor=white&label=npm)](https://www.npmjs.com/package/@joint-ops/hitlimit) [![Discussions](https://img.shields.io/badge/Discussions-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/JointOps/hitlimit-monorepo/discussions)

---

### 🚀 [bunway](https://github.com/JointOps/bunway) — Express-style Router for Bun

> Drop-in Express API compatibility for Bun. Same `req`, `res`, `next` — native Bun performance.

- Full Express.js API surface (routing, middleware, `req`/`res`/`next`)
- Built for Bun from the ground up
- Migrate Express apps to Bun without rewriting your routes

```bash
bun add bunway
```


[![Docs](https://img.shields.io/badge/Docs-bunway.jointops.dev-000000?style=flat-square)](https://bunway.jointops.dev) [![npm](https://img.shields.io/npm/v/bunway?style=flat-square&logo=npm&logoColor=white&label=npm)](https://www.npmjs.com/package/bunway) [![Discussions](https://img.shields.io/badge/Discussions-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/JointOps/bunway/discussions)

--- [kaput](https://github.com/JointOps/kaput) — Graceful Shutdown for Node.js

> Zero-config graceful shutdown handling. Stop losing in-flight requests on deploy.

- Handles `SIGTERM`, `SIGINT`, and uncaught exceptions
- Works with Express, Fastify, and raw Node.js HTTP servers
- Zero configuration required

```bash
npm i @joint-ops/kaput
```

[![Docs](https://img.shields.io/badge/Docs-kaput.jointops.dev-000000?style=flat-square)](https://kaput.jointops.dev) [![npm](https://img.shields.io/npm/v/@joint-ops/kaput?style=flat-square&logo=npm&logoColor=white&label=npm)](https://www.npmjs.com/package/@joint-ops/kaput)

---

## Our Philosophy

- **Performance is a feature.** We benchmark everything and publish the numbers openly.
- **Zero dependencies by default.** Your bundle shouldn't pay for our convenience.
- **Framework-agnostic.** Tools that work across your whole stack, not just one framework.
- **Production-first.** We build things we'd run in prod ourselves.

---

## Contributing

All our projects are open source under the MIT license. We welcome contributions of all kinds — bug reports, feature requests, documentation improvements, and pull requests.

Every repo has a `CONTRIBUTING.md` with setup instructions. The easiest way to start:

1. Browse [open issues](https://github.com/issues?q=is%3Aopen+is%3Aissue+org%3AJointOps) across all our repos
2. Join the conversation — [hitlimit discussions](https://github.com/JointOps/hitlimit-monorepo/discussions) · [bunway discussions](https://github.com/JointOps/bunway/discussions)
3. Pick something and send a PR — we review fast

---

## Connect

[![npm](https://img.shields.io/badge/npm-%40joint--ops-CB3837?style=flat-square&logo=npm&logoColor=white)](https://www.npmjs.com/~joint-ops)
[![Website](https://img.shields.io/badge/Website-jointops.dev-000000?style=flat-square)](https://jointops.dev)
[![Email](https://img.shields.io/badge/Email-hello%40jointops.dev-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:hello@jointops.dev)
[![Discussions](https://img.shields.io/badge/Discussions-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/orgs/JointOps/discussions)
---

<sub>© 2025–2026 JointOps · MIT License · Building things that actually work.</sub>
