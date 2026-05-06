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
| User AI session hours | 10.3h | 47.7h | 88.9h | 88.9h |
| AI worker hours | 4.6h | 30.1h | 56.2h | 56.4h |
| AI concurrency hours | 19.2h | 95.1h | 185.2h | 185.4h |
| Interactive sessions | 2 | 29 | 122 | 122 |
| Worker sessions | 28 | 149 | 247 | 248 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours measured from AI message timestamps (reading, thinking, typing between responses)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 20,887 | 139K | 8.3M | 3,041.6M | $9,161.72 | $41,062.51 | $0.00 |
| claude-sonnet-4-6 | 37,343 | 38K | 14.3M | 3,630.3M | $1,584.56 | $9,801.93 | $5,216.44 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gpt-5.5 | 5,194 | 31.0M | 1.2M | 528.8M | $233.30 | $1,427.95 | $1,082.53 |
| claude-haiku-4-5 | 821 | 1K | 182K | 72.3M | $8.60 | $52.11 | $115.76 |
| claude-sonnet-4-5 | 1 | 3 | 1K | 0 | $0.26 | $0.00 | $0.06 |
| **Total** | **67,275** | **31.2M** | **25.5M** | **7,708.8M** | **$12,240.74** | **$58,224.55** | **$6,414.79** |

_8,080.4M total tokens processed. 95.4% cache hit rate._

_$64,639.34 total saved ($58,224.55 caching + $6,414.79 model routing vs all-Opus)._

_Model savings are modest because ~95.4% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 20,463 | 138K | 7.7M | 2,785.7M | $4,760.73 | $37,607.01 | $0.00 |
| claude-sonnet-4-6 | 31,869 | 32K | 11.6M | 2,990.1M | $1,072.24 | $8,073.52 | $4,289.03 |
| claude-opus-4-7 | 3,057 | 4K | 1.5M | 437.9M | $769.90 | $5,912.27 | $0.00 |
| gpt-5.5 | 4,892 | 29.5M | 1.1M | 505.8M | $257.77 | $1,365.72 | $1,031.11 |
| claude-haiku-4-5 | 851 | 1K | 182K | 72.3M | $6.51 | $52.11 | $115.77 |
| **Total** | **61,132** | **29.7M** | **22.2M** | **6,792.0M** | **$6,867.15** | **$53,010.63** | **$5,435.90** |

_7,144.5M total tokens processed. 95.1% cache hit rate._

_$58,446.53 total saved ($53,010.63 caching + $5,435.90 model routing vs all-Opus)._

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
_Stats auto-updated 2026-05-06 23:00 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
