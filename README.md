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
| Screen time (Linux) | 24h | 106.1h | 139.9h | ~1,059h* |
| User AI session hours | 0.0h | 35.9h | 65.5h | 65.5h |
| AI worker hours | 0.4h | 29.1h | 102.5h | 102.5h |
| AI concurrency hours | 0.4h | 77.2h | 280.3h | 280.3h |
| Interactive sessions | 0 | 38 | 53 | 53 |
| Worker sessions | 1 | 156 | 600 | 600 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 8,408 | 124K | 3.4M | 1,278.1M | $4,577.55 | $17,255.56 | $0.00 |
| claude-opus-4-7 | 3,025 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gpt-5.5 | 30,546 | 154.4M | 5.6M | 2,116.6M | $1,031.94 | $5,715.00 | $4,735.78 |
| claude-sonnet-4-6 | 14,088 | 14K | 6.4M | 1,516.1M | $682.58 | $4,093.49 | $2,206.96 |
| claude-haiku-4-5 | 520 | 691 | 124K | 51.6M | $6.16 | $37.20 | $82.19 |
| gpt-5.4-mini | 621 | 1.9M | 96K | 41.5M | $2.06 | $77.85 | $66.67 |
| claude-sonnet-4-5 | 1 | 3 | 1K | 0 | $0.26 | $0.00 | $0.06 |
| **Total** | **57,209** | **156.5M** | **17.3M** | **5,439.7M** | **$7,552.85** | **$33,059.15** | **$7,091.67** |

_5,803.9M total tokens processed. 93.7% cache hit rate._

_$40,150.81 total saved ($33,059.15 caching + $7,091.67 model routing vs all-Opus)._

_Model savings are modest because ~93.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | $26,082.33 | $101,035.04 | $0.00 |
| claude-sonnet-4-6 | 71,305 | 148.9M | 22.0M | 6,176.0M | $3,143.34 | $16,675.28 | $10,519.66 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gpt-5.5 | 30,546 | 154.4M | 5.6M | 2,116.6M | $1,031.94 | $5,715.00 | $4,735.78 |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | $20.68 | $54.19 | $1,939.33 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| big-pickle | 88 | 157K | 15K | 4.5M | $3.36 | $0.00 | $10.34 |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | $3.07 | $18.10 | $9.62 |
| gpt-5.4-mini | 621 | 1.9M | 96K | 41.5M | $2.06 | $77.85 | $66.67 |
| claude-sonnet-4-5 | 16 | 67 | 4K | 1.7M | $2.00 | $4.65 | $2.34 |
| **Total** | **193,252** | **639.3M** | **57.7M** | **16,826.9M** | **$31,550.38** | **$129,516.62** | **$17,409.65** |

_18,169.1M total tokens processed. 92.6% cache hit rate._

_$146,926.28 total saved ($129,516.62 caching + $17,409.65 model routing vs all-Opus)._

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
_Stats auto-updated 2026-05-17 11:25 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
