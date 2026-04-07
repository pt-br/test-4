# test-4

Early-stage project — tech stack and product scope TBD.

## Quick Start
No scripts defined yet. Update this section once a framework is chosen.

## Project Structure
```
tasks/        — Task board (tasks.md + archive.md)
lessons/      — Lessons learned from reviews and QA
.claude/      — Claude Code pipeline config and rules
```

## Key Conventions
- Tasks are tracked in `tasks/tasks.md`, grouped by date
- Lessons are written to `lessons/{topic}/` after non-trivial review findings
- All code work goes through the Claudio pipeline (PM → DEV → REVIEW → QA → MERGE)
- Branch naming: `{issue-number}-{short-slug}` (e.g. `12-add-login-page`)
- Worktrees are created at `../{project}-worktrees/` (sibling to the repo root)
