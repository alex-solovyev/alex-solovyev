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
| Screen time (Linux) | 24h | 104.6h | 150.5h | ~1,059h* |
| User AI session hours | 0.3h | 27.9h | 30.7h | 30.7h |
| AI worker hours | 5.2h | 42.9h | 62.1h | 62.1h |
| AI concurrency hours | 5.6h | 126.8h | 152.2h | 152.2h |
| Interactive sessions | 8 | 56 | 90 | 90 |
| Worker sessions | 40 | 309 | 446 | 446 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 5,845 | 121K | 2.6M | 855.0M | $3,033.48 | $11,543.78 | $0.00 |
| gpt-5.5 | 46,366 | 223.4M | 8.3M | 3,290.9M | $1,552.52 | $8,885.53 | $7,132.36 |
| claude-sonnet-4-6 | 12,080 | 12K | 5.6M | 1,350.4M | $601.48 | $3,646.34 | $1,960.43 |
| claude-opus-4-7 | 1,084 | 1K | 597K | 164.7M | $406.08 | $2,224.23 | $0.00 |
| claude-haiku-4-5 | 475 | 646 | 114K | 47.9M | $5.72 | $34.50 | $76.15 |
| gpt-5.4-mini | 846 | 3.1M | 122K | 54.9M | $2.87 | $103.06 | $95.23 |
| claude-sonnet-4-5 | 1 | 3 | 1K | 0 | $0.26 | $0.00 | $0.06 |
| **Total** | **66,697** | **226.6M** | **17.4M** | **5,764.1M** | **$5,602.41** | **$26,437.44** | **$9,264.24** |

_6,128.3M total tokens processed. 94.1% cache hit rate._

_$35,701.68 total saved ($26,437.44 caching + $9,264.24 model routing vs all-Opus)._

_Model savings are modest because ~94.1% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | $26,082.33 | $101,035.04 | $0.00 |
| claude-sonnet-4-6 | 71,305 | 148.9M | 22.0M | 6,176.0M | $3,143.34 | $16,675.28 | $10,519.66 |
| gpt-5.5 | 46,366 | 223.4M | 8.3M | 3,290.9M | $1,552.52 | $8,885.53 | $7,132.36 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | $20.68 | $54.19 | $1,939.33 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| big-pickle | 88 | 157K | 15K | 4.5M | $3.36 | $0.00 | $10.34 |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | $3.07 | $18.10 | $9.62 |
| gpt-5.4-mini | 846 | 3.1M | 122K | 54.9M | $2.87 | $103.06 | $95.23 |
| claude-sonnet-4-5 | 16 | 67 | 4K | 1.7M | $2.00 | $4.65 | $2.34 |
| **Total** | **209,297** | **709.4M** | **60.4M** | **18,014.6M** | **$32,071.77** | **$132,712.36** | **$19,834.79** |

_19,429.6M total tokens processed. 92.7% cache hit rate._

_$152,547.15 total saved ($132,712.36 caching + $19,834.79 model routing vs all-Opus)._

_Model savings are modest because ~92.7% of tokens are cache reads, where price differences between models are small._
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
- **[wordpress-cd](https://github.com/rossigee/wordpress-cd)** -- No description
- **[wordpress-cd-s3](https://github.com/rossigee/wordpress-cd-s3)** -- Wordpress CD driver to deploy WP artifacts to S3 buckets.
- **[yc-remote-dev](https://github.com/MrRTi/yc-remote-dev)** -- Terraform config for remote dev environment at Yandex Cloud<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/alex-solovyev)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-05-25 02:29 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
