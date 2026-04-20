# Logan Freeman

Building open infrastructure for running AI agents in production — signed
receipts, auditable metering, and the protocols that sit on top. Works with
any model provider.

## What I build

Three open protocols for AI API commerce and governance:

- **[cognitive-meter](https://github.com/Stray-South/cognitive-meter-public)** —
  Signed receipts for AI API calls. Ed25519 + SHA-256 hash chain, language-neutral
  schema, works with Anthropic, OpenAI, Gemini, or any OTel-instrumented provider.
  Apache 2.0.
- **[cognitive-meter-verify](https://github.com/Stray-South/cognitive-meter-verify)** —
  Zero-dependency browser demo of the receipt verification chain.
  [Live demo →](https://stray-south.github.io/cognitive-meter-verify/)
- **[WESUMN architecture](https://github.com/Stray-South/wesumn-public)** —
  Design rationale for the production platform running the above in a dual-mode
  (Tauri desktop + web SaaS) AI agent governance system.
- Payment (x402-gateway) and lifecycle (commerce-402) protocols are in staged
  release — running in production at WESUMN, publishing publicly after the
  current beta cycle.

## Running in production

These aren't hypothetical protocols. They run in [WESUMN](https://wesummonit.com),
a cognitive AI agent monitoring and governance platform with real compliance
obligations (EU AI Act, Colorado SB-205). The public specs and demo are extracted
from that production system.

## Stack I ship with

- **Frontend** — React 19, TypeScript, Vite 7, Tailwind 4
- **Desktop** — Tauri 2, Rust
- **API** — Hono on Node, Drizzle ORM, Postgres 15
- **Cognitive engine** — FastAPI, Python 3.11
- **Auth / Billing** — Clerk, Stripe
- **Infra** — Render, Vercel, Docker

## What I care about

- **Accessibility as a design constraint**, not a post-launch patch. WCAG 2.2 AA, AuDHD-first defaults, keyboard-first flows.
- **Auditable systems.** If someone asks "how did you charge me that" or "how do you know the agent did what it claimed," I want the answer to be a signed, hash-chained receipt — not trust.
- **Compliance as product.** EU AI Act, Colorado SB-205, HIPAA exports generated from the same events the UI reads.

## Contact

- ljfreeman83@gmail.com
- [LinkedIn](https://www.linkedin.com/in/loganfreemanai)
- [wesummonit.com](https://wesummonit.com)
