# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **5866** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 2338 | [Browse →](./aiml/) |
| 📦 **Misc** | 1079 | [Browse →](./misc/) |
| 🎨 **Frontend** | 584 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 529 | [Browse →](./orchestration/) |
| 🔧 **DevTools** | 310 | [Browse →](./devtools/) |
| ⚙️ **Backend** | 284 | [Browse →](./backend/) |
| ⛓️ **Crypto** | 207 | [Browse →](./crypto/) |
| 📊 **Data** | 139 | [Browse →](./data/) |
| 💳 **Payments** | 94 | [Browse →](./payments/) |
| 📱 **Mobile** | 76 | [Browse →](./mobile/) |
| 📈 **Trading** | 76 | [Browse →](./trading/) |
| 🚀 **DevOps & Infra** | 65 | [Browse →](./devopsinfra/) |
| 🔐 **Security** | 44 | [Browse →](./security/) |
| ✨ **Design** | 19 | [Browse →](./design/) |
| 🎯 **Product** | 14 | [Browse →](./product/) |
| 🏷️ **Marketing** | 8 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [pear-devs/pear-desktop](./misc/pear-devs-pear-desktop.md) | ⭐ 31.6k | Misc |
| 2 | [flame-engine/flame](./mobile/flame-engine-flame.md) | ⭐ 10.6k | Mobile |
| 3 | [openebs/openebs](./aiml/openebs-openebs.md) | ⭐ 9.7k | AI/ML |
| 4 | [moeru-ai/airi](./aiml/moeru-ai-airi.md) | ⭐ 39.1k | AI/ML |
| 5 | [VoltAgent/awesome-agent-skills](./orchestration/voltagent-awesome-agent-skills.md) | ⭐ 21.1k | Orchestration |
| 6 | [dockur/windows](./aiml/dockur-windows.md) | ⭐ 51.3k | AI/ML |
| 7 | [gofiber/fiber](./backend/gofiber-fiber.md) | ⭐ 39.7k | Backend |
| 8 | [x64dbg/x64dbg](./security/x64dbg-x64dbg.md) | ⭐ 48.3k | Security |
| 9 | [laurent22/joplin](./frontend/laurent22-joplin.md) | ⭐ 54.7k | Frontend |
| 10 | [MudBlazor/MudBlazor](./frontend/mudblazor-mudblazor.md) | ⭐ 10.4k | Frontend |

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
