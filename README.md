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
| Screen time (Linux) | 24h | 167.8h | 671.8h | ~8724h* |
| Interactive human attention | 6.6h | 24.1h | 109.3h | 367.6h |
| Interactive AI generation | 0.9h | 187.5h | 423.6h | 835.4h |
| Worker-classified human attention | 8.3h | 24.5h | 44.7h | 75.2h |
| Worker/headless AI generation | 12.3h | 71.5h | 204.3h | 1954.9h |
| Additive observed work | 23.8h | 302.5h | 771.6h | 3,217.3h |
| Interactive sessions | 9 | 31 | 101 | 190 |
| Worker sessions | 169 | 592 | 1,656 | 14,105 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 206 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| claude-sonnet-5-5 | 30,823 | 65K | 11.2M | 3,854.3M | 248.1M | 93.9% | 988 | 201.8h |
| claude-opus-5-5 | 13,589 | 28K | 4.5M | 1,852.0M | 60.4M | 96.8% | 248 | 107.4h |
| gpt-6-sol | 5,076 | 17.8M | 654K | 337.9M | 0 | 95.0% | 277 | 27.0h |
| gpt-5.6-sol | 4,200 | 14.9M | 642K | 439.2M | 0 | 96.7% | 144 | 22.8h |
| gpt-5.5 | 3,696 | 10.9M | 767K | 514.9M | 0 | 97.9% | 8 | 106.3h |
| gpt-6-astra | 1,589 | 6.9M | 233K | 318.9M | 0 | 97.9% | 6 | 44.5h |
| gpt-5.6-terra | 1,377 | 7.7M | 258K | 96.6M | 0 | 92.6% | 100 | 6.8h |
| claude-haiku-4-5 | 158 | 839 | 42K | 14.6M | 1.7M | 89.4% | 1 | 1.8h |
| gpt-5.6-luna | 142 | 2.2M | 6K | 2.0M | 0 | 47.0% | 100 | 0.2h |
| claude-sonnet-4-6 | 132 | 142 | 25K | 9.5M | 351K | 96.5% | 5 | 0.4h |
| gpt-6-luna | 27 | 374K | 5K | 0 | 0 | 0.0% | 13 | 0.0h |
| gpt-6.1-sol | 7 | 0 | 0 | 0 | 0 | 0.0% | 7 | 0.0h |
| claude-haiku-5-5 | 1 | 4 | 4 | 0 | 22K | 0.0% | 1 | 0.0h |
| claude-sonnet-4-5 | 1 | 3 | 9 | 0 | 35K | 0.0% | 1 | 0.0h |
| **Total** | **60,818** | **61.1M** | **18.4M** | **7,440.4M** | **310.7M** | **95.2%** | **1,830** | **519.0h** |

_7,830.8M total tokens processed. 95.2% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.5 | 153,150 | 723.4M | 28.7M | 12,312.2M | 0 | 94.5% | 4,722 | 1,254.7h |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | 479.1M | 91.0% | 2,397 | 384.7h |
| claude-sonnet-4-6 | 71,445 | 148.9M | 22.0M | 6,185.6M | 137.2M | 95.6% | 1,290 | 277.0h |
| claude-sonnet-5-5 | 30,823 | 65K | 11.2M | 3,854.3M | 248.1M | 93.9% | 988 | 201.8h |
| gpt-5.6-sol | 25,047 | 97.6M | 4.8M | 2,025.2M | 0 | 95.4% | 1,075 | 137.5h |
| gpt-5.6-terra | 17,326 | 82.0M | 3.9M | 1,017.7M | 0 | 92.5% | 1,258 | 99.0h |
| claude-opus-5-5 | 13,589 | 28K | 4.5M | 1,852.0M | 60.4M | 96.8% | 248 | 107.4h |
| gpt-6-sol | 5,076 | 17.8M | 654K | 337.9M | 0 | 95.0% | 277 | 27.0h |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | 0 | 86.6% | 96 | 19.1h |
| gpt-6-astra | 4,262 | 20.3M | 718K | 751.4M | 0 | 97.4% | 49 | 64.4h |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | 25.9M | 94.4% | 24 | 16.5h |
| gpt-5.6-luna | 2,488 | 26.6M | 312K | 107.1M | 0 | 80.1% | 1,526 | 7.4h |
| gpt-5.4-mini | 1,451 | 6.0M | 181K | 77.4M | 0 | 92.7% | 276 | 5.3h |
| claude-haiku-4-5 | 1,086 | 1K | 247K | 93.0M | 3.9M | 95.9% | 21 | 5.0h |
| big-pickle | 88 | 157K | 15K | 4.5M | 344K | 90.1% | 4 | 0.1h |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | 177K | 97.4% | 2 | 0.2h |
| gemini-3.1-pro | 27 | 0 | 0 | 0 | 0 | 0.0% | 27 | 0.0h |
| gpt-6-luna | 27 | 374K | 5K | 0 | 0 | 0.0% | 13 | 0.0h |
| claude-sonnet-4-5 | 17 | 70 | 4K | 1.7M | 413K | 80.6% | 3 | 0.0h |
| gpt-6.1-sol | 7 | 0 | 0 | 0 | 0 | 0.0% | 7 | 0.0h |
| claude-haiku-5-5 | 1 | 4 | 4 | 0 | 22K | 0.0% | 1 | 0.0h |
| **Total** | **415,658** | **1,457.4M** | **107.2M** | **37,028.5M** | **955.8M** | **93.9%** | **14,208** | **2,607.1h** |

_39,549.1M total tokens processed. 93.9% cache hit rate._
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
_Stats auto-updated 2026-10-16 13:03 UTC by [aidevops](https://aidevops.sh) pulse._
<!-- UPDATED-END -->

<!-- TOTAL-CONTRIBUTIONS-START -->
<div align="center">
  <a href="https://commit-history.com/alex-solovyev?metric=total" target="_blank" rel="noopener noreferrer">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="assets/contributions/total-dark.svg" />
      <img alt="alex-solovyev's cumulative total GitHub contributions" src="assets/contributions/total-light.svg" width="960" />
    </picture>
  </a>
</div>

[Verify on commit-history.com](https://commit-history.com/alex-solovyev?metric=total) · [Chart data](assets/contributions/total.json)

Includes commits, issues, pull requests, reviews, repositories, and restricted contributions. Refreshed daily through the prior UTC day; commit-history.com may use a different refresh cutoff. GitHub controls link navigation—Ctrl/Cmd-click opens verification in a new tab.
<!-- TOTAL-CONTRIBUTIONS-END -->
