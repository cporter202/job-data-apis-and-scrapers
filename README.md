<div align="center">

# 💼 Job Data APIs and Scrapers

**Job listings, hiring signals, salary data, employer research, and recruiting APIs.**

[![GitHub stars](https://img.shields.io/github/stars/cporter202/job-data-apis-and-scrapers?style=for-the-badge)](https://github.com/cporter202/job-data-apis-and-scrapers/stargazers)
[![Daily sync](https://img.shields.io/github/actions/workflow/status/cporter202/job-data-apis-and-scrapers/daily-sync.yml?label=daily%20sync&style=for-the-badge)](https://github.com/cporter202/job-data-apis-and-scrapers/actions/workflows/daily-sync.yml)
[![License](https://img.shields.io/github/license/cporter202/job-data-apis-and-scrapers?style=for-the-badge)](LICENSE)

</div>

## What this repo is

A focused directory for collecting job listings, company hiring signals, salary information, skills, employer profiles, and recruiting research data.

- [Browse Apify job APIs](catalog/README.md) — a large directory of ready-to-use actors.
- [Browse CoreClaw jobs workers](featured/coreclaw.md) — focused workers with API and MCP access.

## Start with a job to be done

| If you need to… | Start here |
|---|---|
| Aggregate jobs across multiple boards | [Apify catalog](catalog/README.md) |
| Pull Glassdoor, Indeed, or LinkedIn data | [CoreClaw workers](featured/coreclaw.md) |
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

This repository preserves referral parameters present in the upstream catalogs where available. See [SPONSORED_PARTNERS.md](SPONSORED_PARTNERS.md) for the disclosure. A referral link is not an endorsement of fit, quality, legality, or pricing.

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

