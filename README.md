# HYROX Season 9: fastest 1000m Row splits

Top 3 row times per race and category (Men, Women, Men Pro, Women Pro) for HYROX Season 9 (2026/27), compiled from the public results lists.

**Live page:** https://davids-agentic-git.github.io/hyrox-season9-rowing/

- `index.html`: self-contained page (data embedded, no build step, no external requests).
- `data/`: the same data as an Excel workbook and CSV files.

## Sources and method

- Row split lists: [results.hyrox.com/season-9](https://results.hyrox.com/season-9/) (labelled "Season 26/27").
- Race calendar: event pages on [hyresult.com](https://www.hyresult.com/), an independent community site.
- The raw lists contain impossible splits from timing-mat misreads (for example 0:21 or 2:15 for 1000 m), so candidates are validated: a plausibility floor (3:00 men / 3:20 women), a consistency check against the athlete's own 1000m SkiErg time (reject below 75%), and removal of one faulty race day (Maastricht, Saturday, men). Everything removed is listed on the page's "Method & notes" tab and in `data/hyrox_season9_rowing_excluded_splits.csv`. The thresholds are a judgement call, not an official standard.
- Only athletes with a finish time are eligible (DNF / partial results are left out), so every top 3 consists of finishers.
- Six races were mid-weekend on the data date (14 Nov 2026), so their lists are interim.

## Disclaimer

An unofficial, independent project, not affiliated with, endorsed by or sponsored by HYROX or HYRESULT. Results are copied from public lists and may change or contain errors; check the official results before relying on any figure.
