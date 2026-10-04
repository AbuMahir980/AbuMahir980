# 👋 Hi, I'm Qudus Adebola Lawal

**Frontend Engineer — React, TypeScript & React Native · 📍 Lagos, Nigeria**

I build React and TypeScript products that have to behave under real conditions: data-heavy operational dashboards, customer-facing web apps, enrolment and payment flows, and the shared frontend foundations that keep several products consistent. I'm the creator of [Peer AI](https://github.com/AbuMahir980/peer-ai), an open-source tool that holds AI coding assistants to an engineering process ([on npm](https://www.npmjs.com/package/peer-ai)), and I'm currently using it to build a React Native and Expo app for a travel start-up.

[![React](https://img.shields.io/badge/React_19-20232a?style=flat-square&logo=react&logoColor=61DAFB)](#)
[![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)](#)
[![React Native](https://img.shields.io/badge/React_Native-20232a?style=flat-square&logo=react&logoColor=61DAFB)](#)
[![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)](#)
[![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)](#)
[![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)](#)

---

## 🛠️ What I work on

📊 **Operational dashboards that stay honest under load.** Telemetry views with polling, severity-based prioritisation, device drill-downs and map layers — and, when a date-range filter across several views was taking minutes and returning partial data, prefetching 90 days of telemetry into TanStack Query's cache so the same filter is instant with a background refresh.

💳 **Customer flows where the money has to be right.** Enrolment, eligibility rules, checkout and post-payment access, built with explicit initiation, pending, success, failure and recovery states — so a user is never left guessing whether a payment went through.

🧱 **Frontends owned end to end, on shared foundations.** I own product frontends end to end — component architecture, state, data fetching and delivery — as part of wider, distributed remote teams. I standardise typed API models, HTTP clients, authentication handling and status logic so every surface behaves the same way.

🚦 **Explicit states, not spinners.** Loading, empty, stale, offline, not-found, alarm and failure are designed on purpose, so an operator can tell a system problem from a device or data problem.

🧪 **Validation with real people.** I test products end to end through real user workflows, onboard and observe pilot users, and turn what they struggle with into reproducible defects and acceptance criteria before customers are admitted.

📱 **A mobile app built to the pixel, with AI agents under my direction.** On a React Native/Expo travel app I set the architecture and the rules, and AI coding agents working under Peer AI implement each piece against written acceptance criteria; I review every change before it merges. The design system — tokens from one design file, ~40 shared components with every state — and a Playwright screenshot diff against the Expo web build keep every screen within 0.05% of its design; an offline outbox replays queued expenses in order with idempotent requests, so a retry never records twice. The reviews have caught what tests passed: four money bugs and a rate-limit bypass, before launch.

---

## ⭐ Featured

### 🤖 [Peer AI](https://github.com/AbuMahir980/peer-ai) — keeps AI coding tools to the standard of a careful senior team, and proves it

AI coding tools write code fast and skip what makes software safe to ship. Peer AI gives every AI tool the same way of working — written plans, acceptance criteria, rules and reviews — checks that each was followed, and refuses work whose record the evidence doesn't support.

- 📦 **One npm package, any AI tool.** `peer-ai init` reads the repository and writes one config; `render` sets up Claude Code, Codex, Cursor, GitHub Copilot and Gemini CLI from it; an MCP server gives the tool its next piece of work and the rules for the file in hand. [npmjs.com/package/peer-ai](https://www.npmjs.com/package/peer-ai)
- 📚 **29 skills, 197 rules.** Step-by-step procedures for requirements, architecture, threat modelling, security, privacy, accessibility, performance, releases and more, with rules built on OWASP ASVS/MASVS and WCAG 2.2: 46 enforced by tools that fail the build, 148 by reviews that must cite evidence, 3 by a person.
- ✅ **A CI gate that wants proof.** `peer-ai check` fails a pull request whose work isn't verified and reviewed against the commit about to merge. Works with parallel agents in separate git worktrees.
- 📏 **Measured, not promised.** On the same model, a pre-launch release check found 12 of 12 planted problems with Peer AI against 8 without; every run and its cost is published in `evals/`.
- 🧱 **Built in the open.** AI coding agents implement each piece against written acceptance criteria; I set the architecture and the rules, and review every change before it merges. TypeScript, ~29,000 lines across five packages, 659 tests, CI on Linux, macOS and Windows; 18 RFCs; npm trusted publishing with signed provenance.

Pre-release, in daily use on a client codebase. Started in June 2026 as a Markdown playbook, rewritten from September 2026 as the package.

### 💰 [Mizaniya](https://github.com/AbuMahir980/mizaniya) — budgeting by salary day, not calendar month

A local-first budgeting PWA for people paid in salary cycles — debts in both directions, a rent sinking fund, no server, no accounts. React 19, TypeScript, Tailwind. The money logic lives in a framework-free core (integer kobo with a branded type, every figure a pure function of the transactions) behind a Repository over IndexedDB, so a React Native version can share it. Designed before it was built — a token-based design system and 67 artboards — with module boundaries enforced by lint and 288 tests. Built in the open with Peer AI — agents implement, I set the design system, the architecture rules and the acceptance criteria, and review every change. v1 in progress.

---

## 🧭 How I work

- 🗺️ Understand the product before touching the code: map screens, workflows, dependencies and the API surface first.
- 🚨 Make the risks visible early — architecture, security and data-integrity gaps go into a defect register, not a mental note.
- 📐 Set clear standards, then build in small testable pieces.
- ✅ Verify through real user flows, not just the happy path.
- 🔐 Review code and apply security guardrails (role and resource access, secrets, session handling, payment idempotency) as part of delivery, not after it.
- 🤝 Use AI coding agents as a force multiplier, not a replacement: I set the architecture and acceptance criteria, split work into parallel streams, and review and integrate everything they produce.

---

## 🧰 Stack

| | |
|---|---|
| ⚛️ **Frontend** | React 19, TypeScript, JavaScript (ES6+), React Native / Expo, HTML5, CSS3, Tailwind CSS, Chakra UI, shadcn/ui |
| 🏗️ **Architecture & state** | TanStack Query, Zustand, Context API, design systems and tokens, shared component libraries |
| 🔗 **APIs & workflows** | REST, Axios, JWT/OTP authentication, role-based interfaces, forms and validation, Paystack, Node.js/Express and FastAPI (working knowledge) |
| 📈 **Data & interface quality** | Recharts, MapLibre GL, GeoJSON, loading/empty/error/retry states, accessibility, responsive QA |
| 🚀 **Testing & delivery** | Vitest, Jest, React Testing Library, Playwright, Bruno, Git, GitHub Actions, Vite, ESLint |
| 🤖 **AI-assisted development** | Peer AI (creator), Claude Code, parallel agents in git worktrees, review-gated delivery |
| 📚 **Learning now** | Application security: OWASP, secure coding, threat modelling |

---

## 🌱 Currently

Building a React Native/Expo travel app for a start-up with AI agents under my direction, and shipping Peer AI 1.0 pre-releases from what that project teaches. Mizaniya is being built in the open the same way.

---

## 🌍 Elsewhere

🌐 **Portfolio** → [qudus-portfolio.netlify.app](https://qudus-portfolio.netlify.app/) · 💼 **LinkedIn** → [qudus-lawal-adebola](https://www.linkedin.com/in/qudus-lawal-adebola/) · ✉️ **Email** → [lawalqudus980@gmail.com](mailto:lawalqudus980@gmail.com)

💬 Open to frontend, React and React Native work — full-time and freelance.
