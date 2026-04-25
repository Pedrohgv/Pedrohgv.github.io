# AI Resume Workflow

This workflow keeps `CV/resume.tex` updated continuously using OpenCode skills installed in `.opencode/skills`.

## Source and Attribution

- Skills source: `https://github.com/Paramchoudhary/ResumeSkills`
- Author: Param Choudhary (`https://github.com/Paramchoudhary`)

## Primary Workflow

1. Analyze target role with `job-description-analyzer`.
2. Tailor content with `resume-tailor` and `tech-resume-optimizer`.
3. Strengthen bullets with `resume-bullet-writer`.
4. Add measurable impact with `resume-quantifier`.
5. Validate ATS alignment with `resume-ats-optimizer`.
6. Save versioning metadata with `resume-version-manager`.
7. Reflect approved changes in `CV/resume.tex`.

## Continuous Update Cadence

- Weekly quick pass (10-20 minutes):
  - Add new achievements, project milestones, and technologies.
  - Capture rough metrics while context is fresh.
- Monthly optimization pass (45-90 minutes):
  - Run all core skills in sequence.
  - Refresh summary, skills order, and top bullets for current job market.
- Per-application tailoring pass (30-60 minutes):
  - Analyze JD, tailor keywords, and generate role-specific version notes.

## Repository Operating Model

- Source of truth: `CV/resume.tex`.
- Optional generated artifact: `CV/resume.pdf`.
- Skills location for auto-discovery: `.opencode/skills/`.
- Skills upstream pinning: `.opencode/skills/SOURCE_LOCK.md`.
- Execution notes and templates: `CV/AI_RESUME_TEMPLATES.md`.

## Quality Guardrails

- Do not invent claims, technologies, or metrics.
- Keep quantification conservative and defensible.
- Preserve LaTeX template commands and syntax.
- Favor short, impact-first bullet points.
- Keep ATS-friendly wording while preserving readability.

## Lower-Priority Skills (For future adoption)

- `linkedin-profile-optimizer`, `cover-letter-generator`, `interview-prep-generator`, `salary-negotiation-prep`
- `resume-section-builder`, `resume-formatter`, `career-changer-translator`
- `executive-resume-writer`, `academic-cv-builder`, `offer-comparison-analyzer`, `reference-list-builder`, `creative-portfolio-resume`

Use these when the workflow expands beyond resume maintenance into job-search lifecycle support.
