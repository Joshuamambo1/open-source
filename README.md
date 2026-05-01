# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **13390** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 5079 | [Browse →](./aiml/) |
| 📦 **Misc** | 2647 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1297 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 1020 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 823 | [Browse →](./backend/) |
| 🔧 **DevTools** | 794 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 479 | [Browse →](./crypto/) |
| 📊 **Data** | 305 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 292 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 165 | [Browse →](./mobile/) |
| 💳 **Payments** | 143 | [Browse →](./payments/) |
| 📈 **Trading** | 139 | [Browse →](./trading/) |
| 🔐 **Security** | 112 | [Browse →](./security/) |
| ✨ **Design** | 42 | [Browse →](./design/) |
| 🎯 **Product** | 27 | [Browse →](./product/) |
| 🏷️ **Marketing** | 26 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [pion/webrtc](./backend/pion-webrtc.md) | ⭐ 16.3k | Backend |
| 2 | [gogf/gf](./backend/gogf-gf.md) | ⭐ 13.1k | Backend |
| 3 | [xournalpp/xournalpp](./misc/xournalpp-xournalpp.md) | ⭐ 14.7k | Misc |
| 4 | [mikel-brostrom/boxmot](./misc/mikel-brostrom-boxmot.md) | ⭐ 8.1k | Misc |
| 5 | [kamyu104/LeetCode-Solutions](./data/kamyu104-leetcode-solutions.md) | ⭐ 5.2k | Data |
| 6 | [sub-store-org/Sub-Store](./payments/sub-store-org-sub-store.md) | ⭐ 9.4k | Payments |
| 7 | [googleworkspace/cli](./orchestration/googleworkspace-cli.md) | ⭐ 25.6k | Orchestration |
| 8 | [argoproj/argo-cd](./devopsinfra/argoproj-argo-cd.md) | ⭐ 22.8k | DevOps & Infra |
| 9 | [labring/FastGPT](./orchestration/labring-fastgpt.md) | ⭐ 27.9k | Orchestration |
| 10 | [Automattic/wp-calypso](./frontend/automattic-wp-calypso.md) | ⭐ 12.6k | Frontend |

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
