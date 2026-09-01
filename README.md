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
| Screen time (Linux) | 24h | 168h | 672h | ~8717h* |
| Interactive human attention | 6.9h | 39.8h | 140.6h | 171.0h |
| Interactive AI generation | 2.9h | 16.5h | 111.1h | 243.5h |
| Worker-classified human attention | 0.1h | 3.8h | 18.8h | 20.1h |
| Worker/headless AI generation | 2.5h | 13.1h | 71.5h | 1681.1h |
| Additive observed work | 12.5h | 72.4h | 337.9h | 2,110.7h |
| Interactive sessions | 6 | 9 | 57 | 73 |
| Worker sessions | 178 | 639 | 2,059 | 11,375 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 161 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.5 | 10,211 | 58.5M | 2.5M | 1,258.2M | $508.56 | $3,397.23 | $2,366.83 |
| gpt-5.6-sol | 4,925 | 20.6M | 975K | 395.6M | $352.75 | $1,068.34 | $781.11 |
| gpt-5.6-terra | 9,601 | 45.7M | 1.9M | 567.7M | $249.42 | $1,533.00 | $1,348.88 |
| gpt-5.6-luna | 1,930 | 16.9M | 281K | 103.0M | $6.34 | $278.25 | $344.13 |
| **Total** | **26,667** | **141.9M** | **5.7M** | **2,324.7M** | **$1,117.07** | **$6,276.82** | **$4,840.95** |

_2,472.5M total tokens processed. 94% cache hit rate._

_$11,117.77 total saved ($6,276.82 caching + $4,840.95 model routing vs all-Opus)._

_Model savings are modest because ~94% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | $26,082.33 | $101,035.04 | $0.00 |
| gpt-5.5 | 147,805 | 703.9M | 27.6M | 11,583.5M | $5,207.34 | $31,275.60 | $24,007.07 |
| claude-sonnet-4-6 | 71,313 | 148.9M | 22.0M | 6,176.0M | $3,143.34 | $16,675.28 | $10,519.66 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gpt-5.6-sol | 17,548 | 72.6M | 3.7M | 1,391.3M | $1,249.86 | $3,756.78 | $2,769.28 |
| gpt-5.6-terra | 9,668 | 45.9M | 1.9M | 571.6M | $250.85 | $1,543.57 | $1,356.90 |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | $20.68 | $54.19 | $1,939.33 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| gpt-5.6-luna | 1,936 | 17.0M | 282K | 103.0M | $6.36 | $278.25 | $345.08 |
| gpt-5.4-mini | 1,451 | 6.0M | 181K | 77.4M | $4.50 | $145.18 | $155.32 |
| big-pickle | 88 | 157K | 15K | 4.5M | $3.36 | $0.00 | $10.34 |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | $3.07 | $18.10 | $9.62 |
| claude-sonnet-4-5 | 16 | 67 | 4K | 1.7M | $2.00 | $4.65 | $2.34 |
| **Total** | **340,501** | **1,328.6M** | **85.8M** | **28,395.8M** | **$37,235.29** | **$160,723.15** | **$41,240.85** |

_30,455.4M total tokens processed. 93.2% cache hit rate._

_$201,964.00 total saved ($160,723.15 caching + $41,240.85 model routing vs all-Opus)._

_Model savings are modest because ~93.2% of tokens are cache reads, where price differences between models are small._
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
_Stats auto-updated 2026-09-01 19:10 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://commit-history.com/embed/alex-solovyev?theme=dark" />
    <img alt="alex-solovyev's commit history" src="https://commit-history.com/embed/alex-solovyev" />
  </picture>
</div>
