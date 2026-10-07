# Shabdan Kuldanbaev

Frontend engineer. Five years of product development in fintech and enterprise, all in TypeScript.

At a bank I own the frontend platform — microfrontends, a monorepo, shared standards that the linter and CI enforce — and client-side security, checked against OWASP ASVS L3. I run technical audits, lead code reviews and mentor developers. Outside work I ship products solo, from requirements to production.

### Work

- **Platform.** Monorepo, independently deployed microfrontends, design system in Storybook. A shared rules package rolls one standard out to Next.js, Nuxt and SvelteKit teams, so conventions are enforced, not re-argued in review.
- **Security.** Sessions in httpOnly / SameSite / Secure cookies, CSP and security headers, XSS and CSRF protection, masking of sensitive data in UI and logs.
- **BFF.** A typed layer that aggregates services and returns screen-shaped JSON. Secrets stay on the server; the browser only sees a session cookie.
- **Migrations.** Nuxt 2 → 4, Vue 2 + Vuex → Vue 3 + Pinia, Redux Toolkit → TanStack Query, Next.js 12 → 15. Audit first, TDD at every step, QA acceptance before release.
- **Delivery.** Feature flags separate deploy from release. Pre-push hooks for types and unit tests, e2e and coverage gates in CI. If it fails, the branch does not merge.
- **Tooling.** Custom Claude Code skills and plugins: codemods for migrations, FSD module scaffolding, test generation. Migration steps take hours instead of days.

### Projects

- [srws.net](https://srws.net) — wine and spirits catalog for a boutique in Bishkek, built solo from requirements to production. Next.js 16, React 19, Payload CMS 3, PostgreSQL, Tailwind CSS 4. Orders go to a Telegram bot and email, media on Cloudflare R2, 15 Playwright e2e suites. Source is private.
- [Jash-Muun](https://github.com/shabdan-kuldanbaev/JASH_MUUN) — digital exhibition of the intangible cultural heritage of Kyrgyz mountain communities, supported by ALIPH and EU grants. SvelteKit 2, Svelte 5, DatoCMS over GraphQL, four languages.

### Stack

TypeScript · React / Next.js · Vue / Nuxt · SvelteKit · TanStack Query · Pinia · Zustand · Zod · Payload CMS · PostgreSQL · Tailwind CSS · Vitest · Playwright · Storybook · Docker · GitLab CI · GitHub Actions

### Contact

[work.shabdan274@gmail.com](mailto:work.shabdan274@gmail.com) · [LinkedIn](https://www.linkedin.com/in/shabdan-kuldanbaev-43a154237/) · [Telegram](https://t.me/noxiousbrainiac)
