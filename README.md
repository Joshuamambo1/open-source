# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **15470** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 5773 | [Browse →](./aiml/) |
| 📦 **Misc** | 3192 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1513 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 1141 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 947 | [Browse →](./backend/) |
| 🔧 **DevTools** | 922 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 528 | [Browse →](./crypto/) |
| 📊 **Data** | 351 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 331 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 209 | [Browse →](./mobile/) |
| 💳 **Payments** | 165 | [Browse →](./payments/) |
| 📈 **Trading** | 159 | [Browse →](./trading/) |
| 🔐 **Security** | 127 | [Browse →](./security/) |
| ✨ **Design** | 51 | [Browse →](./design/) |
| 🏷️ **Marketing** | 31 | [Browse →](./marketing/) |
| 🎯 **Product** | 30 | [Browse →](./product/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [Laravel-Lang/lang](./payments/laravel-lang-lang.md) | ⭐ 7.8k | Payments |
| 2 | [Dooy/chatgpt-web-midjourney-proxy](./aiml/dooy-chatgpt-web-midjourney-proxy.md) | ⭐ 6.7k | AI/ML |
| 3 | [teng-lin/notebooklm-py](./aiml/teng-lin-notebooklm-py.md) | ⭐ 12.4k | AI/ML |
| 4 | [ShareX/ShareX](./product/sharex-sharex.md) | ⭐ 37k | Product |
| 5 | [beekeeper-studio/beekeeper-studio](./backend/beekeeper-studio-beekeeper-studio.md) | ⭐ 22.7k | Backend |
| 6 | [quic-go/quic-go](./frontend/quic-go-quic-go.md) | ⭐ 11.6k | Frontend |
| 7 | [getmaxun/maxun](./aiml/getmaxun-maxun.md) | ⭐ 15.5k | AI/ML |
| 8 | [nicolargo/glances](./backend/nicolargo-glances.md) | ⭐ 32.4k | Backend |
| 9 | [stashapp/stash](./misc/stashapp-stash.md) | ⭐ 12.3k | Misc |
| 10 | [v2rayA/v2rayA](./frontend/v2raya-v2raya.md) | ⭐ 15k | Frontend |

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
