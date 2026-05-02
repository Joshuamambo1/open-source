# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **14794** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 5543 | [Browse →](./aiml/) |
| 📦 **Misc** | 3014 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1445 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 1098 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 909 | [Browse →](./backend/) |
| 🔧 **DevTools** | 887 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 514 | [Browse →](./crypto/) |
| 📊 **Data** | 337 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 320 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 196 | [Browse →](./mobile/) |
| 💳 **Payments** | 157 | [Browse →](./payments/) |
| 📈 **Trading** | 149 | [Browse →](./trading/) |
| 🔐 **Security** | 120 | [Browse →](./security/) |
| ✨ **Design** | 48 | [Browse →](./design/) |
| 🎯 **Product** | 29 | [Browse →](./product/) |
| 🏷️ **Marketing** | 28 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [timescale/timescaledb](./data/timescale-timescaledb.md) | ⭐ 22.5k | Data |
| 2 | [MaterialDesignInXAML/MaterialDesignInXamlToolkit](./aiml/materialdesigninxaml-materialdesigninxamltoolkit.md) | ⭐ 16.1k | AI/ML |
| 3 | [luanti-org/luanti](./devtools/luanti-org-luanti.md) | ⭐ 12.8k | DevTools |
| 4 | [rabbitmq/rabbitmq-server](./frontend/rabbitmq-rabbitmq-server.md) | ⭐ 13.6k | Frontend |
| 5 | [The-PR-Agent/pr-agent](./aiml/the-pr-agent-pr-agent.md) | ⭐ 11.1k | AI/ML |
| 6 | [ruvnet/RuView](./aiml/ruvnet-ruview.md) | ⭐ 51.4k | AI/ML |
| 7 | [ComposioHQ/composio](./aiml/composiohq-composio.md) | ⭐ 28k | AI/ML |
| 8 | [firecracker-microvm/firecracker](./payments/firecracker-microvm-firecracker.md) | ⭐ 33.9k | Payments |
| 9 | [redisson/redisson](./frontend/redisson-redisson.md) | ⭐ 24.3k | Frontend |
| 10 | [simple-icons/simple-icons](./design/simple-icons-simple-icons.md) | ⭐ 25k | Design |

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
