# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **2539** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 988 | [Browse →](./aiml/) |
| 📦 **Misc** | 413 | [Browse →](./misc/) |
| 🎨 **Frontend** | 255 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 247 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 132 | [Browse →](./backend/) |
| 🔧 **DevTools** | 132 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 102 | [Browse →](./crypto/) |
| 📊 **Data** | 65 | [Browse →](./data/) |
| 💳 **Payments** | 61 | [Browse →](./payments/) |
| 📈 **Trading** | 41 | [Browse →](./trading/) |
| 🚀 **DevOps & Infra** | 37 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 31 | [Browse →](./mobile/) |
| 🔐 **Security** | 19 | [Browse →](./security/) |
| 🎯 **Product** | 8 | [Browse →](./product/) |
| ✨ **Design** | 6 | [Browse →](./design/) |
| 🏷️ **Marketing** | 2 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [PowerShell/PowerShell](./misc/powershell-powershell.md) | ⭐ 53.3k | Misc |
| 2 | [knadh/listmonk](./payments/knadh-listmonk.md) | ⭐ 20k | Payments |
| 3 | [Dooy/chatgpt-web-midjourney-proxy](./aiml/dooy-chatgpt-web-midjourney-proxy.md) | ⭐ 6.7k | AI/ML |
| 4 | [ValueCell-ai/ClawX](./orchestration/valuecell-ai-clawx.md) | ⭐ 7.1k | Orchestration |
| 5 | [FreshRSS/FreshRSS](./misc/freshrss-freshrss.md) | ⭐ 15k | Misc |
| 6 | [photoprism/photoprism](./aiml/photoprism-photoprism.md) | ⭐ 39.6k | AI/ML |
| 7 | [humhub/humhub](./aiml/humhub-humhub.md) | ⭐ 6.7k | AI/ML |
| 8 | [SeleniumHQ/selenium](./misc/seleniumhq-selenium.md) | ⭐ 34.1k | Misc |
| 9 | [owncast/owncast](./misc/owncast-owncast.md) | ⭐ 11.2k | Misc |
| 10 | [sickn33/antigravity-awesome-skills](./orchestration/sickn33-antigravity-awesome-skills.md) | ⭐ 36.8k | Orchestration |

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
