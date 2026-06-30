# Example Git Insight Report

## Git Insight Summary

- Repository: `example-app`
- Range: `2026-06-24` → `2026-06-30`
- Ref scope: `origin/main`
- Author scope: `all`
- Total: `12` commits, `+1,420 -380`

### Mission Overview

| Mission | Contributors | Commits | +Lines | -Lines |
|---|---:|---:|---:|---:|
| Authentication hardening | `@alice` `@bob` | 4 | +620 | -140 |
| Dashboard usability | `@chris` | 3 | +480 | -90 |
| Test coverage and cleanup | `@alice` | 5 | +320 | -150 |

### Authentication hardening

- Contributors: `@alice`, `@bob`
- Commits: `4`
- Code changes: `+620 -140`
- Work items:
  - Add refresh-token rotation (`abc1234`)
  - Tighten session expiry checks (`def5678`)
  - Cover invalid token paths (`901abcd`)

### Highlight

Most activity focused on reducing authentication risk while keeping dashboard improvements moving in parallel.

### Caveats

- Mission grouping is inferred from commit subjects and touched paths.
