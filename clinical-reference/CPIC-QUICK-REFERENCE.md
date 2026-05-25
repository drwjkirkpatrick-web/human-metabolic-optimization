# CPIC Quick Reference

High-priority pharmacogenomic variants with **CPIC Level 1A/1B** evidence (actionable dosing guidelines available).

## ⚠️ CRITICAL: DPYD (Dihydropyrimidine Dehydrogenase)

| Variant | rs Number | Effect | Action |
|---------|-----------|--------|--------|
| **DPYD *2A** | rs3918290 (IVS14+1G>A) | Splicing defect | **Contraindicate** fluoropyrimidines |
| **DPYD *13** | rs55886062 (c.1679T>G) | p.Ile560Ser | Dose reduction or alternative |
| **HapB3** | rs75017182 (c.1129-5923C>G) | Splicing defect | Dose reduction |
| **c.2846A>T** | rs67376798 | p.Asp949Val | Consider alternative therapy |

**Drugs affected**: 5-Fluorouracil (5-FU), capecitabine, tegafur
**Consequence**: Reduced activity → Fatal toxicity (neutropenia, mucositis, diarrhea)

---

## 🔑 TPMT (Thiopurine S-Methyltransferase)

| Phenotype | Diplotype | Activity | Dosing |
|-----------|-----------|----------|--------|
| **Poor** | *2/*2, *2/*3A, *3A/*3A | None | **Avoid** thiopurines OR extreme dose reduction |
| **Intermediate** | *1/*2, *1/*3A, *1/*3C | Reduced | Start 30-70% dose, titrate |
| **Normal** | *1/*1 | Normal | Standard dosing |

**Drugs affected**: 6-Mercaptopurine, 6-Thioguanine, Azathioprine
**Testing**: Strongly recommended before initiating therapy

---

## 🪚 CYP2D6

### Activity Score to Phenotype

| Activity Score | Phenotype | Population % | Codeine | Tramadol | Tamoxifen |
|----------------|-----------|--------------|---------|----------|-----------|
| 0 | Poor | ~7% | **Avoid** | Avoid | Consider alternatives |
| 0.5 | Intermediate | ~10% | Avoid | Reduce dose | May reduce efficacy |
| 1.0-2.0 | Normal | ~77% | Standard | Standard | Standard |
| >2.0 | Ultra-rapid | ~5-10% | **Avoid** | Use caution | Standard |

### Key Star Alleles

| Allele | rs Numbers | Effect |
|--------|------------|--------|
| *3 | rs35742686 | Splicing (no function) |
| *4 | rs3892097 | Splicing (no function) |
| *5 | Gene deletion | No enzyme |
| *6 | rs5030655 | Frameshift (no function) |
| *10 | rs1065852 | Reduced function (Asian common) |
| *17 | rs28371706 | Reduced function (African common) |
| *41 | rs28371725 | Reduced function |
| *1xN, *2xN | Duplication | Increased activity |

---

## 🩸 CYP2C19

| Phenotype | Diplotype Example | Clopidogrel | PPIs | Voriconazole |
|-----------|-------------------|-------------|------|--------------|
| **Poor** | *2/*2, *2/*3 | **Avoid** → use prasugrel/ticagrelor | Standard | Reduce dose |
| **Intermediate** | *1/*2, *1/*3 | Reduced efficacy | Standard | Standard |
| **Normal** | *1/*1 | Standard | Standard | Standard |
| **Ultra-rapid** | *17/*17 | Standard | Consider alternatives | Standard |

### Key Variants

| Allele | rs Number | Change | Frequency |
|--------|-----------|--------|-----------|
| *2 | rs4244285 | p.Pro227Leu | ~15% Caucasian, ~30% Asian |
| *3 | rs4986893 | p.Trp212Ter | Rare |
| *17 | rs12248560 | Promoter ↑ | ~20% Caucasian |

---

## 🩹 CYP2C9

### Warfarin Dosing

| Genotype | CYP2C9 Effect | VKORC1 Effect | Dose Adjustment |
|----------|---------------|---------------|-----------------|
| *1/*1 | Normal | -1639G>A GG | Standard (5-7mg) |
| *1/*2 | Reduced | -1639G>A GA | Reduce 20-40% |
| *1/*3 | Reduced | -1639G>A AA | Reduce 30-50% |
| *2/*2, *2/*3, *3/*3 | Poor | Any | Reduce 50-90% |

**Key variants**: *2 (rs1799853), *3 (rs1057910)

---

## 💚 CYP3A5

| Genotype | Expression | Tacrolimus Dosing |
|----------|------------|-------------------|
| *1/*1 (Expressor) | High | Standard or higher |
| *1/*3 | Intermediate | Standard |
| *3/*3 (Non-expressor) | None | Reduce dose 1.5-2x |

**Key variant**: *3 (rs776746) - Intron 3 splice variant

---

## 🟠 UGT1A1

### Irinotecan Dosing (Colorectal Cancer)

| Genotype | TA Repeat | Risk | Dosing |
|----------|-----------|------|--------|
| *1/*1 | 6/6 | Low | Standard |
| *1/*28 | 6/7 | Moderate | Reduce dose |
| *28/*28 | 7/7 | High | **Avoid** or extreme reduction |
| *1/*6 (Asian) | - | Moderate | Reduce dose |

**Key variant**: *28 (rs8175347) - TA7 promoter repeat
**Also causes**: Gilbert syndrome (mild unconjugated hyperbilirubinemia)

---

## 🔴 G6PD (Glucose-6-Phosphate Dehydrogenase)

| Class | Variants | Drugs to Avoid |
|-------|----------|----------------|
| **Deficient** | Mediterranean, Canton, A- | Primaquine, dapsone, rasburicase, methylene blue |
| **Normal** | B (wild-type) | Standard |

**Testing**: Required before primaquine (radical cure of P. vivax malaria)

---

## 💜 SLCO1B1 (Statin Myopathy)

| Genotype | Myopathy Risk | Recommendation |
|----------|---------------|----------------|
| *1A/*1A | Low | Standard simvastatin |
| *1A/*5, *1A/*15 | Moderate | Consider lower dose or alternative |
| *5/*5, *5/*15, *15/*15 | High | **Avoid** high-dose simvastatin |

**Key variant**: *5 (rs4149056) p.Val174Ala
**Affected drugs**: Simvastatin, atorvastatin

---

## Quick Decision Tree

```
Starting fluoropyrimidine (5-FU, capecitabine)?
└─→ Test DPYD → If variant → Contraindicate or reduce dose

Starting thiopurine (6-MP, azathioprine)?
└─→ Test TPMT → Poor metabolizer → Avoid or extreme reduction

Starting clopidogrel?
└─→ Test CYP2C19 → Poor metabolizer → Use prasugrel/ticagrelor

Starting warfarin?
└─→ Test CYP2C9 + VKORC1 → Adjust initial dose

Starting tacrolimus?
└─→ Test CYP3A5 → *3/*3 → Reduce dose

Starting irinotecan?
└─→ Test UGT1A1 → *28/*28 → Reduce dose or avoid

Starting primaquine?
└─→ Test G6PD → Deficient → Contraindicate
```

---

**Sources**: CPIC Guidelines (cpicpgx.org), updated 2024
