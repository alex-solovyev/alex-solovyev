# alex-solovyev

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Shell](https://img.shields.io/badge/-Shell-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/-Git-F05032?style=flat-square&logo=git&logoColor=white)
> Shipping with AI agents around the clock -- human hours for thinking, machine hours for doing.
>
> Stats auto-updated by [aidevops](https://aidevops.sh).

<!-- STATS-START -->
## Work with AI

| Metric | Yesterday | Prior 7 Days | Prior 28 Days | Prior 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 24h | 168h | 672h | ~8713h* |
| Interactive human attention | 13.4h | 35.1h | 89.4h | 89.4h |
| Interactive AI generation | 7.0h | 25.7h | 170.6h | 170.6h |
| Worker-classified human attention | 0.0h | 5.3h | 6.6h | 6.6h |
| Worker/headless AI generation | 0.9h | 11.4h | 56.3h | 1631.7h |
| Additive observed work | 21.3h | 75.9h | 320.6h | 1,896.0h |
| Interactive sessions | 6 | 18 | 45 | 45 |
| Worker sessions | 47 | 439 | 960 | 9,999 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 143 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 10,637 | 41.9M | 2.1M | 878.5M | $760.20 | $2,372.08 | $1,686.53 |
| gpt-5.5 | 9,061 | 46.6M | 1.7M | 1,083.9M | $420.93 | $2,926.74 | $1,963.41 |
| gpt-5.6-terra | 1,097 | 4.1M | 210K | 52.5M | $29.16 | $141.93 | $125.94 |
| gpt-5.6-luna | 471 | 4.8M | 29K | 4.4M | $5.86 | $12.04 | $65.33 |
| **Total** | **21,266** | **97.6M** | **4.0M** | **2,019.5M** | **$1,216.15** | **$5,452.78** | **$3,841.20** |

_2,121.3M total tokens processed. 95.2% cache hit rate._

_$9,293.98 total saved ($5,452.78 caching + $3,841.20 model routing vs all-Opus)._

_Model savings are modest because ~95.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | $26,082.33 | $101,035.04 | $0.00 |
| gpt-5.5 | 143,020 | 676.1M | 26.1M | 10,998.0M | $4,964.37 | $29,694.61 | $22,881.39 |
| claude-sonnet-4-6 | 71,313 | 148.9M | 22.0M | 6,176.0M | $3,143.34 | $16,675.28 | $10,519.66 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gpt-5.6-sol | 16,912 | 69.2M | 3.6M | 1,337.4M | $1,198.79 | $3,610.99 | $2,653.34 |
| gpt-5.6-terra | 1,097 | 4.1M | 210K | 52.5M | $29.16 | $141.93 | $125.94 |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | $20.68 | $54.19 | $1,939.33 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| gpt-5.6-luna | 471 | 4.8M | 29K | 4.4M | $5.86 | $12.04 | $65.33 |
| gpt-5.4-mini | 1,451 | 6.0M | 181K | 77.4M | $4.50 | $145.18 | $155.32 |
| big-pickle | 88 | 157K | 15K | 4.5M | $3.36 | $0.00 | $10.34 |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | $3.07 | $18.10 | $9.62 |
| claude-sonnet-4-5 | 16 | 67 | 4K | 1.7M | $2.00 | $4.65 | $2.34 |
| **Total** | **325,044** | **1,243.5M** | **82.1M** | **27,138.6M** | **$36,719.06** | **$157,328.51** | **$38,488.52** |

_29,109.3M total tokens processed. 93.2% cache hit rate._

_$195,817.03 total saved ($157,328.51 caching + $38,488.52 model routing vs all-Opus)._

_Model savings are modest because ~93.2% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[task-manager-python](https://github.com/alex-solovyev/task-manager-python)** -- No description
<!-- CONTRIBUTIONS-START -->
## Contributions

- **[aidevops](https://github.com/marcusquinn/aidevops)** -- Vibe-Coding is easy. DevOps is hard. AI DevOps automates your software, business, and personal development with managed infrastructure through AI chat in OpenCode. Opinionated tools, services, CLI & API tech-stack — for speed, security, and 24/7 results. Open-source-preferred, and SOTA everything.
- **[jquery-ui](https://github.com/jquery/jquery-ui)** -- The official jQuery user interface library.
- **[openwrt-slide-switch](https://github.com/jefferyto/openwrt-slide-switch)** -- Translate slide switch position changes into normal button presses
- **[quickfile-mcp](https://github.com/marcusquinn/quickfile-mcp)** -- MCP server for QuickFile UK accounting software - invoices, clients, purchases, banking, and reports
- **[ru-study-python](https://github.com/dualboot-partners/eu-python-learn-challenge)** -- No description
- **[shadowsocks](https://github.com/shadowsocks/shadowsocks)** -- No description
- **[tambo](https://github.com/tambo-ai/tambo)** -- Generative UI SDK for React
- **[wordpress-cd](https://github.com/rossigee/wordpress-cd)** -- No description
- **[wordpress-cd-s3](https://github.com/rossigee/wordpress-cd-s3)** -- Wordpress CD driver to deploy WP artifacts to S3 buckets.
- **[yc-remote-dev](https://github.com/MrRTi/yc-remote-dev)** -- Terraform config for remote dev environment at Yandex Cloud
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/alex-solovyev)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-08-14 00:07 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/alex-solovyev?theme=dark" />
    <img alt="alex-solovyev's commit history" src="https://commit-history.com/embed/alex-solovyev" />
  </picture>
</div>
