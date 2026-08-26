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
| Screen time (Linux) | 24h | 168h | 672h | ~8716h* |
| Interactive human attention | 0.2h | 29.3h | 125.9h | 131.4h |
| Interactive AI generation | 3.4h | 31.6h | 226.3h | 230.4h |
| Worker-classified human attention | 1.2h | 10.6h | 17.4h | 17.5h |
| Worker/headless AI generation | 3.3h | 25.3h | 69.7h | 1671.3h |
| Additive observed work | 8.1h | 95.0h | 435.1h | 2,046.5h |
| Interactive sessions | 3 | 9 | 65 | 68 |
| Worker sessions | 88 | 482 | 1,603 | 10,824 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 155 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.5 | 11,476 | 61.6M | 2.6M | 1,385.9M | $550.72 | $3,741.99 | $2,562.26 |
| gpt-5.6-sol | 5,197 | 21.7M | 1.0M | 431.4M | $381.71 | $1,164.80 | $842.84 |
| gpt-5.6-terra | 6,399 | 30.9M | 1.3M | 423.2M | $175.98 | $1,142.80 | $959.77 |
| gpt-5.6-luna | 1,684 | 15.5M | 272K | 101.2M | $5.97 | $273.43 | $323.97 |
| **Total** | **24,756** | **129.8M** | **5.3M** | **2,341.8M** | **$1,114.38** | **$6,323.01** | **$4,688.84** |

_2,477.0M total tokens processed. 94.5% cache hit rate._

_$11,011.85 total saved ($6,323.01 caching + $4,688.84 model routing vs all-Opus)._

_Model savings are modest because ~94.5% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | $26,082.33 | $101,035.04 | $0.00 |
| gpt-5.5 | 146,826 | 696.2M | 27.3M | 11,453.6M | $5,150.13 | $30,924.95 | $23,740.67 |
| claude-sonnet-4-6 | 71,313 | 148.9M | 22.0M | 6,176.0M | $3,143.34 | $16,675.28 | $10,519.66 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gpt-5.6-sol | 17,418 | 71.8M | 3.7M | 1,383.4M | $1,240.84 | $3,735.43 | $2,748.78 |
| gpt-5.6-terra | 6,466 | 31.1M | 1.3M | 427.1M | $177.41 | $1,153.37 | $967.79 |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | $20.68 | $54.19 | $1,939.33 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| gpt-5.6-luna | 1,684 | 15.5M | 272K | 101.2M | $5.97 | $273.43 | $323.97 |
| gpt-5.4-mini | 1,451 | 6.0M | 181K | 77.4M | $4.50 | $145.18 | $155.32 |
| big-pickle | 88 | 157K | 15K | 4.5M | $3.36 | $0.00 | $10.34 |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | $3.07 | $18.10 | $9.62 |
| claude-sonnet-4-5 | 16 | 67 | 4K | 1.7M | $2.00 | $4.65 | $2.34 |
| **Total** | **335,938** | **1,303.7M** | **84.8M** | **28,111.7M** | **$37,095.23** | **$159,956.12** | **$40,543.73** |

_30,145.5M total tokens processed. 93.3% cache hit rate._

_$200,499.85 total saved ($159,956.12 caching + $40,543.73 model routing vs all-Opus)._

_Model savings are modest because ~93.3% of tokens are cache reads, where price differences between models are small._
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
_Stats auto-updated 2026-08-26 00:09 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/alex-solovyev?theme=dark" />
    <img alt="alex-solovyev's commit history" src="https://commit-history.com/embed/alex-solovyev" />
  </picture>
</div>
