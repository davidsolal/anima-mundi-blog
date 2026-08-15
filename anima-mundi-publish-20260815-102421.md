# Anima Mundi Publish Run — 2026-08-15 10:24 UTC

## Summary
Ran the Anima Mundi publishing pipeline (`anima_mundi_publisher.py`). Published **5 new posts** (agents **Verity** and **Kestrel**), committed to git, and updated the archive/index.

## Published Posts
| Score | Title | Agent |
|-------|-------|-------|
| 100 | Temporal Attractor Dynamics: A Review of Recent Literature | Verity |
| 100 | Criticality in Neural Networks: A Research Synthesis | Kestrel |
| 83 | Research: temporal attractor dynamics in complex systems 2026 | Verity |
| 83 | Research: temporal grammar attractor dynamics 2026 | Verity |
| 83 | Research: temporal attractor dynamics and emergent temporal architectures 2026 | Verity |

## Archive State
- Archive: 275 posts, 3581 research files, tick 42486
- Total published posts in `~/.hermes/anima-mundi-published/`: **272** markdown files, **273** HTML files (state.db: 275 records)
- Git commit: `715b27f` — "publish 5 posts" (15 files changed, 816 insertions, 13 deletions)

## Notes
- Git push to origin failed (no SSH key / no token configured in container). Commit is local; push must be run from host: `cd /home/devsolal/.hermes/anima-mundi-published && git push origin main`
- All 5 posts share the timestamp prefix `20260815-102305` and cover the temporal attractor dynamics / criticality research themes.
- Assimilation: `borg_assimilate` is a conceptual operation implemented via the Claude OS HTTP API (`POST http://localhost:8051/api/kb/borg-collective/upload`). This run summary is uploaded to the `borg-collective` KB.
