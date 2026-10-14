# Nasim Sawalma

**Next.js / React developer working with AI agents.** I build and run production websites, from the database to the deployment, and I ship them with an agentic workflow: specs first, separate agents for implementation, tests and review, CI on every pull request, and every decision written down.

*Développeur Next.js / React basé à Lille. Je conçois, livre et maintiens des sites en production, avec un workflow agentique : spécifications d'abord, agents aux rôles séparés, tests, revue et décisions tracées.*

---

### How I work

```
spec with acceptance criteria  ->  test-writer agent (tests from the spec, seen failing first)
                               ->  implementer agent (one spec, nothing else)
                               ->  reviewer agent (read-only, approve / changes needed)
                               ->  CI on the pull request  ->  human review and merge
                               ->  decision log
```

Guardrails are code, not instructions: hooks stop agents from reading credentials, touching production or editing their own rules. The full write-up, with the real agent definitions, is in **[agentic-workflow-case-study](https://github.com/Nomac09/agentic-workflow-case-study)**.

---

### Selected work

| Project | What it is | Stack |
|---|---|---|
| [ladonnadiferro.com](https://ladonnadiferro.com) | Full migration of a fashion label from Wix to Next.js, then a phased upgrade run with the workflow above ([case study](https://github.com/Nomac09/agentic-workflow-case-study)) | Next.js App Router, TypeScript, Supabase, Stripe, Vitest, Playwright, GitHub Actions |
| [Gulf PR Atlas](https://gulfpr.org) ([code](https://github.com/Nomac09/gulfpr)) | Open-data reference on 20 Gulf PR agencies: maps, network graph, heatmap. Nothing published without a source | Next.js, TypeScript, Vercel |
| [Sesame](https://sesamerestaurant.fr) ([code](https://github.com/Nomac09/sesame)) | Ordering site for a delivery kitchen: Stripe payments and webhooks, transactional email, row-level security, accessibility tests | Next.js, Supabase, Stripe, Resend, Playwright |
| [Souqify](https://souqify.fr) ([code](https://github.com/Nomac09/souqify)) | E-commerce store connected to a supplier API: token auth, rate-limited client, automatic order forwarding, delivery tracking | Next.js, MongoDB, Stripe |
| [Aani pay prototype](https://github.com/Nomac09/aani-pay-prototype) | Concept for paying tenant invoices through Aani, the UAE instant payment rail | Next.js, Tailwind, Framer Motion |
| [gazahope.org](https://gazahope.org) | Donation platform built in under ten days and run in production for two and a half years | Next.js, Supabase, Vercel |

---

### Stack

**Front-end:** React, Next.js (App Router, Server Components), TypeScript, Tailwind CSS, accessibility, SEO
**Back-end and data:** Supabase (PostgreSQL, RLS), MongoDB, REST APIs, webhooks, Stripe, Resend
**Quality:** Vitest, Playwright, ESLint, Prettier, GitHub Actions, pull-request reviews
**AI:** Claude Code, Cursor, multi-agent workflows, spec-driven development
**Learning now:** GraphQL, NestJS, Svelte

---

[LinkedIn](https://www.linkedin.com/in/nasim-sawalma) · nasim.sawalma@gmail.com · Lille, France
