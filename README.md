# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **15946** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 5938 | [Browse →](./aiml/) |
| 📦 **Misc** | 3314 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1574 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 1160 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 976 | [Browse →](./backend/) |
| 🔧 **DevTools** | 946 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 539 | [Browse →](./crypto/) |
| 📊 **Data** | 362 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 340 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 220 | [Browse →](./mobile/) |
| 💳 **Payments** | 166 | [Browse →](./payments/) |
| 📈 **Trading** | 164 | [Browse →](./trading/) |
| 🔐 **Security** | 130 | [Browse →](./security/) |
| ✨ **Design** | 53 | [Browse →](./design/) |
| 🎯 **Product** | 33 | [Browse →](./product/) |
| 🏷️ **Marketing** | 31 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [HumanSignal/label-studio](./aiml/humansignal-label-studio.md) | ⭐ 27.2k | AI/ML |
| 2 | [alibaba/spring-cloud-alibaba](./frontend/alibaba-spring-cloud-alibaba.md) | ⭐ 29.1k | Frontend |
| 3 | [microsoft/presidio](./aiml/microsoft-presidio.md) | ⭐ 7.9k | AI/ML |
| 4 | [Serial-Studio/Serial-Studio](./frontend/serial-studio-serial-studio.md) | ⭐ 6.9k | Frontend |
| 5 | [fmtlib/fmt](./misc/fmtlib-fmt.md) | ⭐ 23.5k | Misc |
| 6 | [alibaba/MNN](./aiml/alibaba-mnn.md) | ⭐ 15.1k | AI/ML |
| 7 | [langchain-ai/langgraph](./orchestration/langchain-ai-langgraph.md) | ⭐ 31.1k | Orchestration |
| 8 | [affaan-m/everything-claude-code](./aiml/affaan-m-everything-claude-code.md) | ⭐ 172.9k | AI/ML |
| 9 | [envoyproxy/envoy](./misc/envoyproxy-envoy.md) | ⭐ 27.9k | Misc |
| 10 | [warpdotdev/warp](./aiml/warpdotdev-warp.md) | ⭐ 53.8k | AI/ML |

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
