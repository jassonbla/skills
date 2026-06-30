# Git Insight Report Template

```markdown
## Git Insight Summary

- Repository: `<repo>`
- Range: `<start>` → `<end>`
- Ref scope: `<branch/ref>`
- Author scope: `<all/me/name>`
- Total: `<N>` commits, `+<added> -<deleted>`

### Mission Overview

| Mission | Contributors | Commits | +Lines | -Lines |
|---|---:|---:|---:|---:|
| `<mission>` | `<names>` | `<N>` | `+<added>` | `-<deleted>` |

### `<Mission Name>`

- Contributors: `<names>`
- Commits: `<N>`
- Code changes: `+<added> -<deleted>`
- Work items:
  - `<short work item>` (`<hash>`)
  - `<short work item>` (`<hash>`)

### Highlight

`<one concise interpretation of the progress>`

### Caveats

- `<fetch/author/merge/stat caveat if any>`
```

## Bullet fallback

Use this shape for chat surfaces where Markdown tables render poorly:

```markdown
## Git Insight Summary

- Repository: `<repo>`
- Range: `<start>` → `<end>`
- Total: `<N>` commits, `+<added> -<deleted>`

Missions:
- `<Mission>` — `<N>` commits, `+<added> -<deleted>`, contributors: `<names>`
  - `<work item>` (`<hash>`)
  - `<work item>` (`<hash>`)
```
