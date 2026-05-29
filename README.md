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

| Metric | 24h | 7 Days | 28 Days | 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 24h | 2.9h | 248.5h | ~1,059h* |
| User AI session hours | 7.3h | 39.6h | 57.4h | 57.4h |
| AI worker hours | 6.9h | 47.2h | 73.2h | 73.2h |
| AI concurrency hours | 20.0h | 117.4h | 208.5h | 208.5h |
| Interactive sessions | 28 | 84 | 113 | 113 |
| Worker sessions | 41 | 353 | 538 | 538 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 3,560 | 4K | 1.7M | 592.0M | $2,147.80 | $7,992.10 | $0.00 |
| gpt-5.5 | 56,901 | 279.3M | 10.3M | 4,185.5M | $1,955.51 | $11,301.07 | $8,994.66 |
| claude-sonnet-4-6 | 5,287 | 5K | 2.5M | 584.3M | $271.80 | $1,577.87 | $856.64 |
| claude-opus-4-7 | 696 | 828 | 375K | 106.0M | $258.72 | $1,431.47 | $0.00 |
| claude-haiku-4-5 | 326 | 335 | 75K | 32.2M | $3.97 | $23.23 | $51.15 |
| gpt-5.4-mini | 882 | 3.2M | 127K | 56.6M | $2.98 | $106.19 | $98.70 |
| **Total** | **67,652** | **282.6M** | **15.2M** | **5,556.9M** | **$4,640.78** | **$22,431.93** | **$10,001.16** |

_5,935.1M total tokens processed. 93.6% cache hit rate._

_$32,433.09 total saved ($22,431.93 caching + $10,001.16 model routing vs all-Opus)._

_Model savings are modest because ~93.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | $26,082.33 | $101,035.04 | $0.00 |
| claude-sonnet-4-6 | 71,305 | 148.9M | 22.0M | 6,176.0M | $3,143.34 | $16,675.28 | $10,519.66 |
| gpt-5.5 | 56,901 | 279.3M | 10.3M | 4,185.5M | $1,955.51 | $11,301.07 | $8,994.66 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | $20.68 | $54.19 | $1,939.33 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| big-pickle | 88 | 157K | 15K | 4.5M | $3.36 | $0.00 | $10.34 |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | $3.07 | $18.10 | $9.62 |
| gpt-5.4-mini | 882 | 3.2M | 127K | 56.6M | $2.98 | $106.19 | $98.70 |
| claude-sonnet-4-5 | 16 | 67 | 4K | 1.7M | $2.00 | $4.65 | $2.34 |
| **Total** | **219,868** | **765.5M** | **62.3M** | **18,910.9M** | **$32,474.87** | **$135,131.03** | **$21,700.56** |

_20,384.0M total tokens processed. 92.8% cache hit rate._

_$156,831.60 total saved ($135,131.03 caching + $21,700.56 model routing vs all-Opus)._

_Model savings are modest because ~92.8% of tokens are cache reads, where price differences between models are small._
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
- **[yc-remote-dev](https://github.com/MrRTi/yc-remote-dev)** -- Terraform config for remote dev environment at Yandex Cloud<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/alex-solovyev)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-05-29 04:33 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
