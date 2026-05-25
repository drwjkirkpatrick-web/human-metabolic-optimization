# Contributing

Thank you for considering improving this clinical reference.

## Areas of Contribution

- **New SNPs** — add clinically significant rs numbers with CPIC/PharmGKB citations
- **Pathway Coverage** — expand to 25+ pathways (e.g., thyroid hormone conversion, mast cell mediators)
- **Population Data** — add ancestry-specific allele frequencies
- **Cofactor Updates** — refine mg/μg dosing ranges based on genotype
- **Quiz Questions** — add clinical scenarios with answer explanations
- **Translation** — curriculum localization for non-English learners
- **Web UI** — expand quiz game with streaming or e-learning integrations

## Workflow

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/xyz`)
3. Make changes (Markdown preferred)
4. Run `markdownlint` locally
5. Test the quiz by opening `assets/quiz-game/index.html` in a browser
6. Commit with descriptive messages
7. Open a pull request

## Clinical Accuracy Standards

- All SNP entries must include at minimum: rs number, functional effect, clinical consequence
- Dosing ranges require peer-reviewed citations (use YAML metadata in SKILL.md updates)
- CPIC guideline updates supersede all previous dosing advice
- No proprietary/commercial supplement brand recommendations

## Curriculum Updates

When adding a new week:
1. Add to `12-WEEK-LEARNING-PLAN.md` syllabus
2. Create worksheet in `curriculum/worksheets/week_XX_topic.md`
3. Create quiz in `curriculum/quizzes/week_XX_topic.md`
4. Add quiz questions to `assets/quiz-game/gameData.json`
5. Update `curriculum/GLOSSARY.md` with any new terms

## License

MIT — see LICENSE.
