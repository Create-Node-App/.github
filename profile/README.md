# Create Awesome Node App

<picture>
  <source media="(prefers-color-scheme: dark)" alt="" align="left" width="200px" srcset="https://github.com/Create-Node-App/.github/blob/main/profile/octocat-1696139484130.png?raw=true"/>
  <img alt="" align="left" width="200px" src="https://github.com/Create-Node-App/.github/blob/main/profile/octocat-1696139484130.png?raw=true"/>
</picture>

**One command. Any stack.**

[![Awesome](https://awesome.re/mentioned-badge.svg)](https://github.com/vitejs/awesome-vite#get-started)
[![npm][npmversion]][npmurl]
[![npm][npmdownloads]][npmurl]
[![Website](https://img.shields.io/badge/website-create--awesome--node--app.vercel.app-0d9488?style=flat-square&logo=vercel&logoColor=white)](https://create-awesome-node-app.vercel.app/)
[![Discord](https://img.shields.io/discord/1527933660764831825?style=flat-square&label=Discord&logo=discord&logoColor=white)](https://discord.gg/dwFTsR7fK2)

Choose a template, add addons, and ship production-ready Node, Web, Full-Stack, and AI-ready apps from a cozy developer workbench.

<br clear="left" />
<br clear="left" />

```bash
npm create awesome-node-app@latest my-app
```

Interactive by default. For CI and automation:

```bash
npx create-awesome-node-app my-app \
  --template react-vite-boilerplate \
  --addons tailwind-css zustand github-setup \
  --no-interactive
```

## Flagship — Next.js SaaS AI Starter

Multi-tenant SaaS with AI built in. Use it when you need Auth, Drizzle, pgvector, PBAC, and an admin panel on day one — not as the look of every CNA starter.

**[View repository](https://github.com/Create-Node-App/nextjs-saas-ai-template)** · **[Get started](https://create-awesome-node-app.vercel.app/templates/nextjs-saas-ai-starter)**

| Category | Technology |
|---|---|
| Framework | Next.js 15 (App Router, RSC, Turbopack) |
| Styling | Tailwind CSS v4 + shadcn/ui |
| Database | PostgreSQL 17 + pgvector + Drizzle ORM |
| Auth | Auth.js v5 + Auth0 (SSO) |
| AI | OpenAI / Anthropic via Vercel AI SDK + RAG |
| Access Control | PBAC (Permission-Based, multi-role) |
| Dev Env | DevContainer + direnv (zero-config) |
| i18n | next-intl (EN + ES) |
| Testing | Jest + React Testing Library + Storybook |
| CI/CD | GitHub Actions |

```bash
npx create-awesome-node-app my-saas --template nextjs-saas-ai-starter
```

## Repositories

| Repository | Description |
|---|---|
| [create-node-app](https://github.com/Create-Node-App/create-node-app) | CLI source for `create-awesome-node-app` |
| [cna-templates](https://github.com/Create-Node-App/cna-templates) | Official templates and extensions registry |
| [nextjs-saas-ai-template](https://github.com/Create-Node-App/nextjs-saas-ai-template) | Flagship: multi-tenant SaaS + AI |
| [website](https://github.com/Create-Node-App/website) | Catalog and docs at [create-awesome-node-app.vercel.app](https://create-awesome-node-app.vercel.app/) |
| [create-awesome-node-app](https://www.npmjs.com/package/create-awesome-node-app) | npm package for the scaffolding CLI |

## Templates

| Category | Templates |
|---|---|
| Full Stack | Next.js Starter, **Next.js SaaS AI Starter** |
| Frontend | React + Vite, Remix, Astro |
| Backend | NestJS, Hono |
| Monorepo | Turborepo |
| Browser Extension | Web Extension (React + Vite) |
| Testing | WebdriverIO |

→ [Browse all templates](https://create-awesome-node-app.vercel.app/templates) · [Browse extensions](https://create-awesome-node-app.vercel.app/extensions)

## Extensions

Extend any template with official addons: Tailwind CSS, shadcn/ui, Zustand, TanStack Query, Auth.js, Drizzle, Docker Compose, GitHub Actions CI, DevContainer, and more.

## Contributing

We welcome contributions — templates, extensions, bug fixes, and docs.

- [Contributing guide](https://github.com/Create-Node-App/create-node-app/blob/main/CONTRIBUTING.md)
- Brand identity: cozy nest (amber + teal) — see [docs/BRAND.md](https://github.com/Create-Node-App/create-node-app/blob/main/docs/BRAND.md)

## Find us

- **npm:** [create-awesome-node-app](https://www.npmjs.com/package/create-awesome-node-app)
- **Website:** [create-awesome-node-app.vercel.app](https://create-awesome-node-app.vercel.app/)
- **Awesome Vite:** [Listed](https://github.com/vitejs/awesome-vite#get-started)


## Part of the Create Awesome App ecosystem

| Org | Stack | Status |
|-----|-------|--------|
| [Create-Node-App](https://github.com/Create-Node-App) | Node.js, TypeScript | ✅ Production |
| [Create-Python-App](https://github.com/Create-Python-App) | Python | 🧪 Beta |
| [Create-Vlang-App](https://create-awesome-vlang-app.vercel.app) | V language | ✅ Live |

Website: [create-awesome-python-app.vercel.app](https://create-awesome-python-app.vercel.app/)

## Sponsored by

<a href="https://github.com/nanlabs" target="_blank">
  <img alt="Sponsored by NaNLABS" width="100px" src="https://github.com/Create-Node-App/.github/assets/17727170/c84ffa2e-effb-41e3-9938-be8fae1fd9d2" />
</a>

[npmversion]: https://img.shields.io/npm/v/create-awesome-node-app.svg?maxAge=2592000?style=plastic
[npmdownloads]: https://img.shields.io/npm/dm/create-awesome-node-app.svg?maxAge=2592000?style=plastic
[npmurl]: https://www.npmjs.com/package/create-awesome-node-app
