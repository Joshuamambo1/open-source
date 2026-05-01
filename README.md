# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **13841** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 5227 | [Browse →](./aiml/) |
| 📦 **Misc** | 2761 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1347 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 1042 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 851 | [Browse →](./backend/) |
| 🔧 **DevTools** | 823 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 488 | [Browse →](./crypto/) |
| 📊 **Data** | 318 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 303 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 172 | [Browse →](./mobile/) |
| 💳 **Payments** | 151 | [Browse →](./payments/) |
| 📈 **Trading** | 142 | [Browse →](./trading/) |
| 🔐 **Security** | 117 | [Browse →](./security/) |
| ✨ **Design** | 44 | [Browse →](./design/) |
| 🎯 **Product** | 29 | [Browse →](./product/) |
| 🏷️ **Marketing** | 26 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [invertase/react-native-firebase](./aiml/invertase-react-native-firebase.md) | ⭐ 12.3k | AI/ML |
| 2 | [awsdocs/aws-doc-sdk-examples](./aiml/awsdocs-aws-doc-sdk-examples.md) | ⭐ 10.4k | AI/ML |
| 3 | [VoltAgent/awesome-design-md](./aiml/voltagent-awesome-design-md.md) | ⭐ 69.1k | AI/ML |
| 4 | [influxdata/influxdb](./frontend/influxdata-influxdb.md) | ⭐ 31.5k | Frontend |
| 5 | [argoproj/argo-cd](./devopsinfra/argoproj-argo-cd.md) | ⭐ 22.8k | DevOps & Infra |
| 6 | [ruby/ruby](./misc/ruby-ruby.md) | ⭐ 23.6k | Misc |
| 7 | [LizardByte/Sunshine](./aiml/lizardbyte-sunshine.md) | ⭐ 36.6k | AI/ML |
| 8 | [future-architect/vuls](./aiml/future-architect-vuls.md) | ⭐ 12.1k | AI/ML |
| 9 | [shadps4-emu/shadPS4](./frontend/shadps4-emu-shadps4.md) | ⭐ 31k | Frontend |
| 10 | [pubkey/rxdb](./aiml/pubkey-rxdb.md) | ⭐ 23.2k | AI/ML |

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
