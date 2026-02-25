# NFL Combine Comparables Engine — 2026 Draft

Find historically similar players for any 2026 NFL Draft prospect based on combine measurements.

**Live app:** https://claudevonpierre-beep.github.io/combine-comps/

## Features
- 8,636 historical players (2000–2025) as comparison database
- DJ Top 50 v2.0 prospects pre-loaded
- Weighted Euclidean similarity across 7 metrics (40, ht, wt, vertical, broad jump, cone, shuttle)
- Position-group normalized (z-scores) — compares fairly within position
- Handles partial data (missing metrics excluded from distance calc)

## Update combine results
Edit `prospects_2026.json` and push — app reflects immediately.
