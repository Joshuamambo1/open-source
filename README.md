# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **13244** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 5031 | [Browse →](./aiml/) |
| 📦 **Misc** | 2617 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1288 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 1010 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 808 | [Browse →](./backend/) |
| 🔧 **DevTools** | 785 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 474 | [Browse →](./crypto/) |
| 📊 **Data** | 300 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 289 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 162 | [Browse →](./mobile/) |
| 💳 **Payments** | 139 | [Browse →](./payments/) |
| 📈 **Trading** | 137 | [Browse →](./trading/) |
| 🔐 **Security** | 111 | [Browse →](./security/) |
| ✨ **Design** | 41 | [Browse →](./design/) |
| 🎯 **Product** | 27 | [Browse →](./product/) |
| 🏷️ **Marketing** | 25 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [pion/webrtc](./backend/pion-webrtc.md) | ⭐ 16.3k | Backend |
| 2 | [GyulyVGC/sniffnet](./frontend/gyulyvgc-sniffnet.md) | ⭐ 37k | Frontend |
| 3 | [openshift/origin](./aiml/openshift-origin.md) | ⭐ 8.6k | AI/ML |
| 4 | [argoproj/argo-cd](./devopsinfra/argoproj-argo-cd.md) | ⭐ 22.8k | DevOps & Infra |
| 5 | [saltstack/salt](./devopsinfra/saltstack-salt.md) | ⭐ 15.4k | DevOps & Infra |
| 6 | [bluewave-labs/Checkmate](./frontend/bluewave-labs-checkmate.md) | ⭐ 9.7k | Frontend |
| 7 | [Kilo-Org/kilocode](./aiml/kilo-org-kilocode.md) | ⭐ 18.8k | AI/ML |
| 8 | [alibaba/spring-ai-alibaba](./orchestration/alibaba-spring-ai-alibaba.md) | ⭐ 9.4k | Orchestration |
| 9 | [airbytehq/airbyte](./aiml/airbytehq-airbyte.md) | ⭐ 21.2k | AI/ML |
| 10 | [agentscope-ai/agentscope](./orchestration/agentscope-ai-agentscope.md) | ⭐ 24.5k | Orchestration |

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
