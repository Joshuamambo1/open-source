# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **16355** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 6073 | [Browse →](./aiml/) |
| 📦 **Misc** | 3429 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1615 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 1184 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 1004 | [Browse →](./backend/) |
| 🔧 **DevTools** | 956 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 550 | [Browse →](./crypto/) |
| 📊 **Data** | 376 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 353 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 226 | [Browse →](./mobile/) |
| 📈 **Trading** | 168 | [Browse →](./trading/) |
| 💳 **Payments** | 168 | [Browse →](./payments/) |
| 🔐 **Security** | 135 | [Browse →](./security/) |
| ✨ **Design** | 55 | [Browse →](./design/) |
| 🎯 **Product** | 32 | [Browse →](./product/) |
| 🏷️ **Marketing** | 31 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [google-ai-edge/mediapipe](./aiml/google-ai-edge-mediapipe.md) | ⭐ 35.1k | AI/ML |
| 2 | [pola-rs/polars](./data/pola-rs-polars.md) | ⭐ 38.4k | Data |
| 3 | [arkime/arkime](./data/arkime-arkime.md) | ⭐ 7.4k | Data |
| 4 | [kivy/kivy](./frontend/kivy-kivy.md) | ⭐ 18.9k | Frontend |
| 5 | [farion1231/cc-switch](./aiml/farion1231-cc-switch.md) | ⭐ 59k | AI/ML |
| 6 | [cython/cython](./data/cython-cython.md) | ⭐ 10.7k | Data |
| 7 | [firecracker-microvm/firecracker](./payments/firecracker-microvm-firecracker.md) | ⭐ 33.9k | Payments |
| 8 | [knative/docs](./aiml/knative-docs.md) | ⭐ 5k | AI/ML |
| 9 | [PrefectHQ/fastmcp](./aiml/prefecthq-fastmcp.md) | ⭐ 25k | AI/ML |
| 10 | [ghostfolio/ghostfolio](./trading/ghostfolio-ghostfolio.md) | ⭐ 8.3k | Trading |

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
