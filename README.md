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
| Screen time (Linux) | 0.6h | 0.6h | 29.7h | ~1,059h* |
| User AI session hours | 0.1h | 20.5h | 242.1h | 622.4h |
| AI worker hours | 0.0h | 15.9h | 125.9h | 339.8h |
| AI concurrency hours | 0.1h | 36.4h | 368.0h | 962.3h |
| Interactive sessions | 1 | 28 | 99 | 801 |
| Worker sessions | 0 | 103 | 905 | 1,899 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are interactive session time (user attention + AI generation) measured from AI message timestamps._

_AI session 365-day totals cover 70 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.5 | 48,243 | 232.0M | 8.3M | 3,748.4M | $1,687.12 | $10,120.84 | $7,786.73 |
| gpt-5.4-mini | 626 | 2.7M | 65K | 27.9M | $1.79 | $52.46 | $63.51 |
| **Total** | **48,869** | **234.8M** | **8.4M** | **3,776.4M** | **$1,688.91** | **$10,173.29** | **$7,850.24** |

_4,019.7M total tokens processed. 93.9% cache hit rate._

_$18,023.53 total saved ($10,173.29 caching + $7,850.24 model routing vs all-Opus)._

_Model savings are modest because ~93.9% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | $26,082.33 | $101,035.04 | $0.00 |
| claude-sonnet-4-6 | 71,305 | 148.9M | 22.0M | 6,176.0M | $3,143.34 | $16,675.28 | $10,519.66 |
| gpt-5.5 | 77,624 | 382.6M | 13.9M | 5,805.4M | $2,690.41 | $15,674.60 | $12,392.81 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | $20.68 | $54.19 | $1,939.33 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| gpt-5.4-mini | 1,247 | 4.7M | 161K | 69.4M | $3.85 | $130.31 | $130.18 |
| big-pickle | 88 | 157K | 15K | 4.5M | $3.36 | $0.00 | $10.34 |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | $3.07 | $18.10 | $9.62 |
| claude-sonnet-4-5 | 16 | 67 | 4K | 1.7M | $2.00 | $4.65 | $2.34 |
| **Total** | **240,956** | **870.3M** | **66.0M** | **20,543.6M** | **$33,210.64** | **$139,528.68** | **$25,130.19** |

_22,125.0M total tokens processed. 92.9% cache hit rate._

_$164,658.86 total saved ($139,528.68 caching + $25,130.19 model routing vs all-Opus)._

_Model savings are modest because ~92.9% of tokens are cache reads, where price differences between models are small._
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
_Stats auto-updated 2026-06-15 18:37 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
