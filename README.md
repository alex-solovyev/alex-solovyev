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
| Screen time (Linux) | 24h | 168h | 672h | ~8712h* |
| Interactive human attention | 4.0h | 33.5h | 63.9h | 63.9h |
| Interactive AI generation | 7.1h | 20.7h | 153.0h | 153.0h |
| Worker-classified human attention | 3.4h | 5.3h | 6.6h | 6.6h |
| Worker/headless AI generation | 1.2h | 19.0h | 78.8h | 1628.7h |
| Additive observed work | 14.4h | 77.1h | 300.1h | 1,849.9h |
| Interactive sessions | 10 | 26 | 42 | 42 |
| Worker sessions | 90 | 598 | 968 | 9,914 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 140 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-sol | 13,051 | 51.7M | 2.6M | 1,066.3M | $927.77 | $2,879.08 | $2,058.87 |
| gpt-5.5 | 8,663 | 43.4M | 1.6M | 1,027.2M | $396.87 | $2,773.48 | $1,850.94 |
| gpt-5.6-terra | 916 | 3.5M | 167K | 39.9M | $23.36 | $107.94 | $100.22 |
| gpt-5.6-luna | 401 | 3.9M | 27K | 4.4M | $4.91 | $11.94 | $54.56 |
| **Total** | **23,031** | **102.7M** | **4.4M** | **2,137.9M** | **$1,352.91** | **$5,772.45** | **$4,064.60** |

_2,245.1M total tokens processed. 95.2% cache hit rate._

_$9,837.04 total saved ($5,772.45 caching + $4,064.60 model routing vs all-Opus)._

_Model savings are modest because ~95.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | $26,082.33 | $101,035.04 | $0.00 |
| gpt-5.5 | 142,622 | 672.9M | 26.0M | 10,941.2M | $4,940.31 | $29,541.35 | $22,768.92 |
| claude-sonnet-4-6 | 71,313 | 148.9M | 22.0M | 6,176.0M | $3,143.34 | $16,675.28 | $10,519.66 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gpt-5.6-sol | 16,912 | 69.2M | 3.6M | 1,337.4M | $1,198.79 | $3,610.99 | $2,653.34 |
| gpt-5.6-terra | 916 | 3.5M | 167K | 39.9M | $23.36 | $107.94 | $100.22 |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | $20.68 | $54.19 | $1,939.33 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| gpt-5.6-luna | 401 | 3.9M | 27K | 4.4M | $4.91 | $11.94 | $54.56 |
| gpt-5.4-mini | 1,451 | 6.0M | 181K | 77.4M | $4.50 | $145.18 | $155.32 |
| big-pickle | 88 | 157K | 15K | 4.5M | $3.36 | $0.00 | $10.34 |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | $3.07 | $18.10 | $9.62 |
| claude-sonnet-4-5 | 16 | 67 | 4K | 1.7M | $2.00 | $4.65 | $2.34 |
| **Total** | **324,395** | **1,238.7M** | **81.9M** | **27,069.2M** | **$36,688.25** | **$157,141.18** | **$38,339.57** |

_29,035.0M total tokens processed. 93.2% cache hit rate._

_$195,480.74 total saved ($157,141.18 caching + $38,339.57 model routing vs all-Opus)._

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
_Stats auto-updated 2026-08-11 20:07 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/alex-solovyev?theme=dark" />
    <img alt="alex-solovyev's commit history" src="https://commit-history.com/embed/alex-solovyev" />
  </picture>
</div>
