# Weekly SEO & Competitor Watch

A Claude Code Routine that produces a one-page market briefing every Monday morning.

## What this does

Mondays at 06:00 AM, Claude fetches each URL in [`inputs/watchlist.md`](./inputs/watchlist.md),
diffs the HTML against last week's [`snapshots/`](./snapshots/), and writes a one-page brief
under [`briefs/`](./briefs/) with a "so what" for a founder.

## Setup

1. Clone this repo.
2. Create the routine at [cloud.ai/code/routines](https://cloud.ai/code/routines).
3. Paste [`ROUTINE.md`](./ROUTINE.md).
4. Trigger: cron `0 6 * * 1` (Monday 06:00 UTC).
5. Save.

## Folder structure

- `briefs/YYYY-WW.md` — one file per ISO week
- `snapshots/YYYY-WW/{slug}.html` — raw HTML captured at run time (for next week's diff)
- `inputs/watchlist.md` — competitors + SERP keywords to track
- `inputs/config.yml` — change-detection thresholds

## Kill date: **2026-06-15** (8 weeks)
