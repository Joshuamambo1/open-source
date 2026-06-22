# hatsu38/ghtrack

[![Stars](https://img.shields.io/github/stars/hatsu38/ghtrack?style=flat-square&color=yellow)](https://github.com/hatsu38/ghtrack/stargazers) [![Forks](https://img.shields.io/github/forks/hatsu38/ghtrack?style=flat-square&color=blue)](https://github.com/hatsu38/ghtrack/network) [![Language](https://img.shields.io/badge/lang-Unknown-informational?style=flat-square)](#) [![Score](https://img.shields.io/badge/score-45%2F100-brightgreen?style=flat-square)](#)

> Discovered from Hacker News (github-mentions)

## 📊 Stats

| | |
|---|---|
| ⭐ **Stars** | — |
| 🍴 **Forks** | — |
| 💻 **Language** | Unknown |
| 📈 **Score** | 45/100 |
| 🗓️ **Last push** | 2026-06-22 |
| 🔍 **Source** | hackernews |

## 🏷️ Topics

`hn` `github-mentions`

## 🎯 Categories

Automation

## 📝 Summary

### English

**Brief Summary (2‑3 sentences)**  
Ghtrack is an open‑source tool that automatically records the duration of GitHub Actions workflows and publishes the data to a GitHub Pages site. By visualising runtime metrics, it eliminates the need for developers to manually log or query workflow times, turning a repetitive chore into a repeatable, self‑service dashboard.  

**Value**  
- **Time‑saving automation** – No more manual copy‑pasting of workflow logs or ad‑hoc scripts; Ghtrack captures start/end timestamps and generates a human‑readable report each run.  
- **Visibility & debugging** – Teams can quickly spot slow or flaky jobs, optimise CI pipelines, and share performance trends with stakeholders via a static site.  
- **Low‑cost integration** – Works entirely within the GitHub ecosystem (Actions → Pages), requiring no external services or credentials.  

**Practical Adoption Path**  
1. **Fork or clone the repository** and review the license, issue tracker, and recent commit activity.  
2. **Add the Ghtrack workflow** to your existing CI configuration (usually a small YAML step that runs after your main jobs).  
3. **Configure the destination GitHub Pages branch** (e.g., `gh-pages`) and any optional settings (time‑zone, formatting).  
4. **Run a test build** to verify that the generated HTML page appears in the Pages site and that durations are correctly recorded.  
5. **Iterate** – adjust the workflow to include only the jobs you care about, and optionally extend the generated dashboard with custom charts.  

**Production Readiness**  
- **Maturity:** Medium – the project is recent (last update 2026‑06‑22) and has limited metadata signals, so it is suitable for prototypes, internal tooling, or low‑risk CI pipelines.  
- **Dependencies:** Only standard GitHub Actions and Pages; no external services, which simplifies security review.  
- **Maintenance checks:** Before committing to production, verify that the repository has an active maintainer, a clear contribution guideline, and a reasonable release cadence. Ensure the license is compatible with your organization’s policies.  
- **Risk mitigation:** Deploy first in a sandbox or staging repository, monitor for broken builds or missing data, and establish a fallback (e.g., manual log extraction) until you’re confident in the tool’s stability.  

Overall, Ghtrack offers a lightweight way to bring CI performance insight into GitHub Pages, but it should be piloted and vetted for maintenance and licensing before being rolled out to mission‑critical pipelines.

### Русский

Show HN: Ghtrack — это открытый инструмент, позволяющий автоматически собирать и визуализировать длительность GitHub Actions‑воркфлоу прямо на GitHub Pages, избавляя от ручного подсчёта и копирования метрик. Его обычно внедряют в прототипные или внутренние CI/CD‑процессы, где требуется быстро построить дашборд времени выполнения и интегрировать его с другими инструментами. Готовность к production — средняя: проект пригоден для пилотных решений, но перед масштабным использованием следует проверить лицензию, активность поддержки, наличие документации и частоту релизов.

### 中文

**项目简介**  
Show HN: **Ghtrack** 是一个开源工具，它可以把 GitHub Actions 工作流的执行时长实时同步到 GitHub Pages 上的可视化页面，帮助团队快速了解 CI/CD 的耗时情况，避免手动查询日志的繁琐。

**价值**  
- **自动化监控**：自动收集每次 workflow 的运行时间，省去手动打开 Actions 页面统计的步骤。  
- **可视化报告**：在 GitHub Pages 上生成简洁的图表或列表，便于团队成员、管理者快速定位慢任务。  
- **提升效率**：通过统一的可视化视图，帮助团队发现并优化耗时较长的步骤，从而缩短整体 CI/CD 周期。

**典型接入方式**  
1. **在仓库根目录添加 `ghtrack.yml` 配置文件**，指定要监控的 workflow 名称或 ID。  
2. **在对应的 workflow 中添加一个步骤**，使用官方提供的 Action（如 `ghtrack/action@vX`）将 `run_time` 元数据写入仓库的 `ghtrack-data/` 目录。  
3. **在 GitHub Pages 分支（如 `gh-pages`）中部署一个静态页面**，该页面通过 GitHub Pages 自动读取 `ghtrack-data/` 中的 JSON/CSV 文件并渲染图表（可使用 Chart.js、D3 等前端库）。  
4. **可选**：通过 GitHub Secrets 配置 API Token，以便 Action 有权限写入 Pages 分支。

**生产可用性**  
- **成熟度**：目前评分 45/100，属于 **中等** 稳定性。适合原型、内部工具或实验性项目使用。  
- **准备工作**：在正式上线前需要检查以下方面：  
  - 许可证是否兼容公司政策；  
  - 项目维护频率、Issue 处理情况以及发布节奏；  
  - 文档完整性（尤其是部署到 GitHub Pages 的步骤）；  
  - 与现有 CI/CD 流程的兼容性（是否会导致额外的运行时间或权限冲突）。  
- **风险**：元数据的集成信号较少，可能需要自行补充监控字段或进行二次加工；若项目停止维护，需自行承担后续维护成本。  

总体来说，Ghtrack 在 **自动化、可视化 CI 时长** 方面提供了即插即用的解决方案，适合作为内部监控仪表盘的起点，但在生产环境使用前建议进行充分的审查与测试。

## 🧭 Practical evaluation

**Value:** Show HN: Ghtrack: track GitHub Actions workflow duration in GitHub Pages helps remove repetitive manual operations from a workflow.

**Best use cases**

- remove manual work
- connect tools into repeatable flows
- schedule operational tasks

**Integration notes:** Needs manual inspection before adoption because integration signals are sparse in the discovered metadata.

**Production readiness:** Medium: useful for prototypes or internal workflows, with dependency and maintenance checks before production.

**Quality signals**

- updated 2026-06-22
- 2 topics

**Risks:** Quality signals are limited; verify license, maintenance, docs, issues, and release cadence before using it.

## 🧮 Score breakdown

| Dimension | Score |
|---|---:|
| forks | 0/100 |
| stars | 0/100 |
| topics | 25/100 |
| outlook | 57/100 |
| quality | 41/100 |
| recency | 100/100 |
| adoption | 0/100 |
| production | 58/100 |
| usefulness | 58/100 |
| integration | 30/100 |
| sourceTrust | 80/100 |

---

<sub>🔭 Discovered 2026-06-22 · [View on GitHub](https://github.com/hatsu38/ghtrack) · [← Back to Automation](./README.md)</sub>
