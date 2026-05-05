# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **16536** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 6144 | [Browse →](./aiml/) |
| 📦 **Misc** | 3470 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1632 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 1194 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 1016 | [Browse →](./backend/) |
| 🔧 **DevTools** | 964 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 556 | [Browse →](./crypto/) |
| 📊 **Data** | 377 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 358 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 226 | [Browse →](./mobile/) |
| 📈 **Trading** | 170 | [Browse →](./trading/) |
| 💳 **Payments** | 169 | [Browse →](./payments/) |
| 🔐 **Security** | 139 | [Browse →](./security/) |
| ✨ **Design** | 57 | [Browse →](./design/) |
| 🎯 **Product** | 33 | [Browse →](./product/) |
| 🏷️ **Marketing** | 31 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [Wox-launcher/Wox](./misc/wox-launcher-wox.md) | ⭐ 26.8k | Misc |
| 2 | [Sjj1024/PakePlus](./aiml/sjj1024-pakeplus.md) | ⭐ 11.9k | AI/ML |
| 3 | [apache/casbin](./aiml/apache-casbin.md) | ⭐ 20.1k | AI/ML |
| 4 | [OthmanAdi/planning-with-files](./orchestration/othmanadi-planning-with-files.md) | ⭐ 20.4k | Orchestration |
| 5 | [cython/cython](./data/cython-cython.md) | ⭐ 10.7k | Data |
| 6 | [hoppscotch/hoppscotch](./frontend/hoppscotch-hoppscotch.md) | ⭐ 79.1k | Frontend |
| 7 | [firecracker-microvm/firecracker](./payments/firecracker-microvm-firecracker.md) | ⭐ 33.9k | Payments |
| 8 | [sorin-ionescu/prezto](./devtools/sorin-ionescu-prezto.md) | ⭐ 14.5k | DevTools |
| 9 | [flame-engine/flame](./mobile/flame-engine-flame.md) | ⭐ 10.6k | Mobile |
| 10 | [OpenRefine/OpenRefine](./data/openrefine-openrefine.md) | ⭐ 11.8k | Data |

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
