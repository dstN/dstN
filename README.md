# Dustin Tramm — dstN

Front End Developer in Hamburg, Germany. 10+ years building interfaces — mostly Vue and Nuxt,
increasingly Astro and SvelteKit — with a standing interest in accessibility, privacy by
architecture, and owning the deployment rather than renting it.

[**dstn.github.io**](https://dstn.github.io) · [all 19 projects](https://dstn.github.io/work/)

---

## Shipping

| Project | What it is | Where |
|:---|:---|:---|
| **GourMerge** | Git for recipes — branches, commits, forks and diffable merge requests | [gourmerge.de](https://gourmerge.de) |
| **bewerby** | Job application tracker that runs entirely in the browser. No account, no server-side database | [bewerby.de](https://bewerby.de) |
| **EuroDraft** | Draft an all-time XI from sixty years of tournament squads, then simulate the tournament | [ed.rntm.de](https://ed.rntm.de) · [source](https://github.com/dstN/EuroDraft) |
| **VSGraph** | German domestic-intelligence crime statistics, turned into a public dashboard | [vsgraph.de](https://vsgraph.de) |
| **footyguess** | Guess the footballer from progressively revealed career data | [footyguess.yinside.de](https://footyguess.yinside.de) |
| **Twittr Archivr** | Search a Twitter/X export locally — the parsing happens in your browser | [twittrarchivr.vercel.app](https://twittrarchivr.vercel.app) |
| **Threads Deleter** | Bulk-delete Threads posts via Meta's API. CLI and web dashboard off one core | [threadsdelete.vercel.app](https://threadsdelete.vercel.app) · [source](https://github.com/dstN/threadsDeleter) |
| **tower67** | 2D air-traffic-control game where mouse and voice feed one command pipeline | [source](https://github.com/dstN/tower67) |

## On npm

- [**@dstn/fli**](https://www.npmjs.com/package/@dstn/fli) — downloads Google Webfonts locally and
  writes the `@font-face` CSS, so a site makes no CDN request for its type
- [**@dstn/remcss**](https://www.npmjs.com/package/@dstn/remcss) — pure-CSS framework built on the
  golden ratio. CSS Layers, `oklch()`, container queries, `@scope`, zero JS runtime

## Stack

| | |
|:---|:---|
| **Languages** | TypeScript, JavaScript, CSS, HTML, Python, PHP |
| **Frameworks** | Nuxt 4 (Vue 3), Astro, SvelteKit (Svelte 5), Next.js |
| **Backend** | Nitro/H3, Fastify, FastAPI, Express |
| **Data** | MySQL/MariaDB via Drizzle, SQLAlchemy 2.0, SQLite, IndexedDB + OPFS |
| **Styling** | Vanilla CSS with `oklch()` design tokens, Tailwind CSS |
| **Testing** | Vitest, Playwright, @axe-core/playwright |
| **Ops** | GitHub Actions, Docker Compose, Netcup/Plesk via Passenger, DDEV |
| **CMS** | WordPress (Composer-managed, custom block themes), Directus |

## How I work

**Accessibility is a gate, not a pass.** axe-core runs in CI across every route, theme and
viewport. bewerby is audited against WCAG 2.2 AAA rather than AA — and Axie, a self-hosted
Playwright + axe-core audit service, came out of wanting that check everywhere.

**Privacy by architecture.** Where an app can work without a backend, it does: bewerby keeps
applications in IndexedDB and PDF attachments in OPFS, Twittr Archivr unzips and searches your
export in the browser. No CDN fonts anywhere — that is precisely what `fli` exists for.

**I own the deploy.** Most of these run on my own Netcup/Plesk boxes over Phusion Passenger
rather than serverless, because the ops half is part of the job.
