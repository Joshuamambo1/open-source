# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **12060** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 4596 | [Browse →](./aiml/) |
| 📦 **Misc** | 2338 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1178 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 947 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 735 | [Browse →](./backend/) |
| 🔧 **DevTools** | 716 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 431 | [Browse →](./crypto/) |
| 📊 **Data** | 267 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 259 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 148 | [Browse →](./mobile/) |
| 💳 **Payments** | 129 | [Browse →](./payments/) |
| 📈 **Trading** | 125 | [Browse →](./trading/) |
| 🔐 **Security** | 107 | [Browse →](./security/) |
| ✨ **Design** | 37 | [Browse →](./design/) |
| 🎯 **Product** | 25 | [Browse →](./product/) |
| 🏷️ **Marketing** | 22 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [giampaolo/psutil](./misc/giampaolo-psutil.md) | ⭐ 11.2k | Misc |
| 2 | [btcpayserver/btcpayserver](./crypto/btcpayserver-btcpayserver.md) | ⭐ 7.5k | Crypto |
| 3 | [gnuradio/gnuradio](./security/gnuradio-gnuradio.md) | ⭐ 6.1k | Security |
| 4 | [redox-os/redox](./misc/redox-os-redox.md) | ⭐ 16.3k | Misc |
| 5 | [D4Vinci/Scrapling](./aiml/d4vinci-scrapling.md) | ⭐ 39.3k | AI/ML |
| 6 | [BasedHardware/omi](./aiml/basedhardware-omi.md) | ⭐ 12.3k | AI/ML |
| 7 | [Raphire/Win11Debloat](./devtools/raphire-win11debloat.md) | ⭐ 45.5k | DevTools |
| 8 | [Kilo-Org/kilocode](./aiml/kilo-org-kilocode.md) | ⭐ 18.7k | AI/ML |
| 9 | [argoproj/argo-cd](./devopsinfra/argoproj-argo-cd.md) | ⭐ 22.8k | DevOps & Infra |
| 10 | [nocobase/nocobase](./aiml/nocobase-nocobase.md) | ⭐ 22.2k | AI/ML |

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
