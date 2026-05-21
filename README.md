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
| Screen time (Linux) | 13.1h | 13.1h | 59h | ~1,059h* |
| User AI session hours | 7.8h | 21.6h | 34.6h | 34.6h |
| AI worker hours | 6.8h | 24.7h | 81.1h | 81.1h |
| AI concurrency hours | 17.2h | 104.6h | 272.6h | 272.6h |
| Interactive sessions | 5 | 24 | 68 | 68 |
| Worker sessions | 45 | 130 | 497 | 498 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 7,481 | 123K | 3.1M | 1,091.7M | $3,906.44 | $14,738.64 | $0.00 |
| gpt-5.5 | 38,926 | 189.6M | 7.0M | 2,656.5M | $1,282.92 | $7,172.70 | $5,885.97 |
| claude-opus-4-7 | 3,025 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| claude-sonnet-4-6 | 13,326 | 13K | 6.1M | 1,458.3M | $653.62 | $3,937.54 | $2,121.63 |
| claude-haiku-4-5 | 520 | 691 | 124K | 51.6M | $6.16 | $37.20 | $82.19 |
| gpt-5.4-mini | 621 | 1.9M | 96K | 41.5M | $2.06 | $77.85 | $66.67 |
| claude-sonnet-4-5 | 1 | 3 | 1K | 0 | $0.26 | $0.00 | $0.06 |
| **Total** | **63,900** | **191.7M** | **18.0M** | **5,735.3M** | **$7,103.76** | **$31,843.97** | **$8,156.52** |

_6,114.0M total tokens processed. 93.8% cache hit rate._

_$40,000.50 total saved ($31,843.97 caching + $8,156.52 model routing vs all-Opus)._

_Model savings are modest because ~93.8% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | $26,082.33 | $101,035.04 | $0.00 |
| claude-sonnet-4-6 | 71,305 | 148.9M | 22.0M | 6,176.0M | $3,143.34 | $16,675.28 | $10,519.66 |
| gpt-5.5 | 38,926 | 189.6M | 7.0M | 2,656.5M | $1,282.92 | $7,172.70 | $5,885.97 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | $20.68 | $54.19 | $1,939.33 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| big-pickle | 88 | 157K | 15K | 4.5M | $3.36 | $0.00 | $10.34 |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | $3.07 | $18.10 | $9.62 |
| gpt-5.4-mini | 621 | 1.9M | 96K | 41.5M | $2.06 | $77.85 | $66.67 |
| claude-sonnet-4-5 | 16 | 67 | 4K | 1.7M | $2.00 | $4.65 | $2.34 |
| **Total** | **201,632** | **674.5M** | **59.0M** | **17,366.8M** | **$31,801.36** | **$130,974.32** | **$18,559.84** |

_18,745.5M total tokens processed. 92.6% cache hit rate._

_$149,534.16 total saved ($130,974.32 caching + $18,559.84 model routing vs all-Opus)._

_Model savings are modest because ~92.6% of tokens are cache reads, where price differences between models are small._
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
_Stats auto-updated 2026-05-21 07:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
