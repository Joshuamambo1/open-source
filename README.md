# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **12901** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 4922 | [Browse →](./aiml/) |
| 📦 **Misc** | 2527 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1250 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 992 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 780 | [Browse →](./backend/) |
| 🔧 **DevTools** | 765 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 467 | [Browse →](./crypto/) |
| 📊 **Data** | 290 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 281 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 160 | [Browse →](./mobile/) |
| 💳 **Payments** | 135 | [Browse →](./payments/) |
| 📈 **Trading** | 133 | [Browse →](./trading/) |
| 🔐 **Security** | 110 | [Browse →](./security/) |
| ✨ **Design** | 38 | [Browse →](./design/) |
| 🎯 **Product** | 27 | [Browse →](./product/) |
| 🏷️ **Marketing** | 24 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [hasura/graphql-engine](./aiml/hasura-graphql-engine.md) | ⭐ 32k | AI/ML |
| 2 | [appium/appium](./frontend/appium-appium.md) | ⭐ 21.5k | Frontend |
| 3 | [nats-io/nats-server](./aiml/nats-io-nats-server.md) | ⭐ 19.7k | AI/ML |
| 4 | [MarlinFirmware/Marlin](./frontend/marlinfirmware-marlin.md) | ⭐ 17.4k | Frontend |
| 5 | [triggerdotdev/trigger.dev](./orchestration/triggerdotdev-trigger.dev.md) | ⭐ 14.7k | Orchestration |
| 6 | [apache/superset](./frontend/apache-superset.md) | ⭐ 72.7k | Frontend |
| 7 | [kata-containers/kata-containers](./aiml/kata-containers-kata-containers.md) | ⭐ 7.8k | AI/ML |
| 8 | [webstudio-is/webstudio](./frontend/webstudio-is-webstudio.md) | ⭐ 8.5k | Frontend |
| 9 | [toeverything/AFFiNE](./aiml/toeverything-affine.md) | ⭐ 67.9k | AI/ML |
| 10 | [openshift/origin](./aiml/openshift-origin.md) | ⭐ 8.6k | AI/ML |

## 🚀 How it works

```mermaid
graph LR
  A[GitHub · HN · Reddit · PH] --> B[RepoScout]
  B --> C[Score · Dedupe · Categorize]
  C --> D[LLM Summarize]
  D --> E[Supabase DB]
  D --> F[This Catalog]
```

1. **Discover** — 4 sources pulled in parallel
2. **Score** — weighted: stars, forks, recency, topics, source trust
3. **Categorize** — rule-based + LLM-assisted tagging
4. **Summarize** — concise bilingual (EN/RU) summaries via LLM
5. **Sync** — markdown committed here, metadata upserted to Supabase

## 🛠️ Self-host

```bash
git clone https://github.com/kirbudilov01/reposearchengine
cp .env.example .env
# Set LLM_PROVIDER, CATALOG_REPO_PATH, SUPABASE_URL, ...
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
