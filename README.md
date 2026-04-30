# 🌟 Open Scout Catalog

> Auto-curated catalog of promising open-source projects.
> Scouted from GitHub · HackerNews · Reddit · ProductHunt. Updated every 30 minutes by [RepoScout](https://github.com/kirbudilov01/reposearchengine).

---

## 📊 At a glance

| | |
|---|---|
| 🗂️ **Total projects** | **12986** |
| 📁 **Categories** | **16** |
| 🔄 **Auto-sync** | every 30 min via GitHub Actions |
| 🧠 **Summaries** | LLM-generated (OpenRouter · Ollama · Claude · OpenAI) |

## 🗂️ Categories

| Category | Projects | |
|---|---|---|
| 🤖 **AI/ML** | 4947 | [Browse →](./aiml/) |
| 📦 **Misc** | 2549 | [Browse →](./misc/) |
| 🎨 **Frontend** | 1257 | [Browse →](./frontend/) |
| 🧩 **Orchestration** | 995 | [Browse →](./orchestration/) |
| ⚙️ **Backend** | 788 | [Browse →](./backend/) |
| 🔧 **DevTools** | 768 | [Browse →](./devtools/) |
| ⛓️ **Crypto** | 471 | [Browse →](./crypto/) |
| 📊 **Data** | 294 | [Browse →](./data/) |
| 🚀 **DevOps & Infra** | 282 | [Browse →](./devopsinfra/) |
| 📱 **Mobile** | 161 | [Browse →](./mobile/) |
| 💳 **Payments** | 136 | [Browse →](./payments/) |
| 📈 **Trading** | 134 | [Browse →](./trading/) |
| 🔐 **Security** | 111 | [Browse →](./security/) |
| ✨ **Design** | 41 | [Browse →](./design/) |
| 🎯 **Product** | 27 | [Browse →](./product/) |
| 🏷️ **Marketing** | 25 | [Browse →](./marketing/) |

## 🔥 Top 10 by score

| # | Project | Stars | Category |
|---|---|---|---|
| 1 | [apache/ignite](./backend/apache-ignite.md) | ⭐ 5.1k | Backend |
| 2 | [JuliusBrussee/caveman](./aiml/juliusbrussee-caveman.md) | ⭐ 51.3k | AI/ML |
| 3 | [ceph/ceph](./crypto/ceph-ceph.md) | ⭐ 16.5k | Crypto |
| 4 | [openshift/origin](./aiml/openshift-origin.md) | ⭐ 8.6k | AI/ML |
| 5 | [zitadel/zitadel](./aiml/zitadel-zitadel.md) | ⭐ 13.7k | AI/ML |
| 6 | [firecracker-microvm/firecracker](./payments/firecracker-microvm-firecracker.md) | ⭐ 33.9k | Payments |
| 7 | [mudler/LocalAI](./aiml/mudler-localai.md) | ⭐ 45.9k | AI/ML |
| 8 | [jackocnr/intl-tel-input](./aiml/jackocnr-intl-tel-input.md) | ⭐ 8.2k | AI/ML |
| 9 | [Snailclimb/JavaGuide](./aiml/snailclimb-javaguide.md) | ⭐ 155.4k | AI/ML |
| 10 | [activepieces/activepieces](./aiml/activepieces-activepieces.md) | ⭐ 22k | AI/ML |

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
