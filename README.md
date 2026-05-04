# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **15853** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 5905 | [Browse →](./aiml/) |
| 📦 **Misc** | 3299 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1563 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 1157 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 968 | [Browse →](./backend/) |
| 🔧 **DevTools** | 937 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 536 | [Browse →](./crypto/) |
| 📊 **Data** | 361 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 338 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 218 | [Browse →](./mobile/) |
| 💳 **Payments** | 164 | [Browse →](./payments/) |
| 📈 **Trading** | 163 | [Browse →](./trading/) |
| 🔐 **Security** | 130 | [Browse →](./security/) |
| ✨ **Design** | 52 | [Browse →](./design/) |
| 🎯 **Product** | 31 | [Browse →](./product/) |
| 🏷️ **Marketing** | 31 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [plankanban/planka](./frontend/plankanban-planka.md) | ⭐ 11.9k | Frontend |
| 2 | [alibaba/spring-cloud-alibaba](./frontend/alibaba-spring-cloud-alibaba.md) | ⭐ 29.1k | Frontend |
| 3 | [opendatalab/MinerU](./orchestration/opendatalab-mineru.md) | ⭐ 61.9k | Orchestration |
| 4 | [NousResearch/hermes-agent](./aiml/nousresearch-hermes-agent.md) | ⭐ 131.3k | AI/ML |
| 5 | [vuetifyjs/vuetify](./frontend/vuetifyjs-vuetify.md) | ⭐ 41k | Frontend |
| 6 | [PaddlePaddle/Paddle](./aiml/paddlepaddle-paddle.md) | ⭐ 23.9k | AI/ML |
| 7 | [ChenYilong/CYLTabBarController](./frontend/chenyilong-cyltabbarcontroller.md) | ⭐ 7k | Frontend |
| 8 | [FlowiseAI/Flowise](./orchestration/flowiseai-flowise.md) | ⭐ 52.5k | Orchestration |
| 9 | [zeek/zeek](./security/zeek-zeek.md) | ⭐ 7.6k | Security |
| 10 | [liyupi/codefather](./aiml/liyupi-codefather.md) | ⭐ 7.2k | AI/ML |

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
