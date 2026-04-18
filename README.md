# Logan Freeman — Stray South

Founder-operator building governance and observability tools for AI agents.

I design, ship, and operate AI systems end-to-end: architecture, product, compliance posture, and the unglamorous bits like CI, env hygiene, and audit trails. Current focus is **WESUMN** — a desktop + web SaaS platform for cognitive AI agent monitoring — with a separate open spec, `cognitive-meter`, for signed AI API receipts.

## Current focus

**WESUMN** at [wesummonit.com](https://wesummonit.com) — cognitive AI agent monitoring and governance. Behavioral fingerprinting, drift detection, a signed receipt chain for every agent action, and compliance exports for the EU AI Act, Colorado SB-205, HIPAA, and education-sector rules.

- Public architecture + design notes: [wesumn-public](https://github.com/Stray-South/wesumn-public)
- Signed-receipt spec for AI API calls: [cognitive-meter](https://github.com/Stray-South/cognitive-meter-public)

## Stack I ship with

- **Frontend** — React 19, TypeScript, Vite 7, Tailwind 4
- **Desktop** — Tauri 2, Rust
- **API** — Hono on Node, Drizzle ORM, Postgres 15
- **Cognitive engine** — FastAPI, Python 3.11
- **Auth / Billing** — Clerk, Stripe
- **Infra** — Render, Vercel

## What I care about

- **Accessibility as a design constraint**, not a post-launch patch. WCAG 2.2 AA, AuDHD-first defaults, keyboard-first flows.
- **Auditable systems.** If someone asks "how did you charge me that" or "how do you know the agent did what it claimed," I want the answer to be a signed, hash-chained receipt — not trust.
- **Compliance as product.** EU AI Act, Colorado SB-205, HIPAA exports generated from the same events the UI reads.
- **Single source of truth.** Code, spec, CI, deploy config, and docs should all describe the same system.

## Also online

- Product — [wesummonit.com](https://wesummonit.com)
- LinkedIn — [linkedin.com/in/loganfreemanai](https://www.linkedin.com/in/loganfreemanai/)
- Email — ljfreeman83@gmail.com

---

*Most of my day-to-day code lives in private repos. The public ones here are deliberate slices — architecture, specs, and writing — meant to show how I think and ship.*
