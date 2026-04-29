# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **11548** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 4427 | [Browse →](./aiml/) |
| 📦 **Misc** | 2206 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1138 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 910 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 703 | [Browse →](./backend/) |
| 🔧 **DevTools** | 685 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 412 | [Browse →](./crypto/) |
| 📊 **Data** | 248 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 244 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 140 | [Browse →](./mobile/) |
| 💳 **Payments** | 126 | [Browse →](./payments/) |
| 📈 **Trading** | 117 | [Browse →](./trading/) |
| 🔐 **Security** | 105 | [Browse →](./security/) |
| ✨ **Design** | 39 | [Browse →](./design/) |
| 🎯 **Product** | 26 | [Browse →](./product/) |
| 🏷️ **Marketing** | 22 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [samber/awesome-prometheus-alerts](./misc/samber-awesome-prometheus-alerts.md) | ⭐ 7.9k | Misc |
| 2 | [hwdsl2/docker-ipsec-vpn-server](./backend/hwdsl2-docker-ipsec-vpn-server.md) | ⭐ 7.1k | Backend |
| 3 | [emqx/emqx](./aiml/emqx-emqx.md) | ⭐ 16.2k | AI/ML |
| 4 | [keybase/client](./frontend/keybase-client.md) | ⭐ 9.2k | Frontend |
| 5 | [logseq/logseq](./product/logseq-logseq.md) | ⭐ 42.5k | Product |
| 6 | [LizardByte/Sunshine](./aiml/lizardbyte-sunshine.md) | ⭐ 36.5k | AI/ML |
| 7 | [firecracker-microvm/firecracker](./payments/firecracker-microvm-firecracker.md) | ⭐ 33.9k | Payments |
| 8 | [renovatebot/renovate](./devtools/renovatebot-renovate.md) | ⭐ 21.4k | DevTools |
| 9 | [netbirdio/netbird](./misc/netbirdio-netbird.md) | ⭐ 24.9k | Misc |
| 10 | [supermemoryai/supermemory](./orchestration/supermemoryai-supermemory.md) | ⭐ 22.3k | Orchestration |

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
