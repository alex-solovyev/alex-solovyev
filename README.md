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
| Screen time (Linux) | 2.8h | 2.8h | 51.3h | ~1,059h* |
| User AI session hours | 12.7h | 45.0h | 63.0h | 63.0h |
| AI worker hours | 6.7h | 46.6h | 76.2h | 76.2h |
| AI concurrency hours | 25.9h | 122.5h | 218.3h | 218.3h |
| Interactive sessions | 27 | 84 | 122 | 122 |
| Worker sessions | 44 | 354 | 559 | 559 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.5 | 57,958 | 285.3M | 10.4M | 4,266.8M | $1,994.23 | $11,520.39 | $9,174.27 |
| claude-opus-4-6 | 2,535 | 3K | 1.0M | 453.5M | $1,770.57 | $6,123.53 | $0.00 |
| claude-sonnet-4-6 | 4,312 | 4K | 2.1M | 480.4M | $222.74 | $1,297.23 | $704.61 |
| claude-opus-4-7 | 521 | 621 | 280K | 79.5M | $195.68 | $1,074.02 | $0.00 |
| claude-haiku-4-5 | 326 | 335 | 75K | 32.2M | $3.97 | $23.23 | $51.15 |
| gpt-5.4-mini | 882 | 3.2M | 127K | 56.6M | $2.98 | $106.19 | $98.70 |
| **Total** | **66,534** | **288.6M** | **14.2M** | **5,369.3M** | **$4,190.17** | **$20,144.59** | **$10,028.74** |

_5,742.4M total tokens processed. 93.5% cache hit rate._

_$30,173.33 total saved ($20,144.59 caching + $10,028.74 model routing vs all-Opus)._

_Model savings are modest because ~93.5% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | $26,082.33 | $101,035.04 | $0.00 |
| claude-sonnet-4-6 | 71,305 | 148.9M | 22.0M | 6,176.0M | $3,143.34 | $16,675.28 | $10,519.66 |
| gpt-5.5 | 57,958 | 285.3M | 10.4M | 4,266.8M | $1,994.23 | $11,520.39 | $9,174.27 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | $20.68 | $54.19 | $1,939.33 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| big-pickle | 88 | 157K | 15K | 4.5M | $3.36 | $0.00 | $10.34 |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | $3.07 | $18.10 | $9.62 |
| gpt-5.4-mini | 882 | 3.2M | 127K | 56.6M | $2.98 | $106.19 | $98.70 |
| claude-sonnet-4-5 | 16 | 67 | 4K | 1.7M | $2.00 | $4.65 | $2.34 |
| **Total** | **220,925** | **771.6M** | **62.5M** | **18,992.1M** | **$32,513.59** | **$135,350.35** | **$21,880.18** |

_20,471.4M total tokens processed. 92.8% cache hit rate._

_$157,230.53 total saved ($135,350.35 caching + $21,880.18 model routing vs all-Opus)._

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
_Stats auto-updated 2026-05-29 17:33 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
