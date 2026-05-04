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
| User AI session hours | 1.7h | 47.6h | 61.9h | 61.9h |
| AI worker hours | 1.4h | 31.2h | 42.3h | 42.3h |
| AI concurrency hours | 5.3h | 104.1h | 135.8h | 135.8h |
| Interactive sessions | 9 | 106 | 123 | 123 |
| Worker sessions | 4 | 120 | 163 | 163 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 25,920 | 144K | 9.7M | 3,417.7M | $10,091.86 | $46,140.07 | $0.00 |
| claude-sonnet-4-6 | 44,290 | 45K | 15.7M | 4,184.0M | $1,805.59 | $11,296.99 | $5,969.38 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gpt-5.5 | 331 | 1.9M | 56K | 32.5M | $14.20 | $87.87 | $65.74 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| claude-sonnet-4-5 | 1 | 3 | 1K | 0 | $0.26 | $0.00 | $0.06 |
| **Total** | **74,499** | **2.1M** | **27.3M** | **8,148.3M** | **$13,173.51** | **$63,461.44** | **$6,161.08** |

_8,515.1M total tokens processed. 95.7% cache hit rate._

_$69,622.52 total saved ($63,461.44 caching + $6,161.08 model routing vs all-Opus)._

_Model savings are modest because ~95.7% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 20,448 | 138K | 7.7M | 2,785.7M | $4,760.73 | $37,607.01 | $0.00 |
| claude-sonnet-4-6 | 31,864 | 32K | 11.6M | 2,990.1M | $1,072.24 | $8,073.52 | $4,289.03 |
| claude-opus-4-7 | 3,057 | 4K | 1.5M | 437.9M | $769.90 | $5,912.27 | $0.00 |
| gpt-5.5 | 332 | 1.9M | 56K | 32.6M | $16.35 | $88.08 | $65.44 |
| claude-haiku-4-5 | 851 | 1K | 182K | 72.3M | $6.51 | $52.11 | $115.77 |
| **Total** | **56,552** | **2.0M** | **21.1M** | **6,318.8M** | **$6,625.73** | **$51,732.99** | **$4,470.24** |

_6,642.5M total tokens processed. 95.1% cache hit rate._

_$56,203.23 total saved ($51,732.99 caching + $4,470.24 model routing vs all-Opus)._

_Model savings are modest because ~95.1% of tokens are cache reads, where price differences between models are small._
<!-- STATS-END -->

## Projects

- **[task-manager-python](https://github.com/alex-solovyev/task-manager-python)** -- No description
<!-- CONTRIBUTIONS-START -->
<!-- CONTRIBUTIONS-END -->

## Connect

[![GitHub](https://img.shields.io/badge/-Follow-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/alex-solovyev)
---

<!-- UPDATED-START -->
_Stats auto-updated 2026-05-04 02:48 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
