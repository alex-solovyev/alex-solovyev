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
| Screen time (Linux) | h | h | 0h | ~0h* |
| User AI session hours | 5.8h | 26.6h | 110.6h | 354.6h |
| AI worker hours | 12.3h | 59.4h | 189.1h | 1024.3h |
| AI concurrency hours | 24.0h | 115.0h | 377.6h | 1,764.7h |
| Interactive sessions | 8 | 41 | 94 | 856 |
| Worker sessions | 33 | 74 | 517 | 2,249 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 85 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.5 | 51,696 | 244.1M | 9.3M | 3,731.3M | $1,731.23 | $10,074.74 | $7,968.14 |
| gpt-5.4-mini | 508 | 2.6M | 44K | 16.9M | $1.34 | $31.81 | $51.22 |
| **Total** | **52,204** | **246.8M** | **9.3M** | **3,748.3M** | **$1,732.57** | **$10,106.55** | **$8,019.37** |

_4,004.6M total tokens processed. 93.6% cache hit rate._

_$18,125.91 total saved ($10,106.55 caching + $8,019.37 model routing vs all-Opus)._

_Model savings are modest because ~93.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | $26,082.33 | $101,035.04 | $0.00 |
| gpt-5.5 | 111,824 | 538.4M | 20.1M | 8,124.1M | $3,785.98 | $21,935.27 | $17,419.55 |
| claude-sonnet-4-6 | 71,305 | 148.9M | 22.0M | 6,176.0M | $3,143.34 | $16,675.28 | $10,519.66 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | $20.68 | $54.19 | $1,939.33 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| gpt-5.4-mini | 1,449 | 6.0M | 181K | 77.4M | $4.49 | $145.18 | $155.00 |
| big-pickle | 88 | 157K | 15K | 4.5M | $3.36 | $0.00 | $10.34 |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | $3.07 | $18.10 | $9.62 |
| claude-sonnet-4-5 | 16 | 67 | 4K | 1.7M | $2.00 | $4.65 | $2.34 |
| **Total** | **275,358** | **1,027.4M** | **72.2M** | **22,870.3M** | **$34,306.85** | **$145,804.21** | **$30,181.75** |

_24,615.1M total tokens processed. 92.9% cache hit rate._

_$175,985.96 total saved ($145,804.21 caching + $30,181.75 model routing vs all-Opus)._

_Model savings are modest because ~92.9% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[task-manager-python](https://github.com/alex-solovyev/task-manager-python)** -- No description
<!-- CONTRIBUTIONS-START -->
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/alex-solovyev)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-06-30 15:57 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
