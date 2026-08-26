# Dustin Tramm — dstN

Front End Developer in Hamburg, Germany. 10+ years building interfaces — Vue and Nuxt at work,
Astro and SvelteKit alongside it. Accessibility and privacy are where I spend the extra effort.

[**dstn.github.io**](https://dstn.github.io) · [all 19 projects](https://dstn.github.io/work/)

---

## Non-negotiables

**Accessibility is a gate, not a pass.** `@axe-core/playwright` runs in CI across every route,
theme and viewport — a failing audit blocks the deploy the same way a failing test does. bewerby
is audited against WCAG 2.2 **AAA**, not AA. When I wanted that check on everything, I built
Axie: a self-hosted Playwright + axe-core audit service whose reports are fully offline-capable,
base64 fonts and inline SVGs, no external requests.

**Privacy belongs in the architecture, not the cookie banner.** Where an app can work without a
backend, it does: bewerby keeps applications in IndexedDB and PDF attachments in OPFS, so there
is no account and no server-side database to breach. Twittr Archivr unzips and searches your
Twitter export in the browser — the file never leaves your machine. No CDN fonts anywhere, which
is exactly why `fli` exists. Where user data is unavoidable, GDPR export and erasure are built in
from the start rather than retrofitted.

## Shipping

| Project | What it is | Where |
| :--- | :--- | :--- |
| **GourMerge** | Git for recipes — branches, commits, forks and diffable merge requests | [gourmerge.de](https://gourmerge.de) |
| **bewerby** | Job application tracker that runs entirely in the browser. No account, no server-side database | [bewerby.de](https://bewerby.de) |
| **EuroDraft** | Draft an all-time XI from sixty years of tournament squads, then simulate the tournament | [ed.rntm.de](https://ed.rntm.de) · [source](https://github.com/dstN/EuroDraft) |
| **VSGraph** | German domestic-intelligence crime statistics, turned into a public dashboard | [vsgraph.de](https://vsgraph.de) |
| **footyguess** | Guess the footballer from progressively revealed career data | [footyguess.yinside.de](https://footyguess.yinside.de) |
| **Twittr Archivr** | Search a Twitter/X export locally — the parsing happens in your browser | [twittrarchivr.vercel.app](https://twittrarchivr.vercel.app) |
| **Threads Deleter** | Bulk-delete Threads posts via Meta's API. CLI and web dashboard off one core | [threadsdelete.vercel.app](https://threadsdelete.vercel.app) · [source](https://github.com/dstN/threadsDeleter) |

## On npm

- [**@dstn/fli**](https://www.npmjs.com/package/@dstn/fli) — downloads Google Webfonts locally and
  writes the `@font-face` CSS, so a site makes no CDN request for its type
- [**@dstn/remcss**](https://www.npmjs.com/package/@dstn/remcss) — pure-CSS framework built on the
  golden ratio. CSS Layers, `oklch()`, container queries, `@scope`, zero JS runtime

## Stack

| | |
| :--- | :--- |
| **Languages** | TypeScript, JavaScript, CSS, HTML, PHP, Python |
| **Frameworks** | Vue 3, Nuxt 4, Astro, SvelteKit (Svelte 5), React, Next.js, NestJS |
| **Templating** | Twig, MJML |
| **Styling** | Vanilla CSS with `oklch()` design tokens, CSS Layers, container queries, Tailwind CSS, SASS, Bootstrap |
| **CMS** | WordPress (Composer-managed block themes), Joomla, NEOS, Directus |
| **Backend** | Nitro/H3, Fastify, FastAPI, Express |
| **Data** | MySQL/MariaDB via Drizzle, SQLAlchemy 2.0, SQLite, IndexedDB + OPFS |
| **Testing** | Vitest, Playwright, @axe-core/playwright |
| **Tooling** | Git, Vite, Docker, DDEV, GitHub Actions, Figma |
