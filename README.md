### Aleksa Dragnić
**Backend Software Engineer** | C#, .NET, ASP.NET Core · Node.js, TypeScript · PostgreSQL

I design, build and run production backend services. For over two years I have been the sole engineer of two live chess platforms (Node.js, PostgreSQL, Stripe). In .NET I build in the open:

| Project | What it shows | Live |
|---|---|---|
| [UserManagementAPI](https://github.com/aleksa-dragnic/UserManagementAPI) | .NET 10 REST API for users, roles and permissions: clean architecture, CQRS, domain events, outbox, rotating refresh tokens, OpenTelemetry, 371 tests with Testcontainers, 21 ADRs | [API docs](https://api.aleksadragnic.com/scalar) |
| [Umapi-Console](https://github.com/aleksa-dragnic/Umapi-Console) | React 19 and TypeScript admin console for the API, with Vitest and Playwright tests | [console.aleksadragnic.com](https://console.aleksadragnic.com) |

**At work (code is private, happy to walk through the architecture):**
- Cut database time per request by 50% while traffic doubled; critical queries from 270 ms to 12 ms
- Built Stripe subscription billing end to end: renewals, idempotent webhooks, refunds, vouchers
- Built a broker that rents cloud CPU machines on demand, with price ceilings and spend limits
- Zero-downtime releases backed by 1,600+ automated tests

**Stack:** C#, .NET, ASP.NET Core, EF Core, Node.js, Express, TypeScript, React, PostgreSQL, Redis, Stripe, Docker, Nginx, Linux

Open to remote backend roles · CET · [LinkedIn](https://www.linkedin.com/in/aleksa-dragnic) · aljosadragnic@gmail.com
