# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **15771** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 5879 | [Browse →](./aiml/) |
| 📦 **Misc** | 3277 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1554 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 1152 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 965 | [Browse →](./backend/) |
| 🔧 **DevTools** | 930 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 535 | [Browse →](./crypto/) |
| 📊 **Data** | 357 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 337 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 217 | [Browse →](./mobile/) |
| 💳 **Payments** | 164 | [Browse →](./payments/) |
| 📈 **Trading** | 161 | [Browse →](./trading/) |
| 🔐 **Security** | 129 | [Browse →](./security/) |
| ✨ **Design** | 52 | [Browse →](./design/) |
| 🎯 **Product** | 31 | [Browse →](./product/) |
| 🏷️ **Marketing** | 31 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [opendatalab/MinerU](./orchestration/opendatalab-mineru.md) | ⭐ 61.9k | Orchestration |
| 2 | [akfamily/akshare](./trading/akfamily-akshare.md) | ⭐ 18.8k | Trading |
| 3 | [krzyzanowskim/CryptoSwift](./crypto/krzyzanowskim-cryptoswift.md) | ⭐ 10.5k | Crypto |
| 4 | [rook/rook](./orchestration/rook-rook.md) | ⭐ 13.5k | Orchestration |
| 5 | [firecracker-microvm/firecracker](./payments/firecracker-microvm-firecracker.md) | ⭐ 33.9k | Payments |
| 6 | [linshenkx/prompt-optimizer](./aiml/linshenkx-prompt-optimizer.md) | ⭐ 27.9k | AI/ML |
| 7 | [ruvnet/ruflo](./orchestration/ruvnet-ruflo.md) | ⭐ 38.4k | Orchestration |
| 8 | [h2oai/h2o-3](./aiml/h2oai-h2o-3.md) | ⭐ 7.5k | AI/ML |
| 9 | [Graylog2/graylog2-server](./backend/graylog2-graylog2-server.md) | ⭐ 8k | Backend |
| 10 | [run-llama/llama_index](./orchestration/run-llama-llama-index.md) | ⭐ 49.1k | Orchestration |

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
