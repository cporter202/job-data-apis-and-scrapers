<div align="center">

<img src="./assets/hero.svg" alt="Job Data APIs and Scrapers — listings, hiring signals, salaries, and recruiting" width="100%" />

<br />

# 💼 Job Data APIs and Scrapers


**Job listings, hiring signals, salary data, employer research, and recruiting APIs.**

[![GitHub stars](https://img.shields.io/github/stars/cporter202/job-data-apis-and-scrapers?style=for-the-badge)](https://github.com/cporter202/job-data-apis-and-scrapers/stargazers)
[![Daily sync](https://img.shields.io/github/actions/workflow/status/cporter202/job-data-apis-and-scrapers/daily-sync.yml?label=daily%20sync&style=for-the-badge)](https://github.com/cporter202/job-data-apis-and-scrapers/actions/workflows/daily-sync.yml)
[![License](https://img.shields.io/github/license/cporter202/job-data-apis-and-scrapers?style=for-the-badge)](LICENSE)

<p>
  <a href="catalog/README.md"><strong>Browse API Lists</strong></a> ·
  <a href="#start-with-a-job-to-be-done"><strong>Start Building</strong></a>
</p>

</div>

<!-- APIMESA-FEATURED-START -->
## ⭐ Featured: APIMesa

<p align="center">
  <a href="https://apimesa.com" target="_blank" rel="noopener">
    <img src=".github/assets/apimesa-promo-banner.png" alt="APIMesa — AI, Scraping & Data APIs. 150+ APIs, one API key, live playground at apimesa.com" width="100%">
  </a>
</p>

**[APIMesa](https://apimesa.com)** is a pay-per-call API marketplace with 150+ live APIs for AI, scraping, data, SEO, lead generation, media, and developer utilities — one API key, clear per-call credit pricing, and a live playground for every API.

<!-- APIMESA-FEATURED-END -->

## What this repo is

A focused directory for collecting job listings, company hiring signals, salary information, skills, employer profiles, and recruiting research data.

The API lists are the main content of this repository:

- [Browse Apify job APIs](catalog/README.md) — a large directory of ready-to-use actors.
- [Browse CoreClaw jobs APIs](catalog/coreclaw.md) — worker APIs with API and MCP access.

| API list | What you will find |
|---|---|
| [Apify API list](catalog/README.md) | The full jobs API directory, with one entry per actor and description. |
| [CoreClaw API list](catalog/coreclaw.md) | The full jobs API directory, with worker IDs and capabilities. |

| Coverage snapshot | Current directory |
|---|---:|
| Apify job actors | **1,149** |
| CoreClaw jobs workers | **12** |
| Sync cadence | **Daily** |

## Start with a job to be done

| If you need to… | Start here |
|---|---|
| Aggregate jobs across multiple boards | [Apify catalog](catalog/README.md) |
| Pull Glassdoor, Indeed, or LinkedIn data | [CoreClaw API list](catalog/coreclaw.md) |
| Normalize jobs and deduplicate listings | [Job aggregation playbook](playbooks/job-aggregation.md) |
| Turn hiring activity into a signal | [Hiring signals playbook](playbooks/hiring-signals.md) |
| Compare providers before building | [Provider selection checklist](playbooks/provider-selection.md) |

## Common build paths

- Multi-board job search and alerting
- Job deduplication and canonical schemas
- Skills, salary, and location analysis
- Employer and hiring-signal monitoring
- Recruiter and staffing dashboards
- Labor-market reports and datasets

## Provider notes

This repository preserves referral parameters present in the API lists where available. See [LINKS.md](LINKS.md) for a neutral referral-link note. A referral link is not an endorsement of fit, quality, legality, or pricing.

Respect job-board terms, robots rules, privacy obligations, employment-data regulations, rate limits, and restrictions on automated profiling. Do not use this directory as a substitute for legal or hiring advice.

## Maintenance

GitHub Actions checks the upstream Apify and CoreClaw category directories daily and updates only the catalog files when their content changes. Run the sync locally with:

```bash
node settings/sync_catalog.js
```

## Related directories

- [API Mega List](https://github.com/cporter202/API-mega-list)
- [Real Estate Data APIs](https://github.com/cporter202/real-estate-data-apis)
- [Ecommerce Intelligence APIs](https://github.com/cporter202/ecommerce-intelligence-apis)

<!-- AIWITHCHRIS-BANNER-START -->
<p align="center">
  <a href="https://aiwithchris.com" target="_blank" rel="noopener">
    <img src=".github/assets/ai-toolkit-banner.png" alt="Hey, I'm Chris — Work Smarter, Create Faster, Earn More With AI. Join my AI Playbook at aiwithchris.com, $10/month" width="100%">
  </a>
</p>
<p align="center">
  <a href="https://aiwithchris.com"><strong>🚀 Join my AI Playbook — aiwithchris.com</strong></a><br>
  $10/month · 3,600+ prompts · agent workflows · repo breakdowns · money ideas
</p>
<!-- AIWITHCHRIS-BANNER-END -->

