# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **3979** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 1606 | [Browse →](./aiml/) |
| 📦 **Misc** | 633 | [Browse →](./misc/) |
| 🧩 **Orchestration** | 398 | [Browse →](./orchestration/) |
| 🎨 **Frontend** | 390 | [Browse →](./frontend/) |
| 🔧 **DevTools** | 210 | [Browse →](./devtools/) |
| ⚙️ **Backend** | 205 | [Browse →](./backend/) |
| ⛓️ **Crypto** | 158 | [Browse →](./crypto/) |
| 📊 **Data** | 87 | [Browse →](./data/) |
| 💳 **Payments** | 84 | [Browse →](./payments/) |
| 📈 **Trading** | 55 | [Browse →](./trading/) |
| 🚀 **DevOps & Infra** | 51 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 42 | [Browse →](./mobile/) |
| 🔐 **Security** | 34 | [Browse →](./security/) |
| ✨ **Design** | 12 | [Browse →](./design/) |
| 🎯 **Product** | 10 | [Browse →](./product/) |
| 🏷️ **Marketing** | 4 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [alibaba/arthas](./orchestration/alibaba-arthas.md) | ⭐ 37.3k | Orchestration |
| 2 | [open-multi-agent/open-multi-agent](./orchestration/open-multi-agent-open-multi-agent.md) | ⭐ 6.1k | Orchestration |
| 3 | [authelia/authelia](./devopsinfra/authelia-authelia.md) | ⭐ 27.7k | DevOps & Infra |
| 4 | [Narcooo/inkos](./aiml/narcooo-inkos.md) | ⭐ 5.9k | AI/ML |
| 5 | [yzhao062/pyod](./orchestration/yzhao062-pyod.md) | ⭐ 9.8k | Orchestration |
| 6 | [starship/starship](./misc/starship-starship.md) | ⭐ 57.3k | Misc |
| 7 | [eosphoros-ai/DB-GPT](./aiml/eosphoros-ai-db-gpt.md) | ⭐ 18.7k | AI/ML |
| 8 | [hwdsl2/docker-ipsec-vpn-server](./backend/hwdsl2-docker-ipsec-vpn-server.md) | ⭐ 7.1k | Backend |
| 9 | [StarRocks/starrocks](./devtools/starrocks-starrocks.md) | ⭐ 11.7k | DevTools |
| 10 | [stride3d/stride](./misc/stride3d-stride.md) | ⭐ 7.6k | Misc |

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
