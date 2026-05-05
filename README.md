# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **16515** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 6136 | [Browse →](./aiml/) |
| 📦 **Misc** | 3470 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1631 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 1191 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 1013 | [Browse →](./backend/) |
| 🔧 **DevTools** | 964 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 556 | [Browse →](./crypto/) |
| 📊 **Data** | 376 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 355 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 226 | [Browse →](./mobile/) |
| 💳 **Payments** | 169 | [Browse →](./payments/) |
| 📈 **Trading** | 169 | [Browse →](./trading/) |
| 🔐 **Security** | 139 | [Browse →](./security/) |
| ✨ **Design** | 56 | [Browse →](./design/) |
| 🎯 **Product** | 33 | [Browse →](./product/) |
| 🏷️ **Marketing** | 31 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [redox-os/redox](./misc/redox-os-redox.md) | ⭐ 16.3k | Misc |
| 2 | [endless-sky/endless-sky](./trading/endless-sky-endless-sky.md) | ⭐ 7.3k | Trading |
| 3 | [biomejs/biome](./aiml/biomejs-biome.md) | ⭐ 24.5k | AI/ML |
| 4 | [MarSeventh/CloudFlare-ImgBed](./aiml/marseventh-cloudflare-imgbed.md) | ⭐ 5k | AI/ML |
| 5 | [recharts/recharts](./crypto/recharts-recharts.md) | ⭐ 27.1k | Crypto |
| 6 | [charmbracelet/bubbletea](./frontend/charmbracelet-bubbletea.md) | ⭐ 42.1k | Frontend |
| 7 | [Lissy93/dashy](./frontend/lissy93-dashy.md) | ⭐ 25k | Frontend |
| 8 | [Wox-launcher/Wox](./misc/wox-launcher-wox.md) | ⭐ 26.8k | Misc |
| 9 | [Sjj1024/PakePlus](./aiml/sjj1024-pakeplus.md) | ⭐ 11.9k | AI/ML |
| 10 | [rabbitmq/rabbitmq-server](./frontend/rabbitmq-rabbitmq-server.md) | ⭐ 13.6k | Frontend |

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
