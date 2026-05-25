# Project Architecture

## Philosophy

This project unifies three layers into one clinical~educational repository:

1. **Reference** — dense, clinician-facing knowledge (`clinical-reference/`)
2. **Curriculum** — structured learning with weekly progression (`curriculum/`)
3. **Interactive** — self-assessment via browser quiz (`assets/quiz-game/`)

All content exists as Markdown (except the quiz, which is a single self-contained HTML file). This enables version control, diff-based reviewing, and contribution workflows.

## Content Conventions

### Clinical Reference (`clinical-reference/`)

- **SKILL.md** is the master table of 22 metabolic pathways
- Table columns: Enzyme | Gene | rs Number | cDNA Change | Protein Change | Cofactor | Clinical Significance
- Cofactors are mandatory — every enzyme entry must list vitamins/minerals required
- CPIC tiers annotate clinical actionability

### Curriculum (`curriculum/`)

- **12-WEEK-LEARNING-PLAN.md** serves as the syllabus and reading guide
- Each week has a matching worksheet in `worksheets/` and quiz in `quizzes/`
- Worksheets follow the clinical audit pattern: Assess → Analyze → Protocol → Monitor
- Quizzes use scenario-based multiple choice, 4 options per question

### Quiz Game (`assets/quiz-game/`)

- Single HTML file, no build step required
- Loads `gameData.json` at runtime; falls back to embedded JSON if fetch fails
- Category chooser on first screen
- Score breakdown by category shown at end
- Responsive, no external CSS framework

## Branching and Releases

- `main` — always stable, passes CI
- Tags follow `vYYYY.MM` (e.g., `v2026.05`)
- Curriculum updates tracked in `clinical-reference/CHANGELOG.md`

## Data Sources

- CPIC guidelines (cpicpgx.org)
- PharmGKB (pharmgkb.org)
- ClinVar (ncbi.nlm.nih.gov/clinvar)
- Peer-reviewed pharmacogenomic literature
