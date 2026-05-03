# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **14993** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 5600 | [Browse →](./aiml/) |
| 📦 **Misc** | 3075 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1469 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 1111 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 918 | [Browse →](./backend/) |
| 🔧 **DevTools** | 896 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 518 | [Browse →](./crypto/) |
| 📊 **Data** | 342 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 322 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 204 | [Browse →](./mobile/) |
| 💳 **Payments** | 160 | [Browse →](./payments/) |
| 📈 **Trading** | 152 | [Browse →](./trading/) |
| 🔐 **Security** | 120 | [Browse →](./security/) |
| ✨ **Design** | 49 | [Browse →](./design/) |
| 🎯 **Product** | 29 | [Browse →](./product/) |
| 🏷️ **Marketing** | 28 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [HugoBlox/kit](./aiml/hugoblox-kit.md) | ⭐ 9.4k | AI/ML |
| 2 | [xtekky/gpt4free](./aiml/xtekky-gpt4free.md) | ⭐ 66.2k | AI/ML |
| 3 | [Leonxlnx/taste-skill](./aiml/leonxlnx-taste-skill.md) | ⭐ 14.5k | AI/ML |
| 4 | [The-PR-Agent/pr-agent](./aiml/the-pr-agent-pr-agent.md) | ⭐ 11.1k | AI/ML |
| 5 | [kovidgoyal/calibre](./misc/kovidgoyal-calibre.md) | ⭐ 24.7k | Misc |
| 6 | [ImageMagick/ImageMagick](./frontend/imagemagick-imagemagick.md) | ⭐ 16.3k | Frontend |
| 7 | [google/comprehensive-rust](./aiml/google-comprehensive-rust.md) | ⭐ 32.9k | AI/ML |
| 8 | [nats-io/nats-server](./aiml/nats-io-nats-server.md) | ⭐ 19.7k | AI/ML |
| 9 | [firecracker-microvm/firecracker](./payments/firecracker-microvm-firecracker.md) | ⭐ 33.9k | Payments |
| 10 | [laurent22/joplin](./frontend/laurent22-joplin.md) | ⭐ 54.6k | Frontend |

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
