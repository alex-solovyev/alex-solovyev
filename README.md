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
| Screen time (Linux) | 24h | 2.9h | 224.5h | ~1,059h* |
| User AI session hours | 8.1h | 40.4h | 51.4h | 51.5h |
| AI worker hours | 7.2h | 47.2h | 66.1h | 66.1h |
| AI concurrency hours | 18.6h | 117.7h | 189.6h | 189.7h |
| Interactive sessions | 18 | 72 | 91 | 91 |
| Worker sessions | 59 | 374 | 497 | 497 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 4,352 | 119K | 2.0M | 692.5M | $2,479.17 | $9,349.34 | $0.00 |
| gpt-5.5 | 54,364 | 263.9M | 9.8M | 3,962.5M | $1,851.81 | $10,698.93 | $8,514.13 |
| claude-sonnet-4-6 | 6,034 | 6K | 2.9M | 684.4M | $312.25 | $1,848.12 | $996.03 |
| claude-opus-4-7 | 807 | 956 | 443K | 121.2M | $294.43 | $1,636.90 | $0.00 |
| claude-haiku-4-5 | 326 | 335 | 75K | 32.2M | $3.97 | $23.23 | $51.15 |
| gpt-5.4-mini | 882 | 3.2M | 127K | 56.6M | $2.98 | $106.19 | $98.70 |
| claude-sonnet-4-5 | 1 | 3 | 1K | 0 | $0.26 | $0.00 | $0.06 |
| **Total** | **66,766** | **267.3M** | **15.5M** | **5,549.7M** | **$4,944.87** | **$23,662.72** | **$9,660.08** |

_5,923.2M total tokens processed. 93.7% cache hit rate._

_$33,322.80 total saved ($23,662.72 caching + $9,660.08 model routing vs all-Opus)._

_Model savings are modest because ~93.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | $26,082.33 | $101,035.04 | $0.00 |
| claude-sonnet-4-6 | 71,305 | 148.9M | 22.0M | 6,176.0M | $3,143.34 | $16,675.28 | $10,519.66 |
| gpt-5.5 | 54,364 | 263.9M | 9.8M | 3,962.5M | $1,851.81 | $10,698.93 | $8,514.13 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | $20.68 | $54.19 | $1,939.33 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| big-pickle | 88 | 157K | 15K | 4.5M | $3.36 | $0.00 | $10.34 |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | $3.07 | $18.10 | $9.62 |
| gpt-5.4-mini | 882 | 3.2M | 127K | 56.6M | $2.98 | $106.19 | $98.70 |
| claude-sonnet-4-5 | 16 | 67 | 4K | 1.7M | $2.00 | $4.65 | $2.34 |
| **Total** | **217,331** | **750.2M** | **61.9M** | **18,687.9M** | **$32,371.17** | **$134,528.89** | **$21,220.03** |

_20,145.1M total tokens processed. 92.8% cache hit rate._

_$155,748.92 total saved ($134,528.89 caching + $21,220.03 model routing vs all-Opus)._

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
_Stats auto-updated 2026-05-28 04:32 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
