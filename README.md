# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **13434** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 5096 | [Browse →](./aiml/) |
| 📦 **Misc** | 2657 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1303 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 1022 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 825 | [Browse →](./backend/) |
| 🔧 **DevTools** | 798 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 479 | [Browse →](./crypto/) |
| 📊 **Data** | 306 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 294 | [Browse →](./devopsinfra/) |
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
| 2 | [xournalpp/xournalpp](./misc/xournalpp-xournalpp.md) | ⭐ 14.7k | Misc |
| 3 | [argoproj/argo-cd](./devopsinfra/argoproj-argo-cd.md) | ⭐ 22.8k | DevOps & Infra |
| 4 | [firecracker-microvm/firecracker](./payments/firecracker-microvm-firecracker.md) | ⭐ 33.9k | Payments |
| 5 | [qutebrowser/qutebrowser](./misc/qutebrowser-qutebrowser.md) | ⭐ 11.5k | Misc |
| 6 | [doocs/leetcode](./misc/doocs-leetcode.md) | ⭐ 36k | Misc |
| 7 | [Anuken/Mindustry](./mobile/anuken-mindustry.md) | ⭐ 27.4k | Mobile |
| 8 | [locustio/locust](./aiml/locustio-locust.md) | ⭐ 27.7k | AI/ML |
| 9 | [OpenBB-finance/OpenBB](./crypto/openbb-finance-openbb.md) | ⭐ 66.8k | Crypto |
| 10 | [mumble-voip/mumble](./backend/mumble-voip-mumble.md) | ⭐ 8k | Backend |

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
