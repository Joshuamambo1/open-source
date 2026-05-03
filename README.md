# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **15426** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 5760 | [Browse →](./aiml/) |
| 📦 **Misc** | 3183 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1507 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 1140 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 943 | [Browse →](./backend/) |
| 🔧 **DevTools** | 920 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 527 | [Browse →](./crypto/) |
| 📊 **Data** | 349 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 331 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 209 | [Browse →](./mobile/) |
| 💳 **Payments** | 163 | [Browse →](./payments/) |
| 📈 **Trading** | 157 | [Browse →](./trading/) |
| 🔐 **Security** | 126 | [Browse →](./security/) |
| ✨ **Design** | 51 | [Browse →](./design/) |
| 🏷️ **Marketing** | 31 | [Browse →](./marketing/) |
| 🎯 **Product** | 29 | [Browse →](./product/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [Dooy/chatgpt-web-midjourney-proxy](./aiml/dooy-chatgpt-web-midjourney-proxy.md) | ⭐ 6.7k | AI/ML |
| 2 | [teng-lin/notebooklm-py](./aiml/teng-lin-notebooklm-py.md) | ⭐ 12.4k | AI/ML |
| 3 | [beekeeper-studio/beekeeper-studio](./backend/beekeeper-studio-beekeeper-studio.md) | ⭐ 22.7k | Backend |
| 4 | [v2rayA/v2rayA](./frontend/v2raya-v2raya.md) | ⭐ 15k | Frontend |
| 5 | [quic-go/quic-go](./frontend/quic-go-quic-go.md) | ⭐ 11.6k | Frontend |
| 6 | [getmaxun/maxun](./aiml/getmaxun-maxun.md) | ⭐ 15.5k | AI/ML |
| 7 | [emacs-lsp/lsp-mode](./aiml/emacs-lsp-lsp-mode.md) | ⭐ 5.1k | AI/ML |
| 8 | [nicolargo/glances](./backend/nicolargo-glances.md) | ⭐ 32.4k | Backend |
| 9 | [stashapp/stash](./misc/stashapp-stash.md) | ⭐ 12.3k | Misc |
| 10 | [travisvn/awesome-claude-skills](./aiml/travisvn-awesome-claude-skills.md) | ⭐ 12.1k | AI/ML |

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
