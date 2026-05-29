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
| Screen time (Linux) | 24h | 2.9h | 256.5h | ~1,059h* |
| User AI session hours | 8.7h | 41.2h | 59.0h | 59.0h |
| AI worker hours | 5.7h | 46.4h | 74.8h | 74.8h |
| AI concurrency hours | 20.3h | 118.4h | 211.8h | 211.8h |
| Interactive sessions | 26 | 84 | 117 | 117 |
| Worker sessions | 42 | 357 | 553 | 553 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.5 | 57,325 | 281.0M | 10.3M | 4,206.6M | $1,966.16 | $11,357.87 | $9,043.25 |
| claude-opus-4-6 | 2,706 | 3K | 1.1M | 480.9M | $1,829.66 | $6,492.88 | $0.00 |
| claude-sonnet-4-6 | 4,514 | 4K | 2.2M | 503.3M | $232.58 | $1,358.95 | $737.77 |
| claude-opus-4-7 | 521 | 621 | 280K | 79.5M | $195.68 | $1,074.02 | $0.00 |
| claude-haiku-4-5 | 326 | 335 | 75K | 32.2M | $3.97 | $23.23 | $51.15 |
| gpt-5.4-mini | 882 | 3.2M | 127K | 56.6M | $2.98 | $106.19 | $98.70 |
| **Total** | **66,274** | **284.3M** | **14.2M** | **5,359.3M** | **$4,231.03** | **$20,413.15** | **$9,930.87** |

_5,729.3M total tokens processed. 93.5% cache hit rate._

_$30,344.02 total saved ($20,413.15 caching + $9,930.87 model routing vs all-Opus)._

_Model savings are modest because ~93.5% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | $26,082.33 | $101,035.04 | $0.00 |
| claude-sonnet-4-6 | 71,305 | 148.9M | 22.0M | 6,176.0M | $3,143.34 | $16,675.28 | $10,519.66 |
| gpt-5.5 | 57,325 | 281.0M | 10.3M | 4,206.6M | $1,966.16 | $11,357.87 | $9,043.25 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | $20.68 | $54.19 | $1,939.33 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| big-pickle | 88 | 157K | 15K | 4.5M | $3.36 | $0.00 | $10.34 |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | $3.07 | $18.10 | $9.62 |
| gpt-5.4-mini | 882 | 3.2M | 127K | 56.6M | $2.98 | $106.19 | $98.70 |
| claude-sonnet-4-5 | 16 | 67 | 4K | 1.7M | $2.00 | $4.65 | $2.34 |
| **Total** | **220,292** | **767.2M** | **62.4M** | **18,932.0M** | **$32,485.52** | **$135,187.83** | **$21,749.15** |

_20,406.7M total tokens processed. 92.8% cache hit rate._

_$156,936.98 total saved ($135,187.83 caching + $21,749.15 model routing vs all-Opus)._

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
_Stats auto-updated 2026-05-29 12:33 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
