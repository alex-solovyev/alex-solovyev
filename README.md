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
| User AI session hours | 1.3h | 48.1h | 63.2h | 63.2h |
| AI worker hours | 6.0h | 30.8h | 47.9h | 47.9h |
| AI concurrency hours | 7.9h | 103.9h | 143.2h | 143.2h |
| Interactive sessions | 6 | 102 | 124 | 124 |
| Worker sessions | 46 | 146 | 208 | 208 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 25,336 | 143K | 9.6M | 3,376.2M | $9,942.55 | $45,579.02 | $0.00 |
| claude-sonnet-4-6 | 39,780 | 40K | 14.8M | 3,815.7M | $1,661.25 | $10,302.44 | $5,471.15 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gpt-5.5 | 2,009 | 12.4M | 452K | 140.2M | $75.01 | $378.58 | $345.01 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| claude-sonnet-4-5 | 1 | 3 | 1K | 0 | $0.26 | $0.00 | $0.06 |
| **Total** | **71,083** | **12.6M** | **26.6M** | **7,846.1M** | **$12,940.67** | **$62,196.56** | **$5,942.12** |

_8,213.4M total tokens processed. 95.5% cache hit rate._

_$68,138.68 total saved ($62,196.56 caching + $5,942.12 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 20,455 | 138K | 7.7M | 2,785.7M | $4,760.73 | $37,607.01 | $0.00 |
| claude-sonnet-4-6 | 31,867 | 32K | 11.6M | 2,990.1M | $1,072.24 | $8,073.52 | $4,289.03 |
| claude-opus-4-7 | 3,057 | 4K | 1.5M | 437.9M | $769.90 | $5,912.27 | $0.00 |
| gpt-5.5 | 1,614 | 10.6M | 352K | 113.6M | $71.45 | $306.88 | $285.86 |
| claude-haiku-4-5 | 851 | 1K | 182K | 72.3M | $6.51 | $52.11 | $115.77 |
| **Total** | **57,844** | **10.8M** | **21.4M** | **6,399.8M** | **$6,680.83** | **$51,951.79** | **$4,690.65** |

_6,732.7M total tokens processed. 95.1% cache hit rate._

_$56,642.44 total saved ($51,951.79 caching + $4,690.65 model routing vs all-Opus)._

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
_Stats auto-updated 2026-05-04 16:50 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
