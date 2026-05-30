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
| Screen time (Linux) | 14.8h | 14.8h | 63.3h | ~1,059h* |
| User AI session hours | 8.8h | 42.6h | 67.7h | 67.7h |
| AI worker hours | 5.2h | 46.9h | 78.8h | 78.8h |
| AI concurrency hours | 18.0h | 116.6h | 228.5h | 228.5h |
| Interactive sessions | 19 | 86 | 127 | 127 |
| Worker sessions | 33 | 348 | 574 | 574 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.5 | 58,877 | 290.6M | 10.6M | 4,343.7M | $2,029.98 | $11,728.05 | $9,339.72 |
| claude-opus-4-6 | 1,299 | 1K | 574K | 247.2M | $1,127.26 | $3,337.80 | $0.00 |
| claude-sonnet-4-6 | 2,821 | 2K | 1.3M | 311.8M | $143.27 | $842.05 | $457.32 |
| claude-opus-4-7 | 46 | 50 | 26K | 7.2M | $20.01 | $97.21 | $0.00 |
| gpt-5.4-mini | 941 | 3.3M | 136K | 60.4M | $3.15 | $113.37 | $103.78 |
| claude-haiku-4-5 | 205 | 213 | 45K | 19.7M | $2.47 | $14.25 | $31.35 |
| **Total** | **64,189** | **294.0M** | **12.8M** | **4,990.2M** | **$3,326.14** | **$16,132.73** | **$9,932.17** |

_5,344.0M total tokens processed. 93.4% cache hit rate._

_$26,064.90 total saved ($16,132.73 caching + $9,932.17 model routing vs all-Opus)._

_Model savings are modest because ~93.4% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | $26,082.33 | $101,035.04 | $0.00 |
| claude-sonnet-4-6 | 71,305 | 148.9M | 22.0M | 6,176.0M | $3,143.34 | $16,675.28 | $10,519.66 |
| gpt-5.5 | 58,877 | 290.6M | 10.6M | 4,343.7M | $2,029.98 | $11,728.05 | $9,339.72 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | $20.68 | $54.19 | $1,939.33 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| big-pickle | 88 | 157K | 15K | 4.5M | $3.36 | $0.00 | $10.34 |
| gpt-5.4-mini | 941 | 3.3M | 136K | 60.4M | $3.15 | $113.37 | $103.78 |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | $3.07 | $18.10 | $9.62 |
| claude-sonnet-4-5 | 16 | 67 | 4K | 1.7M | $2.00 | $4.65 | $2.34 |
| **Total** | **221,903** | **777.0M** | **62.7M** | **19,072.9M** | **$32,549.51** | **$135,565.19** | **$22,050.70** |

_20,557.7M total tokens processed. 92.8% cache hit rate._

_$157,615.88 total saved ($135,565.19 caching + $22,050.70 model routing vs all-Opus)._

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
_Stats auto-updated 2026-05-30 05:33 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
