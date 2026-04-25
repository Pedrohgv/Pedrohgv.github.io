# Application Tracker

Use this file as the single source of truth for custom resume variants and application context.

## Status Legend

- `draft` - Variant created, not submitted
- `applied` - Submitted
- `screening` - Recruiter/hiring-manager screen
- `interview` - Interview rounds in progress
- `offer` - Offer received
- `rejected` - Closed by company
- `withdrawn` - Closed by candidate

## Applications

| Date | Company | Role | Job URL | Resume Variant | Base Version | Match Score | Status | Last Update | Notes |
|---|---|---|---|---|---|---:|---|---|---|
| 2026-04-25 | Telepatia | Senior AI Engineer | N/A (description provided directly) | `CV/versions/Venturott_AIEngineer_Telepatia_2026-04.pdf` | `CV/resume.tex` | 72 | draft | 2026-04-25 | Strong fit on agents/pipelines/FastAPI/MLOps; gaps to address in interviews: explicit million-user scale and direct RAG/knowledge-graph depth. |
| YYYY-MM-DD |  |  |  |  | `CV/resume.tex` | 0 | draft | YYYY-MM-DD | |

## Variant Naming Convention

- Recommended pattern: `LastName_Role_Company_YYYY-MM`
- Keep names stable between this tracker and your tailored resume notes.

## Update Rules

- Add one row per application.
- Update `Status`, `Last Update`, and `Notes` after each milestone.
- Keep `Match Score` from `job-description-analyzer` for later review.
- Record link to interview prep notes in `Notes` when available.
