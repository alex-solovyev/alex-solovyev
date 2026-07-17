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

| Metric | Yesterday | Prior 7 Days | Prior 28 Days | Prior 365 Days |
| --- | ---: | ---: | ---: | ---: |
| Screen time (Linux) | 24h | 168h | 672h | ~8704h* |
| Interactive human attention | 0.0h | 12.4h | 88.5h | 352.7h |
| Interactive AI generation | 0.3h | 6.2h | 82.6h | 429.3h |
| Worker-classified human attention | 0.0h | 0.0h | 5.1h | 17.6h |
| Worker/headless AI generation | 9.4h | 55.1h | 245.8h | 1205.2h |
| Additive observed work | 9.7h | 73.7h | 420.5h | 1,997.1h |
| Interactive sessions | 5 | 17 | 77 | 1,251 |
| Worker sessions | 66 | 349 | 2,139 | 9,066 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 115 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.5 | 49,909 | 218.2M | 9.4M | 3,635.1M | $1,640.09 | $9,814.87 | $7,546.88 |
| gpt-5.6-sol | 10,069 | 40.8M | 2.2M | 753.5M | $688.29 | $2,034.67 | $1,527.40 |
| gpt-5.6-terra | 66 | 210K | 11K | 3.9M | $1.76 | $10.57 | $7.92 |
| gpt-5.4-mini | 156 | 783K | 18K | 7.9M | $0.49 | $14.84 | $17.90 |
| **Total** | **60,200** | **260.1M** | **11.6M** | **4,400.5M** | **$2,330.63** | **$11,874.95** | **$9,100.10** |

_4,672.3M total tokens processed. 94.2% cache hit rate._

_$20,975.04 total saved ($11,874.95 caching + $9,100.10 model routing vs all-Opus)._

_Model savings are modest because ~94.2% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | $26,082.33 | $101,035.04 | $0.00 |
| gpt-5.5 | 134,066 | 629.8M | 24.4M | 9,922.6M | $4,546.81 | $26,791.23 | $20,933.34 |
| claude-sonnet-4-6 | 71,313 | 148.9M | 22.0M | 6,176.0M | $3,143.34 | $16,675.28 | $10,519.66 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gpt-5.6-sol | 10,069 | 40.8M | 2.2M | 753.5M | $688.29 | $2,034.67 | $1,527.40 |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | $20.68 | $54.19 | $1,939.33 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| gpt-5.4-mini | 1,451 | 6.0M | 181K | 77.4M | $4.50 | $145.18 | $155.32 |
| big-pickle | 88 | 157K | 15K | 4.5M | $3.36 | $0.00 | $10.34 |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | $3.07 | $18.10 | $9.62 |
| claude-sonnet-4-5 | 16 | 67 | 4K | 1.7M | $2.00 | $4.65 | $2.34 |
| gpt-5.6-terra | 66 | 210K | 11K | 3.9M | $1.76 | $10.57 | $7.92 |
| **Total** | **307,745** | **1,159.9M** | **78.8M** | **25,426.3M** | **$35,757.74** | **$152,705.41** | **$35,231.18** |

_27,310.1M total tokens processed. 93.1% cache hit rate._

_$187,936.59 total saved ($152,705.41 caching + $35,231.18 model routing vs all-Opus)._

_Model savings are modest because ~93.1% of tokens are cache reads, where price differences between models are small._
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
- **[yc-remote-dev](https://github.com/MrRTi/yc-remote-dev)** -- Terraform config for remote dev environment at Yandex Cloud
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/alex-solovyev)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-07-17 11:59 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
