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
| User AI session hours | 3.7h | 26.3h | 110.5h | 352.2h |
| AI worker hours | 12.8h | 56.6h | 181.5h | 1014.9h |
| AI concurrency hours | 21.6h | 112.8h | 369.7h | 1,751.9h |
| Interactive sessions | 7 | 38 | 93 | 853 |
| Worker sessions | 14 | 56 | 505 | 2,222 |

_Screen time from systemd-logind session events, snapshotted daily. *365-day extrapolated (accumulating real data)._

_User AI session hours are attended interactive time measured from gaps between AI responses and the next user message; AI concurrency hours include attended time, AI generation, and background workers._

_AI session 365-day totals cover 85 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.5 | 50,421 | 238.6M | 9.0M | 3,649.1M | $1,691.77 | $9,852.75 | $7,787.81 |
| gpt-5.4-mini | 508 | 2.6M | 44K | 16.9M | $1.34 | $31.81 | $51.22 |
| **Total** | **50,929** | **241.3M** | **9.1M** | **3,666.1M** | **$1,693.11** | **$9,884.56** | **$7,839.04** |

_3,916.6M total tokens processed. 93.6% cache hit rate._

_$17,723.59 total saved ($9,884.56 caching + $7,839.04 model routing vs all-Opus)._

_Model savings are modest because ~93.6% of tokens are cache reads, where price differences between models are small._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | API Cost | Cache savings | Model savings |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | $26,082.33 | $101,035.04 | $0.00 |
| gpt-5.5 | 109,895 | 530.8M | 19.7M | 8,013.4M | $3,732.11 | $21,636.34 | $17,173.87 |
| claude-sonnet-4-6 | 71,305 | 148.9M | 22.0M | 6,176.0M | $3,143.34 | $16,675.28 | $10,519.66 |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | $1,252.30 | $5,880.05 | $0.00 |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | $20.68 | $54.19 | $1,939.33 |
| claude-haiku-4-5 | 928 | 1K | 204K | 78.4M | $9.30 | $56.46 | $125.90 |
| gpt-5.4-mini | 1,449 | 6.0M | 181K | 77.4M | $4.49 | $145.18 | $155.00 |
| big-pickle | 88 | 157K | 15K | 4.5M | $3.36 | $0.00 | $10.34 |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | $3.07 | $18.10 | $9.62 |
| claude-sonnet-4-5 | 16 | 67 | 4K | 1.7M | $2.00 | $4.65 | $2.34 |
| **Total** | **273,429** | **1,019.8M** | **71.9M** | **22,759.6M** | **$34,252.98** | **$145,505.28** | **$29,936.07** |

_24,496.4M total tokens processed. 92.9% cache hit rate._

_$175,441.35 total saved ($145,505.28 caching + $29,936.07 model routing vs all-Opus)._

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
_Stats auto-updated 2026-06-30 01:57 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->
