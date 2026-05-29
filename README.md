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
| Screen time (Linux) | 7.8h | 7.8h | 56.3h | ~1,059h* |
| User AI session hours | 17.4h | 46.0h | 67.7h | 67.7h |
| AI worker hours | 7.1h | 47.6h | 77.9h | 77.9h |
| AI concurrency hours | 30.1h | 122.7h | 225.9h | 225.9h |
| Interactive sessions | 30 | 87 | 126 | 126 |
| Worker sessions | 43 | 356 | 567 | 567 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.5 | 58,644 | 289.3M | 10.6M | 4,333.1M | $2,023.36 | $11,699.56 | $9,309.49 |
| claude-opus-4-6 | 1,642 | 2K | 711K | 300.2M | $1,378.68 | $4,053.72 | $0.00 |
| claude-sonnet-4-6 | 3,860 | 3K | 1.8M | 430.5M | $197.46 | $1,162.48 | $629.09 |
| claude-opus-4-7 | 404 | 482 | 224K | 61.4M | $154.15 | $829.30 | $0.00 |
| gpt-5.4-mini | 941 | 3.3M | 136K | 60.4M | $3.15 | $113.37 | $103.78 |
| claude-haiku-4-5 | 244 | 264 | 55K | 23.5M | $2.92 | $16.95 | $37.35 |
| **Total** | **65,735** | **292.7M** | **13.6M** | **5,209.4M** | **$3,759.72** | **$17,875.38** | **$10,079.71** |

_5,576.2M total tokens processed. 93.4% cache hit rate._

_$27,955.09 total saved ($17,875.38 caching + $10,079.71 model routing vs all-Opus)._

_Model savings are modest because ~93.4% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | $26,082.33 | $101,035.04 | $0.00 |
| claude-sonnet-4-6 | 71,305 | 148.9M | 22.0M | 6,176.0M | $3,143.34 | $16,675.28 | $10,519.66 |
| gpt-5.5 | 58,644 | 289.3M | 10.6M | 4,333.1M | $2,023.36 | $11,699.56 | $9,309.49 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | $20.68 | $54.19 | $1,939.33 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| big-pickle | 88 | 157K | 15K | 4.5M | $3.36 | $0.00 | $10.34 |
| gpt-5.4-mini | 941 | 3.3M | 136K | 60.4M | $3.15 | $113.37 | $103.78 |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | $3.07 | $18.10 | $9.62 |
| claude-sonnet-4-5 | 16 | 67 | 4K | 1.7M | $2.00 | $4.65 | $2.34 |
| **Total** | **221,670** | **775.7M** | **62.6M** | **19,062.3M** | **$32,542.89** | **$135,536.70** | **$22,020.47** |

_20,545.8M total tokens processed. 92.8% cache hit rate._

_$157,557.17 total saved ($135,536.70 caching + $22,020.47 model routing vs all-Opus)._

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
_Stats auto-updated 2026-05-29 22:33 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
