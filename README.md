<div align="center">

<img src="./assets/hero.svg" alt="Job Data APIs and Scrapers — listings, hiring signals, salaries, and recruiting" width="100%" />

<br />

# 💼 Job Data APIs and Scrapers

**Job listings, hiring signals, salary data, employer research, and recruiting APIs.**

[![GitHub stars](https://img.shields.io/github/stars/cporter202/job-data-apis-and-scrapers?style=for-the-badge)](https://github.com/cporter202/job-data-apis-and-scrapers/stargazers)
[![Daily sync](https://img.shields.io/github/actions/workflow/status/cporter202/job-data-apis-and-scrapers/daily-sync.yml?label=daily%20sync&style=for-the-badge)](https://github.com/cporter202/job-data-apis-and-scrapers/actions/workflows/daily-sync.yml)
[![License](https://img.shields.io/github/license/cporter202/job-data-apis-and-scrapers?style=for-the-badge)](LICENSE)

<p>
  <a href="#featured-provider-paths"><strong>Featured Providers</strong></a> ·
  <a href="catalog/README.md"><strong>Browse 1,149 Apify APIs</strong></a> ·
  <a href="featured/coreclaw.md"><strong>Browse CoreClaw Workers</strong></a> ·
  <a href="#start-with-a-job-to-be-done"><strong>Start Building</strong></a>
</p>

</div>

## What this repo is

A focused directory for collecting job listings, company hiring signals, salary information, skills, employer profiles, and recruiting research data.

- [Browse Apify job APIs](catalog/README.md) — a large directory of ready-to-use actors.
- [Browse CoreClaw jobs workers](featured/coreclaw.md) — focused workers with API and MCP access.

## Featured provider paths

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🔎 Apify actor catalog</h3>
      <p>Broad coverage for job boards, employers, salary research, skills, and recruiting workflows.</p>
      <p><a href="https://apify.com/?fpr=p2hrc6"><strong>Explore Apify with my referral →</strong></a></p>
    </td>
    <td width="50%" valign="top">
      <h3>⚡ CoreClaw worker catalog</h3>
      <p>Focused workers for Glassdoor, Indeed, LinkedIn, multi-board jobs, and recruiting research.</p>
      <p><a href="https://www.coreclaw.com/store/categories?fpr=chris69"><strong>Explore CoreClaw with my referral →</strong></a></p>
    </td>
  </tr>
</table>

| Coverage snapshot | Current directory |
|---|---:|
| Apify job actors | **1,149** |
| CoreClaw jobs workers | **12** |
| Sync cadence | **Daily** |

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
