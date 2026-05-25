# Human Metabolic Optimization

**A comprehensive clinical reference and progressive learning curriculum for human metabolic pathways, pharmacogenomic SNPs, and cofactor-guided nutritional medicine.**

This repository is designed as an **open educational resource** for students, educators, and healthcare professionals seeking to understand how genetic variation influences metabolism, drug response, and nutrient requirements. The content is presented for self-directed learning, classroom instruction, and clinical reference — not as a substitute for individualized medical care.

**Live on:** https://github.com/drwjkirkpatrick-web/human-metabolic-optimization

---

## Educational Purpose

This is a **free, open-access curriculum** built around three integrated learning layers:

1. **Clinical Reference** — 22 metabolic pathway tables covering 450+ enzymes, specific rs numbers, cDNA/protein changes, and mandatory vitamin/mineral cofactors for every step.
2. **12-Week Curriculum** — Progressive learning plan from CPIC guidelines through multi-gene clinical integration, with worksheets and quizzes.
3. **Interactive Quiz Game** — Category-selectable browser-based knowledge checks with 48 scenario-driven questions.

**Who this is for:**
- Academic programs in pharmacogenomics, nutritional biochemistry, or functional medicine
- Self-directed learners building expertise in metabolic enzymology
- Clinical training programs requiring structured cases and competency checks
- Educators seeking ready-made worksheets, quizzes, and clinical scenarios

This curriculum assumes prerequisite knowledge in basic genetics, pharmacology, and cell biology. It does not replace formal certification or supervised clinical training.

**Built for:** Naturopathic physicians, functional medicine practitioners, pharmacists, genetic counselors, and students of clinical enzymology.

---

## Repository Layout

```
human-metabolic-optimization/
├── README.md                          # This file
├── LICENSE                            # MIT
├── clinical-reference/
│   ├── SKILL.md                       # Master reference: 22 pathway tables
│   ├── CLINICALLY-RANKED-SNPs.md      # Tier 1-5 SNPs by clinical actionability
│   └── CPIC-QUICK-REFERENCE.md        # Critical dosing adjustments
├── curriculum/
│   ├── 12-WEEK-LEARNING-PLAN.md       # Full 12-week curriculum with study activities
│   ├── GLOSSARY.md                    # Genetics, metabolism, and emunctorology terms
│   ├── worksheets/
│   │   ├── week_01_detox_priming.md
│   │   ├── week_02_methylation_audit.md
│   │   └── ... (all 12 weeks)
│   └── quizzes/
│       ├── week_01_priming_quiz.md
│       ├── week_02_methylation_quiz.md
│       └── ... (all 12 weeks)
├── assets/
│   └── quiz-game/
│       ├── index.html                 # Self-contained React quiz (open in browser)
│       └── gameData.json              # Question data source
└── .github/
    └── workflows/
        └── ci.yml                     # Markdown lint + schema validation
```

---

## Quick Start

### Browse the Reference

Open `clinical-reference/SKILL.md` in any markdown reader. It's organized by pathway:

| Section | Pathway |
|---------|---------|
| 1 | Phase I Drug Metabolism (CYP450) |
| 2 | Phase II Conjugation (NAT2, COMT, UGT, GST) |
| 3 | One-Carbon / Methylation |
| 4 | Urea Cycle |
| 5 | Citric Acid Cycle |
| 6 | Lipid Metabolism |
| 7 | Amino Acid Metabolism |
| 8 | Oxalate / Glyoxylate |
| 9 | Vitamin C Transport & Recycling |
| 10 | Cofactor/Mineral Processing |
| 11 | Mineral Cofactor Summary |
| 12 | Neurotransmitter Metabolism |
| 13 | Heme / Porphyrin |
| 14 | Purine / Pyrimidine |
| 15 | Fatty Acid Beta-Oxidation |
| 16 | Oxidative Phosphorylation |
| 17 | Steroid Biosynthesis |
| 18 | Glycogen Metabolism |
| 19 | Bile Acid Synthesis |
| 20 | Connective Tissue / Collagen |
| 21 | Lysosomal Enzymes |
| 22 | Melanin / Tyrosine Metabolism |

Every enzyme entry includes:
- **rs numbers** (e.g., `rs1065852`)
- **cDNA changes** (e.g., `c.100C>T`)
- **Protein changes** (e.g., `p.Pro34Ser`)
- **Star alleles** where applicable (e.g., `CYP2D6 *10`)
- **Mandatory vitamin/mineral cofactors**
- **Clinical significance** (CPIC level, disease association)

### Follow the Curriculum

Open `curriculum/12-WEEK-LEARNING-PLAN.md` and work through one week at a time. Each week includes:
- Learning objectives
- Reading assignments (from SKILL.md and external CPIC/PharmGKB)
- Worksheet (clinical audit template)
- Quiz (scenario-based multiple choice)
- Clinical pearls

| Week | Topic | Tier |
|------|-------|------|
| 1 | Foundations & CPIC Evidence | — |
| 2 | DPYD (Fluoropyrimidines) | 1 |
| 3 | TPMT (Thiopurines) | 1 |
| 4 | HLA-B (Stevens-Johnson / DRESS) | 1 |
| 5 | CYP2C19 (Clopidogrel / PPIs) | 2 |
| 6 | CYP2D6 (Opioids / Psychotropics) | 2 |
| 7 | CYP2C9/VKORC1 (Warfarin) | 2 |
| 8 | G6PD & UGT1A1 | 2 |
| 9 | SLCO1B1 & CYP3A5 | 2-3 |
| 10 | NAT2, CYP2B6, CYP1A2 | 3 |
| 11 | MTHFR, COMT, APOE | 4 |
| 12 | Integration & Final Assessment | — |

### Play the Quiz

1. Open `assets/quiz-game/index.html` in any browser
2. No server needed — it's a self-contained HTML file with embedded React
3. 24 questions across 12 metabolic categories
4. Score tracking with category breakdown

---

## Core Focus Areas

### High-Impact Pharmacogenomic Variants

| Gene | Variant | Clinical Impact |
|------|---------|-----------------|
| CYP2C19 | *2 (rs4244285) | Clopidogrel ineffective — switch to prasugrel |
| CYP2D6 | *3-*6, *10, *1xN | Codeine toxicity or inefficacy |
| DPYD | *2A (IVS14+1G>A) | 5-FU fatal toxicity — dose reduce 50% |
| TPMT | *2, *3A | Thiopurine myelosuppression — dose reduce |
| HLA-B | *57:01 | Abacavir hypersensitivity — absolute contraindication |
| MTHFR | C677T (rs1801133) | Homocysteine elevation — L-methylfolate |
| COMT | Val158Met (rs4680) | Pain sensitivity, dopamine levels |
| APOE | ε2/ε3/ε4 | Alzheimer risk, statin response |

### Cofactor Philosophy

Every enzyme entry in `SKILL.md` lists required cofactors. This is not optional — it's the bridge between pharmacogenomics and nutritional medicine:

- **Iron (heme)** → CYP450 enzymes
- **B6, B12, folate** → One-carbon cycle
- **Magnesium** → ATP-dependent reactions (>300 enzymes)
- **Zinc** → SOD1, DNA polymerases
- **Copper** → SOD1, cytochrome c oxidase
- **Manganese** → SOD2, arginase
- **Selenium** → GPX1-4, deiodinases
- **Molybdenum** → Sulfite oxidase

---

## Curriculum by Week

### Weeks 1-4: Foundations + Tier 1 (Life-Threatening)
- **Week 1:** CPIC evidence levels, star alleles, population frequencies
- **Week 2:** DPYD — fluoropyrimidines, dose reduction algorithms
- **Week 3:** TPMT — thiopurines, myelosuppression risk
- **Week 4:** HLA-B — abacavir hypersensitivity, carbamazepine SJS

### Weeks 5-8: Tier 2 (Major Dosing Adjustments)
- **Week 5:** CYP2C19 — clopidogrel, PPIs, psychiatric meds
- **Week 6:** CYP2D6 — codeine, tamoxifen, antidepressants
- **Week 7:** CYP2C9/VKORC1 — warfarin dosing algorithms
- **Week 8:** G6PD & UGT1A1 — hemolysis risk, irinotecan toxicity

### Weeks 9-11: Tier 3-4 (Functional + Nutritional)
- **Week 9:** SLCO1B1 & CYP3A5 — statin myopathy, tacrolimus
- **Week 10:** NAT2, CYP2B6, CYP1A2 — isoniazid, efavirenz, smoking
- **Week 11:** MTHFR, COMT, APOE — methylation, pain, cognition

### Week 12: Integration
- Multi-gene case studies
- Final comprehensive assessment
- Protocol design workshop

---

## Clinical Disclaimer

**All content in this repository is for educational and reference purposes only.**

This curriculum is not a substitute for professional medical advice, diagnosis, or treatment. It does not replace the judgment of a qualified healthcare provider.

If you intend to use any of the information here — including supplement protocols, dosing suggestions, dietary recommendations, or medication considerations — **you must first discuss them with your personal physician, pharmacist, or other licensed healthcare practitioner.** They are the only ones who can evaluate how this general educational material applies to your specific health situation.

Goals for self-directed learners:
- Understand how genes influence metabolism, drug response, and nutrient handling
- Recognize when a question may warrant referral to a specialist or genetic counselor
- Communicate more effectively with your healthcare team

**This is not self-medicine.** The information here is general and educational. It cannot account for your personal medical history, current medications, allergies, pregnancy status, or other clinical details that require individualized professional assessment.

Key cautions for healthcare providers and educators:
- CYP phenotyping requires **activity score methodology** (CPIC guidelines)
- Population variant frequencies vary significantly by ancestry
- Recommend **multi-gene pharmacogenomic panels** for complex patients
- Very few single SNPs have clinically actionable consequences in isolation
- Always verify information against current CPIC guidelines and PharmGKB before applying recommendations

---

## External References

- [CPIC Guidelines](https://cpicpgx.org/) — Clinical Pharmacogenetics Implementation Consortium
- [PharmGKB](https://www.pharmgkb.org/) — Pharmacogenomics Knowledge Base
- [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/) — SNP clinical significance
- [KEGG Pathway](https://www.genome.jp/kegg/pathway.html) — Metabolic pathway maps
- [Reactome](https://reactome.org/) — Pathway database

---

## Contributing

Contributions welcome in these areas:
- Additional population-specific variant frequencies
- New CPIC guideline updates
- Additional rare disease associations
- Enzyme kinetics data (Km, Vmax)
- Quiz question expansion

---

## License

MIT License — see LICENSE for details.

---

**Maintained by:** Walker (Oregon naturopathic physician)  
**Last Updated:** May 2026  
**Skill Version:** 1.3  
**Curriculum Weeks:** 12 core
