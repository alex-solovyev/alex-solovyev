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
| User AI session hours | 0.3h | 47.7h | 62.1h | 62.1h |
| AI worker hours | 5.9h | 30.4h | 47.2h | 47.2h |
| AI concurrency hours | 6.8h | 102.9h | 141.1h | 141.1h |
| Interactive sessions | 6 | 101 | 123 | 123 |
| Worker sessions | 43 | 141 | 202 | 202 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 25,336 | 143K | 9.6M | 3,376.2M | $9,942.55 | $45,579.02 | $0.00 |
| claude-sonnet-4-6 | 40,028 | 40K | 14.9M | 3,830.3M | $1,667.10 | $10,342.03 | $5,491.42 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gpt-5.5 | 1,688 | 10.6M | 373K | 120.0M | $63.99 | $324.08 | $294.53 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| claude-sonnet-4-5 | 1 | 3 | 1K | 0 | $0.26 | $0.00 | $0.06 |
| **Total** | **71,010** | **10.8M** | **26.6M** | **7,840.6M** | **$12,935.50** | **$62,181.64** | **$5,911.91** |

_8,206.2M total tokens processed. 95.5% cache hit rate._

_$68,093.56 total saved ($62,181.64 caching + $5,911.91 model routing vs all-Opus)._

_Model savings are modest because ~95.5% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 20,454 | 138K | 7.7M | 2,785.7M | $4,760.73 | $37,607.01 | $0.00 |
| claude-sonnet-4-6 | 31,866 | 32K | 11.6M | 2,990.1M | $1,072.24 | $8,073.52 | $4,289.03 |
| claude-opus-4-7 | 3,057 | 4K | 1.5M | 437.9M | $769.90 | $5,912.27 | $0.00 |
| gpt-5.5 | 1,422 | 9.3M | 296K | 102.2M | $63.24 | $276.09 | $253.03 |
| claude-haiku-4-5 | 851 | 1K | 182K | 72.3M | $6.51 | $52.11 | $115.77 |
| **Total** | **57,650** | **9.5M** | **21.3M** | **6,388.4M** | **$6,672.62** | **$51,921.00** | **$4,657.82** |

_6,719.9M total tokens processed. 95.1% cache hit rate._

_$56,578.82 total saved ($51,921.00 caching + $4,657.82 model routing vs all-Opus)._

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
_Stats auto-updated 2026-05-04 15:50 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
