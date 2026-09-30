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
| Screen time (Linux) | 24h | 167.9h | 671.9h | ~8722h* |
| Interactive human attention | 11.4h | 43.5h | 142.1h | 321.7h |
| Interactive AI generation | 6.7h | 71.9h | 308.9h | 557.6h |
| Worker-classified human attention | 4.3h | 8.6h | 18.1h | 40.4h |
| Worker/headless AI generation | 8.9h | 28.1h | 105.0h | 1792.3h |
| Additive observed work | 27.7h | 147.4h | 568.9h | 2,701.8h |
| Interactive sessions | 26 | 47 | 69 | 139 |
| Worker sessions | 120 | 354 | 1,637 | 13,027 |

_Screen time from linux-wtmp:login-session-proxy; collection status: ok. *365-day estimate uses observed calendar coverage._

_Periods are completed local calendar days ending at midnight; today is excluded._

_Human attention is unioned wall-clock time, so overlapping sessions are not double-counted. AI generation is additive machine work across sessions; it is not wall-clock concurrency._

_AI session 365-day totals cover 190 days of local assistant session history (not extrapolated)._

## AI Model Usage (last 30 days)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.6-terra | 8,562 | 39.9M | 2.1M | 496.7M | 0 | 92.6% | 532 | 54.0h |
| gpt-5.6-sol | 7,531 | 25.1M | 1.0M | 635.1M | 0 | 96.2% | 338 | 35.7h |
| gpt-5.5 | 5,557 | 20.9M | 1.1M | 760.8M | 0 | 97.3% | 16 | 221.1h |
| gpt-6-sol | 5,076 | 17.8M | 654K | 337.9M | 0 | 95.0% | 277 | 27.0h |
| gpt-6-astra | 4,262 | 20.3M | 718K | 751.4M | 0 | 97.4% | 49 | 64.4h |
| claude-opus-5-5 | 1,584 | 3K | 563K | 211.8M | 7.4M | 96.6% | 33 | 7.3h |
| claude-sonnet-5-5 | 1,250 | 2K | 423K | 115.2M | 10.2M | 91.8% | 42 | 21.9h |
| gpt-5.6-luna | 586 | 9.7M | 31K | 4.3M | 0 | 30.8% | 507 | 0.9h |
| claude-haiku-4-5 | 158 | 839 | 42K | 14.6M | 1.7M | 89.4% | 1 | 1.8h |
| claude-sonnet-4-6 | 50 | 52 | 8K | 4.0M | 125K | 97.0% | 1 | 0.1h |
| gpt-6-luna | 23 | 374K | 5K | 0 | 0 | 0.0% | 11 | 0.0h |
| claude-sonnet-4-5 | 1 | 3 | 9 | 0 | 35K | 0.0% | 1 | 0.0h |
| **Total** | **34,640** | **134.3M** | **6.8M** | **3,332.2M** | **19.6M** | **95.6%** | **1,789** | **434.2h** |

_3,493.1M total tokens processed. 95.6% cache hit rate._

## AI Model Usage (all time)

| Model | Requests | Input | Output | Cache read | Cache write | Cache Hit-Rate % | Session Count | Session Hours |
| --- | ---: | ---: | ---: | ---: | ---: | ---: | ---: | ---: |
| gpt-5.5 | 153,150 | 723.4M | 28.7M | 12,312.2M | 0 | 94.5% | 4,722 | 1,254.7h |
| claude-opus-4-6 | 81,888 | 259.0M | 26.4M | 7,484.0M | 479.1M | 91.0% | 2,397 | 384.7h |
| claude-sonnet-4-6 | 71,363 | 148.9M | 22.0M | 6,180.1M | 137.0M | 95.6% | 1,286 | 276.7h |
| gpt-5.6-sol | 25,047 | 97.6M | 4.8M | 2,025.2M | 0 | 95.4% | 1,075 | 137.5h |
| gpt-5.6-terra | 17,326 | 82.0M | 3.9M | 1,017.7M | 0 | 92.5% | 1,258 | 99.0h |
| gpt-6-sol | 5,076 | 17.8M | 654K | 337.9M | 0 | 95.0% | 277 | 27.0h |
| gemini-3-flash | 4,744 | 74.7M | 1.6M | 481.6M | 0 | 86.6% | 96 | 19.1h |
| gpt-6-astra | 4,262 | 20.3M | 718K | 751.4M | 0 | 97.4% | 49 | 64.4h |
| claude-opus-4-7 | 3,029 | 4K | 1.4M | 435.5M | 25.9M | 94.4% | 24 | 16.5h |
| gpt-5.6-luna | 2,488 | 26.6M | 312K | 107.1M | 0 | 80.1% | 1,526 | 7.4h |
| claude-opus-5-5 | 1,584 | 3K | 563K | 211.8M | 7.4M | 96.6% | 33 | 7.3h |
| gpt-5.4-mini | 1,451 | 6.0M | 181K | 77.4M | 0 | 92.7% | 276 | 5.3h |
| claude-sonnet-5-5 | 1,250 | 2K | 423K | 115.2M | 10.2M | 91.8% | 42 | 21.9h |
| claude-haiku-4-5 | 1,086 | 1K | 247K | 93.0M | 3.9M | 95.9% | 21 | 5.0h |
| big-pickle | 88 | 157K | 15K | 4.5M | 344K | 90.1% | 4 | 0.1h |
| claude-sonnet-4 | 87 | 158 | 26K | 6.7M | 177K | 97.4% | 2 | 0.2h |
| gemini-3.1-pro | 27 | 0 | 0 | 0 | 0 | 0.0% | 27 | 0.0h |
| gpt-6-luna | 23 | 374K | 5K | 0 | 0 | 0.0% | 11 | 0.0h |
| claude-sonnet-4-5 | 17 | 70 | 4K | 1.7M | 413K | 80.6% | 3 | 0.0h |
| **Total** | **373,986** | **1,457.3M** | **92.4M** | **31,643.6M** | **664.7M** | **93.7%** | **13,086** | **2,326.8h** |

_33,858.1M total tokens processed. 93.7% cache hit rate._
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
_Stats auto-updated 2026-09-30 20:32 UTC by [aidevops](https://aidevops.sh) pulse._
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
