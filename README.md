# Human Metabolic Optimization

**A clinically referenced curriculum for pharmacogenomics, metabolic pathway enzymology, and cofactor-guided nutritional medicine.**

Open educational resource for students, educators, and healthcare professionals exploring how genetic variation shapes drug response, nutrient requirements, and metabolic health. Built for self-directed learning, classroom instruction, and clinical reference — not as a substitute for individualized medical care.

---

## What's Inside

| Layer | Description | Size |
|-------|-------------|------|
| **Clinical Reference** | 22 metabolic pathway tables, 450+ enzymes with rs numbers, star alleles, cofactors | `clinical-reference/SKILL.md` (~102 KB) |
| **Ranked SNP List** | Tier 1–5 pharmacogenomic variants by clinical actionability | `clinical-reference/CLINICALLY-RANKED-SNPs.md` (~15 KB) |
| **CPIC Quick Reference** | Level 1A/1B dosing adjustments for high-impact variants | `clinical-reference/CPIC-QUICK-REFERENCE.md` (~6 KB) |
| **12-Week Curriculum** | Progressive learning plan with worksheets and weekly quizzes | `curriculum/` (~41 KB plan + 12 worksheets + 12 quizzes) |
| **Master Quiz** | 72 clinically verified Q&A with cited references, professional UI | `assets/quiz-game/master-quiz.html` (~92 KB) |

---

## Master Quiz — 72 Questions, 24 Categories

A self-contained HTML quiz application. No server, no dependencies — just open it in a browser.

**Features:**
- 72 scenario-driven questions across 24 metabolic and pharmacogenomic categories
- Every answer backed by a cited reference (CPIC, PharmGKB, GeneReviews, PubMed, FDA, OMIM)
- Clean, professional light theme with easy-to-read typography
- Two modes: play all 72 shuffled, or focus on a single category
- Progress bar, score circle, category breakdown with visual bars
- Missed-question review with explanations and source links
- Mobile responsive

**Categories (3 questions each):**

| Category | Coverage |
|----------|----------|
| Detox Priming | GSTM1/GSTT1 null, glutathione, selenium |
| Methylation | MTHFR C677T, homocysteine, folate |
| One-Carbon | MTR/MTRR, methyl-folate trap, B12 |
| Gateway | MDR1/ABCB1, P-glycoprotein, curcumin |
| Liver Phase I | CYP2D6, codeine, tamoxifen |
| Liver Phase II | NAT2, UGT1A1*28, Gilbert's/irinotecan |
| Renal | ACE I/D, blood pressure, electrolytes |
| Colon | LPL, triglycerides, omega-3 |
| Skin/Lungs | COMT, dopamine, estrogen clearance |
| Archetypes | APOE ε4, Alzheimer's risk, Explorer genotype |
| Mitochondria | PPAR-γ, chromium, alpha-lipoic acid, G6PD |
| Sensitivity | Herxheimer reaction, slow acetylators, GST null |
| Critical PGx | DPYD *2A + 5-FU, TPMT *3A + thiopurines, HLA-B*57:01 + abacavir |
| Antiplatelet PGx | CYP2C19 *2/*2 + clopidogrel, prasugrel/ticagrelor alternatives |
| Warfarin Dosing | CYP2C9 *2/*3, VKORC1 -1639G>A, CYP4F2 |
| Statin Safety | SLCO1B1 *5 + rhabdomyolysis, CPIC guidance, HMGCR |
| Urea Cycle | OTC deficiency, hyperammonemic crisis, NAGS + carglumic acid |
| Antioxidant Enzymes | SOD2 Ala16Val, GPX1 + selenium, NQO1 null + benzene |
| Oxalate Metabolism | AGXT G170R + B6, vitamin C → oxalate, calcium binding |
| Vitamin D Processing | VDR FokI, GC binding protein, CYP2R1 25-hydroxylation |
| Neurotransmitters | MAOA VNTR, TPH2, SERT 5-HTTLPR |
| Heme & Porphyria | AIP/HMBS, barbiturate precipitants, safe alternatives |
| Fatty Acid Oxidation | MCAD hypoketotic hypoglycemia, CPT2 myopathy, riboflavin MADD |
| Lysosomal Disorders | Gaucher/GBA + Parkinsonism, Fabry/GLA, Pompe/GAA + ERT |

**To run locally:**
```bash
cd assets/quiz-game
python3 -m http.server 8124
# Open http://localhost:8124/master-quiz.html
```

---

## Clinical Reference

### SKILL.md — 22 Pathway Tables

Open `clinical-reference/SKILL.md` in any markdown reader. Organized by pathway:

| # | Pathway | # | Pathway |
|---|---------|---|---------|
| 1 | Phase I Drug Metabolism (CYP450) | 12 | Neurotransmitter Metabolism |
| 2 | Phase II Conjugation (NAT2, COMT, UGT, GST) | 13 | Heme / Porphyrin |
| 3 | One-Carbon / Methylation | 14 | Purine / Pyrimidine |
| 4 | Urea Cycle | 15 | Fatty Acid Beta-Oxidation |
| 5 | Citric Acid Cycle | 16 | Oxidative Phosphorylation |
| 6 | Lipid Metabolism | 17 | Steroid Biosynthesis |
| 7 | Amino Acid Metabolism | 18 | Glycogen Metabolism |
| 8 | Oxalate / Glyoxylate | 19 | Bile Acid Synthesis |
| 9 | Vitamin C Transport & Recycling | 20 | Connective Tissue / Collagen |
| 10 | Cofactor/Mineral Processing | 21 | Lysosomal Enzymes |
| 11 | Mineral Cofactor Summary | 22 | Melanin / Tyrosine Metabolism |

Every enzyme entry includes rs numbers, cDNA changes, protein changes, star alleles where applicable, mandatory vitamin/mineral cofactors, and clinical significance.

### CLINICALLY-RANKED-SNPs.md — Tier 1–5

Variants ranked by clinical impact and actionability:

- **Tier 1 — Critical:** DPYD, TPMT, HLA-B*57:01 (life-threatening, mandatory testing)
- **Tier 2 — Major Dosing:** CYP2C19, CYP2D6, CYP2C9/VKORC1, G6PD, UGT1A1, SLCO1B1
- **Tier 3 — Moderate:** NAT2, CYP2B6, CYP1A2, CYP3A5
- **Tier 4 — Functional:** MTHFR, COMT, APOE
- **Tier 5 — Emerging:** Research-phase associations

---

## 12-Week Curriculum

Open `curriculum/12-WEEK-LEARNING-PLAN.md` and work through one week at a time. Each week includes learning objectives, reading assignments, a clinical audit worksheet, a scenario-based quiz, and clinical pearls.

| Weeks | Focus | Tier | Key Genes |
|-------|-------|------|-----------|
| 1 | Foundations & CPIC Evidence | — | Overview |
| 2–4 | Life-Threatening Variants | 1 | DPYD, TPMT, HLA-B |
| 5–8 | Major Dosing Adjustments | 2 | CYP2C19, CYP2D6, CYP2C9/VKORC1, G6PD, UGT1A1 |
| 9–11 | Functional + Nutritional | 3–4 | SLCO1B1, CYP3A5, NAT2, CYP2B6, MTHFR, COMT, APOE |
| 12 | Integration & Final Assessment | — | Multi-gene cases |

---

## Cofactor Philosophy

Every enzyme in `SKILL.md` lists required cofactors — the bridge between pharmacogenomics and nutritional medicine:

| Cofactor | Enzymes | Function |
|----------|---------|----------|
| Iron (heme) | CYP450 family | Phase I oxidation |
| B6, B12, folate | MTHFR, MTR, MTRR | One-carbon cycle |
| Magnesium | 300+ ATP-dependent enzymes | Energy transfer |
| Zinc | SOD1, DNA polymerases | Antioxidant, synthesis |
| Copper | SOD1, cytochrome c oxidase | Antioxidant, respiration |
| Manganese | SOD2, arginase | Mitochondrial defense |
| Selenium | GPX1–4, deiodinases | Glutathione peroxidase |
| Molybdenum | Sulfite oxidase | Sulfite detoxification |

---

## Repository Layout

```
human-metabolic-optimization/
├── README.md                              # This file
├── LICENSE                                # MIT
├── clinical-reference/
│   ├── SKILL.md                           # 22 pathway tables, 450+ enzymes
│   ├── CLINICALLY-RANKED-SNPs.md          # Tier 1-5 variants by actionability
│   ├── CPIC-QUICK-REFERENCE.md            # Level 1A/1B dosing adjustments
│   └── CHANGELOG.md                       # Reference update history
├── curriculum/
│   ├── 12-WEEK-LEARNING-PLAN.md           # Full curriculum with study activities
│   ├── GLOSSARY.md                        # Genetics, metabolism, emunctorology terms
│   ├── worksheets/                        # 12 weekly clinical audit templates
│   └── quizzes/                           # 12 weekly scenario-based quizzes
├── assets/
│   └── quiz-game/
│       ├── master-quiz.html               # 72-Q interactive quiz (self-contained)
│       ├── index.html                     # Original quiz (24 Q)
│       └── gameData.json                  # Original question data
├── docs/
│   ├── ARCHITECTURE.md                    # Repository structure guide
│   └── CONTRIBUTING.md                    # How to contribute
└── .github/
    └── workflows/
        └── ci.yml                         # Markdown lint + schema validation
```

---

## High-Impact Variants at a Glance

| Gene | Variant | Clinical Impact | Action |
|------|---------|-----------------|--------|
| DPYD | *2A (rs3918290) | 5-FU fatal toxicity | Contraindicate fluoropyrimidines |
| TPMT | *3A (rs1800460 + rs1142345) | Thiopurine myelosuppression | Dose reduce or avoid |
| HLA-B | *57:01 | Abacavir hypersensitivity | Absolute contraindication |
| CYP2C19 | *2 (rs4244285) | Clopidogrel ineffective | Switch to prasugrel/ticagrelor |
| CYP2D6 | *3–*6, *1xN | Codeine toxicity or inefficacy | Avoid or adjust opioids |
| CYP2C9 | *2/*3 | Warfarin over-anticoagulation | Reduce per CPIC algorithm |
| VKORC1 | -1639G>A | Warfarin sensitivity | Reduce maintenance dose |
| SLCO1B1 | *5 (rs4149056) | Statin rhabdomyolysis | Reduce statin dose or switch |
| G6PD | Deficient variants | Hemolytic anemia | Avoid oxidant drugs |
| UGT1A1 | *28 (rs8175347) | Irinotecan toxicity | Dose reduce per CPIC |
| MTHFR | C677T (rs1801133) | Homocysteine elevation | L-methylfolate supplementation |
| APOE | ε4 | Alzheimer's risk, statin response | Clinical counseling |

---

## Who This Is For

- Naturopathic and functional medicine practitioners
- Pharmacists and pharmacy students
- Genetic counselors
- Students of clinical enzymology and pharmacogenomics
- Educators seeking structured curriculum materials

**Prerequisites:** basic genetics, pharmacology, and cell biology. This does not replace formal certification or supervised clinical training.

---

## External References

- [CPIC Guidelines](https://cpicpgx.org/) — Clinical Pharmacogenetics Implementation Consortium
- [PharmGKB](https://www.pharmgkb.org/) — Pharmacogenomics Knowledge Base
- [ClinVar](https://www.ncbi.nlm.nih.gov/clinvar/) — SNP clinical significance
- [GeneReviews](https://www.ncbi.nlm.nih.gov/books/NBK1116/) — Inherited disorder references
- [OMIM](https://omim.org/) — Online Mendelian Inheritance in Man
- [KEGG Pathway](https://www.genome.jp/kegg/pathway.html) — Metabolic pathway maps
- [Reactome](https://reactome.org/) — Pathway database

---

## Clinical Disclaimer

**All content in this repository is for educational and reference purposes only.**

This curriculum is not a substitute for professional medical advice, diagnosis, or treatment. If you intend to use any information here — including supplement protocols, dosing suggestions, dietary recommendations, or medication considerations — **you must first discuss them with your personal physician, pharmacist, or other licensed healthcare practitioner.** They are the only ones who can evaluate how this general educational material applies to your specific health situation.

**This is not self-medicine.** The information here is general and educational. It cannot account for personal medical history, current medications, allergies, pregnancy status, or other clinical details that require individualized professional assessment.

Key cautions for healthcare providers:
- CYP phenotyping requires activity score methodology (CPIC guidelines)
- Population variant frequencies vary significantly by ancestry
- Recommend multi-gene pharmacogenomic panels for complex patients
- Very few single SNPs have clinically actionable consequences in isolation
- Always verify against current CPIC guidelines and PharmGKB before applying

---

## Contributing

See `docs/CONTRIBUTING.md` for guidelines. Areas welcome for contributions:
- Additional population-specific variant frequencies
- New CPIC guideline updates
- Additional rare disease associations
- Enzyme kinetics data (Km, Vmax)
- Quiz question expansion

---

## License

MIT License — see [LICENSE](LICENSE) for details.

---

**Last Updated:** August 2026