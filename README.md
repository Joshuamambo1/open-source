# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **3299** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 1309 | [Browse →](./aiml/) |
| 📦 **Misc** | 517 | [Browse →](./misc/) |
| 🎨 **Frontend** | 331 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 329 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 175 | [Browse →](./backend/) |
| 🔧 **DevTools** | 171 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 133 | [Browse →](./crypto/) |
| 📊 **Data** | 78 | [Browse →](./data/) |
| 💳 **Payments** | 75 | [Browse →](./payments/) |
| 📈 **Trading** | 49 | [Browse →](./trading/) |
| 🚀 **DevOps & Infra** | 45 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 39 | [Browse →](./mobile/) |
| 🔐 **Security** | 28 | [Browse →](./security/) |
| 🎯 **Product** | 9 | [Browse →](./product/) |
| ✨ **Design** | 9 | [Browse →](./design/) |
| 🏷️ **Marketing** | 2 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [nukeop/nuclear](./aiml/nukeop-nuclear.md) | ⭐ 17.5k | AI/ML |
| 2 | [kedro-org/kedro](./aiml/kedro-org-kedro.md) | ⭐ 10.9k | AI/ML |
| 3 | [payloadcms/payload](./frontend/payloadcms-payload.md) | ⭐ 42.3k | Frontend |
| 4 | [Lissy93/dashy](./frontend/lissy93-dashy.md) | ⭐ 25k | Frontend |
| 5 | [gfx-rs/wgpu](./backend/gfx-rs-wgpu.md) | ⭐ 17.1k | Backend |
| 6 | [jhipster/generator-jhipster](./frontend/jhipster-generator-jhipster.md) | ⭐ 22.4k | Frontend |
| 7 | [reactos/reactos](./frontend/reactos-reactos.md) | ⭐ 17.5k | Frontend |
| 8 | [teng-lin/notebooklm-py](./aiml/teng-lin-notebooklm-py.md) | ⭐ 12.9k | AI/ML |
| 9 | [Automattic/wp-calypso](./frontend/automattic-wp-calypso.md) | ⭐ 12.6k | Frontend |
| 10 | [pnpm/pnpm](./misc/pnpm-pnpm.md) | ⭐ 34.9k | Misc |

## 🚀 How it works

```mermaid
graph LR
  A[GitHub · HN · Reddit · PH] --> B[RepoScout]
  B --> C[Score · Dedupe · Categorize]
  C --> D[LLM Summarize]
  D --> E[PostgreSQL DB]
  D --> F[This Catalog]
```

1. **Discover** — 4 sources pulled in parallel
2. **Score** — weighted: stars, forks, recency, topics, source trust
3. **Categorize** — rule-based + LLM-assisted tagging
4. **Summarize** — concise bilingual (EN/RU) summaries via LLM
5. **Sync** — markdown committed here, metadata upserted to PostgreSQL

## 🛠️ Self-host

```bash
git clone https://github.com/kirbudilov01/reposearchengine
cp .env.example .env
# Set LLM_PROVIDER, CATALOG_REPO_PATH, DATABASE_URL, ...
npm install && npm start
```

Supports local LLMs (Ollama) and cloud providers (OpenAI · Anthropic · OpenRouter).

## 📦 Data format

- [`index.json`](./index.json) — full catalog sorted by score
- `<category>/README.md` — category index with ranked table
- `<category>/<owner>-<name>.md` — per-repo card with stats, topics, summary

## 📜 License

MIT (metadata). Each linked repository retains its own license.

---

<sub>🤖 Maintained automatically by RepoScout · Built with Claude Code</sub>
