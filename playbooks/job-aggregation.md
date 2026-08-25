# Job aggregation workflow

1. Collect jobs from permitted sources with the source URL and retrieval time.
2. Normalize title, employer, location, remote status, salary, skills, employment type, and posted date.
3. Deduplicate by source job ID where available; otherwise use a cautious title-employer-location key.
4. Preserve the original description and source link for auditability.
5. Expire stale listings with an explicit status instead of silently deleting them.

