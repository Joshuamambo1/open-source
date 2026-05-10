# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **5207** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 2091 | [Browse →](./aiml/) |
| 📦 **Misc** | 916 | [Browse →](./misc/) |
| 🎨 **Frontend** | 522 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 486 | [Browse →](./orchestration/) |
| 🔧 **DevTools** | 274 | [Browse →](./devtools/) |
| ⚙️ **Backend** | 259 | [Browse →](./backend/) |
| ⛓️ **Crypto** | 188 | [Browse →](./crypto/) |
| 📊 **Data** | 120 | [Browse →](./data/) |
| 💳 **Payments** | 91 | [Browse →](./payments/) |
| 📱 **Mobile** | 64 | [Browse →](./mobile/) |
| 📈 **Trading** | 63 | [Browse →](./trading/) |
| 🚀 **DevOps & Infra** | 58 | [Browse →](./devopsinfra/) |
| 🔐 **Security** | 41 | [Browse →](./security/) |
| ✨ **Design** | 16 | [Browse →](./design/) |
| 🎯 **Product** | 12 | [Browse →](./product/) |
| 🏷️ **Marketing** | 6 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [formatjs/formatjs](./frontend/formatjs-formatjs.md) | ⭐ 14.7k | Frontend |
| 2 | [jaywcjlove/reference](./aiml/jaywcjlove-reference.md) | ⭐ 15.1k | AI/ML |
| 3 | [kubernetes-sigs/kubespray](./aiml/kubernetes-sigs-kubespray.md) | ⭐ 18.5k | AI/ML |
| 4 | [laramies/theHarvester](./aiml/laramies-theharvester.md) | ⭐ 16.2k | AI/ML |
| 5 | [PX4/PX4-Autopilot](./misc/px4-px4-autopilot.md) | ⭐ 11.7k | Misc |
| 6 | [clap-rs/clap](./misc/clap-rs-clap.md) | ⭐ 16.4k | Misc |
| 7 | [simple-icons/simple-icons](./design/simple-icons-simple-icons.md) | ⭐ 25.1k | Design |
| 8 | [mvanhorn/last30days-skill](./trading/mvanhorn-last30days-skill.md) | ⭐ 25.3k | Trading |
| 9 | [GyulyVGC/sniffnet](./frontend/gyulyvgc-sniffnet.md) | ⭐ 37.3k | Frontend |
| 10 | [jackocnr/intl-tel-input](./aiml/jackocnr-intl-tel-input.md) | ⭐ 8.2k | AI/ML |

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
