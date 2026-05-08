# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **3179** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 1263 | [Browse →](./aiml/) |
| 📦 **Misc** | 502 | [Browse →](./misc/) |
| 🧩 **Orchestration** | 315 | [Browse →](./orchestration/) |
| 🎨 **Frontend** | 312 | [Browse →](./frontend/) |
| ⚙️ **Backend** | 169 | [Browse →](./backend/) |
| 🔧 **DevTools** | 165 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 129 | [Browse →](./crypto/) |
| 📊 **Data** | 75 | [Browse →](./data/) |
| 💳 **Payments** | 72 | [Browse →](./payments/) |
| 📈 **Trading** | 49 | [Browse →](./trading/) |
| 🚀 **DevOps & Infra** | 44 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 38 | [Browse →](./mobile/) |
| 🔐 **Security** | 26 | [Browse →](./security/) |
| 🎯 **Product** | 9 | [Browse →](./product/) |
| ✨ **Design** | 9 | [Browse →](./design/) |
| 🏷️ **Marketing** | 2 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [trycua/cua](./aiml/trycua-cua.md) | ⭐ 15.8k | AI/ML |
| 2 | [Raphire/Win11Debloat](./devtools/raphire-win11debloat.md) | ⭐ 46k | DevTools |
| 3 | [vuetifyjs/vuetify](./frontend/vuetifyjs-vuetify.md) | ⭐ 41k | Frontend |
| 4 | [luanti-org/luanti](./devtools/luanti-org-luanti.md) | ⭐ 12.8k | DevTools |
| 5 | [microsoft/vcpkg](./misc/microsoft-vcpkg.md) | ⭐ 27k | Misc |
| 6 | [kovidgoyal/kitty](./misc/kovidgoyal-kitty.md) | ⭐ 32.8k | Misc |
| 7 | [temporalio/temporal](./orchestration/temporalio-temporal.md) | ⭐ 20.1k | Orchestration |
| 8 | [weaviate/weaviate](./aiml/weaviate-weaviate.md) | ⭐ 16.2k | AI/ML |
| 9 | [armbian/build](./aiml/armbian-build.md) | ⭐ 5.2k | AI/ML |
| 10 | [alirezarezvani/claude-skills](./orchestration/alirezarezvani-claude-skills.md) | ⭐ 14.1k | Orchestration |

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
