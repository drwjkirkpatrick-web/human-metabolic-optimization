     1|---
     2|name: human-metabolic-snp
     3|title: Human Metabolic Pathways & Pharmacogenomic SNPs
     4|description: Comprehensive reference catalog of human metabolic enzymes, pathways, and clinically actionable SNPs. Covers Phase I/II drug metabolism, one-carbon cycle, urea cycle, citric acid cycle, lipid metabolism, amino acid metabolism, oxalate metabolism, vitamin C recycling, purine/pyrimidine metabolism, fatty acid oxidation, oxidative phosphorylation, steroid biosynthesis, glycogen metabolism, bile acid synthesis, connective tissue, lysosomal enzymes, melanin synthesis, and mineral cofactor pathways.
     5|category: clinic
     6|---
     7|
     8|# Human Metabolic Pathways & Pharmacogenomic SNPs
     9|
    10|## Additional Resources
    11|
    12|This skill includes reference files for deeper study:
    13|- `references/clinically-ranked-snps.md` - SNPs ranked by clinical actionability (Tier 1-5)
    14|- `references/12-week-learning-curriculum.md` - Educational plan for mastering pharmacogenomics
    15|
    16|## Purpose
    17|Enable precise, clinically-oriented Q&A about human metabolic enzymology, pathway flux, and pharmacogenomic variation. Use this when the user asks about:
    18|- Specific gene/enzyme function (e.g. *CYP2D6*, *MTHFR*, *COMT*, *NAT2*)
    19|- SNP effects on metabolism (e.g. *C677T*, *rs4680*, *CYP3A4* *22*)
    20|- Pathway interactions (e.g. folate ↔ methionine ↔ homocysteine)
    21|- Drug metabolism implications (e.g. "is this a poor metabolizer?")
    22|- Nutrient cofactor requirements tied to enzyme variants
    23|- Inborn errors of metabolism (e.g. fatty acid oxidation disorders, glycogen storage diseases)
    24|- Enzyme replacement therapy eligibility
    25|
    26|---
    27|
    28|## Quick Reference: Pathway Coverage
    29|
    30|| Section | Pathway | Key Clinical Applications |
    31||---------|---------|--------------------------|
    32|| 1 | Phase I Drug Metabolism (CYPs) | Pharmacogenomic dosing, adverse reactions |
    33|| 2 | Phase II Conjugation | TPMT, NAT2, COMT, UGT activity |
    34|| 3 | One-Carbon Cycle | MTHFR, methylation, homocysteine |
    35|| 4 | Urea Cycle | Hyperammonemia disorders |
    36|| 5 | Citric Acid Cycle | Mitochondrial energy, cancer metabolism |
    37|| 6 | Lipid Metabolism | APOE, statin response, omega-3 synthesis |
    38|| 7 | Amino Acid Metabolism | PKU, MSUD, antioxidant enzymes |
    39|| 8 | Oxalate Metabolism | Kidney stones, primary hyperoxaluria |
    40|| 9 | Vitamin C Transport | Scurvy risk, antioxidant status |
    41|| 10 | Cofactor Processing | Vitamin D, B12 metabolism |
    42|| 11 | Mineral Summary | Mg, Zn, Fe, Cu, Mn, Se, Mo reference |
    43|| 12 | Neurotransmitters | Depression, ADHD, Parkinson's |
    44|| 13 | Heme/Porphyrin | Acute intermittent porphyria |
    45|| 14 | Purine/Pyrimidine | Gout, 5-FU toxicity, Lesch-Nyhan |
    46|| 15 | Fatty Acid Oxidation | MCAD, VLCAD, metabolic crisis |
    47|| 16 | Oxidative Phosphorylation | Mitochondrial disease, LHON, MELAS |
    48|| 17 | Steroid Biosynthesis | CAH, PCOS, DSD, finasteride response |
    49|| 18 | Glycogen Metabolism | GSD types, Pompe disease |
    50|| 19 | Bile Acid Synthesis | CTX, PFIC, cholestasis |
    51|| 20 | Connective Tissue | EDS types, collagen crosslinking |
    52|| 21 | Lysosomal Enzymes | Fabry, Gaucher, MPS, ERT eligibility |
    53|| 22 | Melanin Metabolism | Albinism, skin cancer risk |
    54|
    55|---
    56|
    57|## 1. Phase I Drug Metabolism — Cytochrome P450 Superfamily
    58|
    59|### High-Clinical-Impact Isoforms
    60|| Gene | Substrate Examples | Key SNPs / Alleles | Phenotype Consequence | Cofactor |
    61||------|-------------------|-------------------|----------------------|----------|
    62|| **CYP1A2** | Caffeine, clozapine, olanzapine, theophylline | *1F (rs762551), *1K | Inducible; *1F = faster metabolizer; smoking induces 1A2 | **Iron** (heme-thiolate) |
    63|| **CYP2B6** | Efavirenz, cyclophosphamide, bupropion, ketamine | *6 (rs3745274), *18 | *6 = reduced function; efavirenz toxicity risk | **Iron** |
    64|| **CYP2C9** | Warfarin, phenytoin, losartan, NSAIDs | *2 (rs1799853), *3 (rs1057910), *5-*13 | *2/*3 = reduced warfarin dose needed; bleeding risk | **Iron** |
    65|| **CYP2C19** | Clopidogrel, PPIs, diazepam, voriconazole | *2 (rs4244285), *3 (rs4986893), *17 (rs12248560) | *2/*3 = poor metabolizer → clopidogrel ineffective; *17 = ultra-rapid | **Iron** |
    66|| **CYP2D6** | Codeine, tamoxifen, tramadol, nortriptyline, metoprolol | *3-*6, *9-*12, *17, *41, *10 (rs1065852), *1xN/*2xN (gene duplication) | Poor/ultra-rapid metabolizer status; codeine toxicity or inefficacy; tamoxifen efficacy | **Iron** |
    67|| **CYP3A4** | Tacrolimus, simvastatin, midazolam, erythromycin | *22 (rs35599367), *1B | *22 = reduced expression; tacrolimus dose reduction | **Iron** |
    68|| **CYP3A5** | Tacrolimus, cyclosporine | *3 (rs776746) | *3 = non-expressor; higher tacrolimus dose needed if *1/*1 | **Iron** |
    69|
    70|### CYP2D6 Star Allele Phenotyping (Quick Reference)
    71|- **Poor Metabolizer (PM):** *3, *4, *5 (gene deletion), *6, *7-*8, *11-*12, *13-*16, etc. — no functional enzyme
    72|- **Intermediate Metabolizer (IM):** *9, *10, *17, *29, *41, *59 — reduced activity
    73|- **Normal/Extensive Metabolizer (EM):** *1, *2, *27, *33, *35, *39
    74|- **Ultra-Rapid Metabolizer (UM):** *1xN, *2xN, *35x2 — gene duplications; codeine → morphine rapid conversion (toxicity in children/breastfeeding)
    75|
    76|---
    77|
    78|## 2. Phase II Drug Metabolism — Conjugation Enzymes
    79|
    80|| Gene | Enzyme | Key SNPs | Functional Impact | Cofactor |
    81||------|--------|----------|-------------------|----------|
    82|| **NAT1** | N-acetyltransferase 1 | *10, *11, *14, *17, *22 | Slow acetylator → sulfonamide toxicity, 5-aminosalicylate efficacy | **CoA** (pantothenate-derived) |
    83|| **NAT2** | N-acetyltransferase 2 | *5 (rs1799930), *6 (rs1799931), *7, *14 | Slow acetylator → isoniazid neuropathy, hydralazine lupus, procainamide toxicity | **CoA** |
    84|| **GSTT1** | Glutathione S-transferase theta 1 | Null deletion (whole gene) | No enzyme → increased toxicity with alkylating agents; protective against some carcinogens | None |
    85|| **GSTM1** | Glutathione S-transferase mu 1 | Null deletion | Same pattern as GSTT1 | None |
    86|| **GSTP1** | GST pi 1 | rs1695 (I105V) | Reduced detox capacity | None |
    87|| **TPMT** | Thiopurine S-methyltransferase | *2 (rs1800462), *3A (rs1800460+rs1142345), *3C | Reduced activity → 6-MP/6-TG/azathioprine fatal myelosuppression if standard dosing | **SAM** (methionine-derived) |
    88|| **COMT** | Catechol-O-methyltransferase | Val158Met (rs4680) | Met/Met = low activity → higher synaptic dopamine; pain sensitivity; estrogen metabolism | **SAM**, **Magnesium** |
    89|| **UGT1A1** | UDP-glucuronosyltransferase 1A1 | *28 (rs8175347, TA7 promoter) | Reduced bilirubin conjugation → irinotecan severe diarrhea/neutropenia; Gilbert syndrome | **UDP-glucuronic acid** |
    90|| **UGT2B7** | UDP-glucuronosyltransferase 2B7 | C802T (His268Tyr), T802C | Morphine/codeine glucuronidation variability | **UDP-glucuronic acid** |
    91|| **SULT1A1** | Sulfotransferase 1A1 | rs9282861 (Arg213His) | Reduced sulfation of estrogens, xenobiotics | **PAPS** (sulfur-derived) |
    92|| **SULT1A3** | Sulfotransferase 1A3 | rs3779499 | Dopamine sulfation | **PAPS** |
    93|
    94|---
    95|
    96|## 3. One-Carbon (Folate/Methionine) Cycle
    97|
    98|The central hub for methylation, nucleotide synthesis, and homocysteine detoxification.
    99|
   100|### Key Enzymes & SNPs
   101|| Gene | Enzyme | Key SNP | cDNA/Protein Change | Biochemical Effect | Clinical Notes | Cofactor |
   102||------|--------|---------|---------------------|-------------------|----------------|----------|
   103|| **MTHFR** | Methylenetetrahydrofolate reductase | **C677T** | c.665C>T (p.Ala222Val) | Thermolabile enzyme; ↓ 70% activity in TT; ↑ homocysteine | Most important MTHFR variant; folate/B12 responsive; compound heterozygote with A1298C increases risk | **FAD**, **Magnesium** |
   104|| **MTHFR** | | **A1298C** | c.1298A>C (p.Glu429Ala) | ↓ 40% enzyme activity; affects BH4 recycling | Less impact than C677T; purine synthesis affected; compound heterozygote = significant impact | **FAD**, **Magnesium** |
   105|| **MTHFR** | | **rs2274976** | c.1296C>T (p.Gly429=, synonymous) | Affects mRNA stability | Asian populations; risk for NTDs | **FAD**, **Magnesium** |
   106|| **MTHFR** | | **rs3737965** | 5'UTR | Promoter variant | Affects transcriptional regulation | **FAD**, **Magnesium** |
   107|| **MTR** | Methionine synthase | **A2756G** | c.2756A>G (p.Asp919Gly) | ↓ remethylation efficiency; ↑ homocysteine | B12 dependent; neuropathy risk; responds to methylcobalamin | **B12** (methylcobalamin), **Zinc** |
   108|| **MTR** | | **c.3518C>T** | (p.Ser1173Leu) | Reduced enzyme activity | Less common; affects B12 recycling | **B12**, **Zinc** |
   109|| **MTRR** | Methionine synthase reductase | **A66G** | c.66A>G (p.Ile22Met) | Impaired reactivation of MTR | B12 functional deficiency; NTD risk | **FAD**, **NADPH** |
   110|| **MTRR** | | **K3504R** | c.1517A>G (p.Lys506Arg) | Reduced reductase activity | Homocysteine elevation | **FAD**, **NADPH** |
   111|| **MTRR** | | **rs2287780** | Intronic | Splicing regulation | Affects MTRR expression levels | **FAD**, **NADPH** |
   112|| **CBS** | Cystathionine beta-synthase | **844ins68** | 68bp insertion in exon 8 | Generally protective; ↓ homocysteine | Common variant; protective against hyperhomocysteinemia; B6 responsive | **PLP** (B6), **Heme** |
   113|| **CBS** | | **C699T** | c.699C>T (p.Thr236=, synonymous) | Affects splicing efficiency | ↓ homocysteine levels; protective | **PLP** (B6), **Heme** |
   114|| **CBS** | | **T833C** | c.833T>C (p.Ile278Thr) | Reduced enzyme activity | ↑ homocysteine; thrombophilia risk | **PLP** (B6), **Heme** |
   115|| **CBS** | | **rs5742905** | Promoter | ↓ transcription | Homocysteine elevation | **PLP** (B6), **Heme** |
   116|| **SHMT** | Serine hydroxymethyltransferase | C1420T (rs1979277) | p.Leu474Phe | Folate partitioning between DNA synthesis vs. methylation | T allele = less 5-mTHF for methylation | **PLP** (B6) |
   117|| **DHFR** | Dihydrofolate reductase | 19bp deletion (rs70991108) | Affects DHFR levels | ↓ dihydrofolate → tetrahydrofolate | Methotrexate response | **NADPH** |
   118|| **TYMS** | Thymidylate synthase | 28bp tandem repeat (5'UTR) | Variable repeats (2R/3R) | ↑ TYMS = more thymidylate, less 5-FU efficacy | 3R/3R = resistance to 5-FU; 2R/2R = better response | None |
   119|| **MTHFD1** | Methylenetetrahydrofolate dehydrogenase | G1958A (rs2236225) | p.Arg653Gln | Impaired formate/10-formyl-THF generation | Miscarriage, NTD risk | **NADP**, **Magnesium** |
   120|| **RFC1** | Reduced folate carrier | A80G (rs1051266) | p.His27Arg | ↓ folate transport | G allele = lower plasma folate | None |
   121|| **FOLR1/FOLR2** | Folate receptors | Various | Affects folate uptake | Folate uptake at placenta/CNS | Neural tube defect association | None |
   122|| **BHMT** | Betaine-homocysteine methyltransferase | G742A (rs3733890) | p.Arg239Gln | Alternative remethylation pathway | Liver-specific; betaine (trimethylglycine) responsive | **Zinc** |
   123|
   124|#### MTHFR Genotype Combinations & Clinical Interpretation
   125|| Genotype | C677T | A1298C | Expected Activity | Clinical Considerations |
   126||----------|-------|--------|-------------------|------------------------|
   127|| **Normal/Normal** | CC | AA | 100% | Standard folate metabolism |
   128|| **C677T heterozygote** | CT | AA | ~70% | Mild elevation in homocysteine possible |
   129|| **C677T homozygote** | TT | AA | ~30-40% | Folate/B12 supplementation beneficial |
   130|| **A1298C heterozygote** | CC | AC | ~70% | Less impact than C677T |
   131|| **A1298C homozygote** | CC | CC | ~60% | BH4 recycling affected |
   132|| **Compound heterozygote** | CT | AC | ~50-60% | Combined effect; higher homocysteine risk |
   133|
   134|#### CBS and Homocysteine Management
   135|| CBS Variant | Effect on Homocysteine | B6 Responsiveness | Clinical Action |
   136||-------------|----------------------|-------------------|-----------------|
   137|| **844ins68** | ↓ Lower homocysteine | Yes | Protective; no action needed |
   138|| **C699T** | ↓ Lower homocysteine | Yes | Protective |
   139|| **T833C** | ↑ Higher homocysteine | Yes | B6 supplementation |
   140|| **rs5742905** | ↑ Higher homocysteine | Variable | Monitor homocysteine |
   141|
   142|### One-Carbon Metabolic Flow
   143|```
   144|Dietary folate → DHF → THF → 5,10-methylene-THF ──MTHFR──→ 5-methyl-THF
   145|                                                        ↓
   146|Homocysteine ←──────MTR/B12────── Methionine ←──── SAM (universal methyl donor)
   147|    ↓ CBS/B6                                          ↓
   148|Cystathionine → Cysteine → Glutathione            COMT, PEMT, DNMTs, etc.
   149|    ↓
   150|Sulfate (via SUOX)
   151|```
   152|
   153|---
   154|
   155|## 4. Urea Cycle & Nitrogen Metabolism
   156|
   157|| Gene | Enzyme | SNP / Variant | Consequence | Cofactor |
   158||------|--------|---------------|-------------|----------|
   159|| **CPS1** | Carbamoyl phosphate synthetase I | p.Thr1406Asn (c.4217C>A); p.Arg1436Gln | Hyperammonemia type I; neonatal lethality if severe | **ATP**, **Magnesium**, **N-acetylglutamate** |
   160|| **OTC** | Ornithine transcarbamylase | c.274C>G (p.Arg92Gly); c.386G>A (p.Arg129His); X-linked | Most common urea cycle disorder; protein load triggers hyperammonemic crisis | None |
   161|| **ASS1** | Argininosuccinate synthetase | c.1168C>T (p.Arg390Cys); c.1121C>T (p.Ala374Val) | Citrullinemia type I; dietary protein restriction needed | **ATP**, **Magnesium**, **Citrulline** |
   162|| **ASL** | Argininosuccinate lyase | c.1124G>A (p.Arg375Gln); c.1085A>G (p.Asn362Ser) | Argininosuccinic aciduria; hepatic/ neurological manifestations | None |
   163|| **ARG1** | Arginase 1 | c.47G>A (p.Trp16*); c.398G>A (p.Arg133His) | Hyperargininemia; spasticity; progressive dementia | **Manganese** |
   164|| **NAGS** | N-acetylglutamate synthase | c.971C>T (p.Ser324Leu); c.851G>A (p.Arg284His) | Hyperammonemia; responds to carglumic acid | **Acetyl-CoA**, **Glutamate** |
   165|| **SLC25A13** | Citrin (aspartate/glutamate carrier) | c.1638_1660dup (p.Thr551fs); c.852_855del (p.Met285fs) | Adult-onset citrullinemia type II (CTLN2); failure to thrive; fatty liver | None |
   166|| **SLC25A15** | ORNT1 (ornithine transporter) | c.562C>T (p.Arg188*); c.365G>A (p.Arg122His) | HHH syndrome (hyperornithinemia, hyperammonemia, homocitrullinuria) | None |
   167|
   168|---
   169|
   170|## 5. Citric Acid Cycle (Krebs/TCA)
   171|
   172|| Gene | Enzyme | SNP / Variant | Clinical Association | Cofactor |
   173||------|--------|---------------|---------------------|----------|
   174|| **IDH1** | Isocitrate dehydrogenase 1 (cytosolic) | **p.Arg132His (c.395G>A)**; p.Arg132Cys; p.Arg132Ser | Glioma (most common); 2-hydroxyglutarate producer; ivosidenib target | **Magnesium** (or Mn²⁺) |
   175|| **IDH2** | Isocitrate dehydrogenase 2 (mitochondrial) | **p.Arg172Gln (c.515G>A)**; p.Arg172Lys; p.Arg140Gln | AML, gliomas; 2-HG producer; enasidenib target | **Magnesium** (or Mn²⁺) |
   176|| **SDHA** | Succinate dehydrogenase flavoprotein subunit A | p.Arg554Trp; p.Arg589Trp; p.Arg451Cys | Leigh syndrome; paraganglioma; GIST | **FAD** |
   177|| **SDHB** | Succinate dehydrogenase iron-sulfur subunit B | **p.Arg46Gln**; p.Cys101Tyr; p.Arg242His | Hereditary paraganglioma-pheochromocytoma syndrome (PGL4); GIST; RCC | **Iron-sulfur [2Fe-2S]** |
   178|| **SDHC** | Succinate dehydrogenase subunit C | p.Arg133*; p.Arg27* | PGL3; paraganglioma; head and neck tumors | None |
   179|| **SDHD** | Succinate dehydrogenase subunit D | **p.Trp43* (c.129G>A)**; p.Leu95Pro | PGL1; pheochromocytoma; parent-of-origin effect (maternal imprinting) | None |
   180|| **FH** | Fumarate hydratase | **p.His193Asp**; p.Leu464Valfs; p.Arg233* | Hereditary leiomyomatosis/renal cell cancer (HLRCC); aggressive RCC | **Iron** |
   181|| **OGDH** | Oxoglutarate dehydrogenase (E1) | c.2431C>T (p.Arg811*); c.1588C>T (p.Arg530Cys) | Dihydrolipoyl dehydrogenase deficiency-like; lactic acidosis | **Thiamine pyrophosphate**, **Lipoate**, **CoA**, **FAD**, **NAD** |
   182|| **ACO2** | Aconitase 2 (mitochondrial) | c.880A>G (p.Asn294Asp); c.1636C>T (p.Arg546Cys) | Optic neuropathy; cerebellar ataxia | **Iron-sulfur [4Fe-4S]** |
   183|| **CS** | Citrate synthase | c.1195G>A (p.Gly399Arg); c.880G>A (p.Gly294Arg) | Combined oxidative phosphorylation deficiency | None |
   184|| **MDH2** | Malate dehydrogenase 2 | c.484C>T (p.Arg162Trp) | Encephalopathy; lactic acidosis | None |
   185|
   186|---
   187|
   188|## 6. Lipid Metabolism
   189|
   190|| Gene | Enzyme / Receptor | Key SNP | Impact | Cofactor |
   191||------|-------------------|---------|--------|----------|
   192|| **APOE** | Apolipoprotein E | **ε2/ε3/ε4** (rs429358 T>C + rs7412 C>T) | ε4 carriers (10-15% AA): ↑ Alzheimer's 3-15x, CVD, ↓ statin response; ε2: type III hyperlipoproteinemia | None |
   193|| **LDLR** | LDL receptor | **c.1027G>A (p.Ala343Thr)**; c.682G>A (p.Gly228Arg); c.2054C>T (p.Pro685Leu) | Familial hypercholesterolemia; premature CAD; PCSK9 inhibitor responsive | **Calcium** (LDLRAP1 accessory) |
   194|| **PCSK9** | Proprotein convertase subtilisin/kexin type 9 | **p.Arg46Leu (c.137G>T)**; p.Gln554* (c.1660C>T) | Loss-of-function = low LDL; gain-of-function = FH; evolocumab target | None |
   195|| **HMGCR** | HMG-CoA reductase | **rs17238484** (intron); **rs3846662** (alternative splicing) | Statin response variability; LDL lowering efficacy | None |
   196|| **CYP7A1** | Cholesterol 7α-hydroxylase | **rs3808607** (-204A>C promoter); rs1125226 | ↓ Bile acid synthesis; gallstones; hyperlipidemia | **Iron** |
   197|| **FADS1** | Fatty acid desaturase 1 (Δ5-desaturase) | **rs174546** (intronic); rs174548; rs174553 | Δ5 desaturation efficiency; DHA/EPA synthesis; atopy risk | **Iron** |
   198|| **FADS2** | Fatty acid desaturase 2 (Δ6-desaturase) | **rs174575**; rs174583; rs2727270 | Δ6 desaturation; ARA synthesis; ADHD associations | **Iron** |
   199|| **ELOVL2** | Elongase of very-long-chain fatty acids 2 | **rs2236212**; rs9526989 | DHA elongation; age-related methylation (epigenetic clock) | None |
   200|| **ELOVL5** | Elongase of very-long-chain fatty acids 5 | **rs2397142**; rs934199 | ARA/EPA elongation; fatty liver disease risk | None |
   201|| **ALOX5** | 5-lipoxygenase | **rs4948672** (SP1 binding site); rs2228065 | Leukotriene synthesis; asthma drug response; zileuton efficacy | **Iron** |
   202|| **ALOX5AP** | 5-lipoxygenase-activating protein | **rs4076128**; rs9315050 | Leukotriene production; cardiovascular inflammation | None |
   203|| **LPL** | Lipoprotein lipase | **p.Asp36Asn (c.106G>A)**; p.Ala288Thr; p.Gly188Glu | Hypertriglyceridemia or LPL deficiency; pancreatitis risk | None |
   204|| **CETP** | Cholesteryl ester transfer protein | **rs708272** (TaqIB); **rs5882** (I405V); rs12149545 | HDL levels; ε4 carriers may not benefit from CETP inhibitors | None |
   205|| **ANGPTL3** | Angiopoietin-like 3 | **p.Gln218* (c.652C>T)**; p.Leu222*; rs11207977 | FH-like phenotype; triglyceride/HDL regulation; evinacumab target | None |
   206|| **ANGPTL4** | Angiopoietin-like 4 | **p.Glu130Gln (c.388G>C)**; p.Ser396* | Triglyceride levels; cancer metastasis associations | None |
   207|
   208|---
   209|
   210|## 7. Amino Acid Metabolism — Clinically Relevant
   211|
   212|| Gene | Enzyme | Key SNP / Variant | Pathway / Disorder | Cofactor |
   213||------|--------|-------------------|-------------------|----------|
   214|| **G6PD** | Glucose-6-phosphate dehydrogenase | **G6PD A- (rs1050828 c.202G>A, p.Val68Met)**; **G6PD Mediterranean (rs5030868 c.563C>T, p.Ser188Phe)**; rs137852314 | X-linked; hemolysis with oxidative stress (fava beans, sulfonamides, primaquine); malaria resistance | **NADP** |
   215|| **PAH** | Phenylalanine hydroxylase | **p.Arg408Trp (c.1222C>T)**; p.Ile65Thr; p.Arg261Gln | PKU; BH4-responsive (up to 50% of patients); sapropterin dihydrochloride | **BH4**, **Iron** |
   216|| **GCH1** | GTP cyclohydrolase 1 | **p.Thr631Met (c.1892C>T)**; p.Arg184His; deletions | Dopa-responsive dystonia (Segawa syndrome); atypical PKU | **Zinc**, **Magnesium**, **BH4** |
   217|| **PTS** | 6-pyruvoyl-tetrahydropterin synthase | **p.Arg16Cys (c.46C>T)**; p.Arg134Cys | BH4 synthesis defect; atypical PKU | None |
   218|| **QDPR** | Quinoid dihydropteridine reductase | **p.Arg147Trp (c.439C>T)**; p.Arg225His | BH4 recycling defect; atypical PKU | **NADH** |
   219|| **PCBD1** | Pterin-4α-carbinolamine dehydratase | **p.Arg135Pro (c.404G>C)** | Mild transient hyperphenylalaninemia | None |
   220|| **BCKDHA** | Branched-chain α-ketoacid DH E1α | **p.Arg170Trp (c.508C>T)**; p.Tyr368Asn | Maple syrup urine disease (MSUD); classic presentation | **Thiamine**, **Lipoate**, **CoA**, **FAD**, **NAD** |
   221|| **BCKDHB** | Branched-chain α-ketoacid DH E1β | **p.Arg183Trp (c.547C>T)**; p.Ala298Val | MSUD; thiamine-responsive MSUD in some | **Thiamine**, **Lipoate**, **CoA**, **FAD**, **NAD** |
   222|| **DBT** | Dihydrolipoyl transacylase (E2) | **p.Arg301Cys (c.901C>T)**; p.Pro375Leu | MSUD; intermediate severity | **Lipoate** |
   223|| **DLD** | Dihydrolipoyl dehydrogenase (E3) | **p.Arg447Gly (c.1339A>G)**; p.Ile280Arg | MSUD + lipoic acid defect; severe Leigh-like syndrome | **FAD**, **NAD** |
   224|| **MAT1A** | Methionine adenosyltransferase I/III | **p.Arg244His (c.731G>A)**; p.Ala259Val | Hypermethionemia; liver disease; hepatocellular carcinoma risk | **Magnesium** |
   225|| **AHCY** | S-adenosylhomocysteine hydrolase | **p.Arg49Cys (c.145C>T)**; p.Tyr143Cys | Methionine accumulation; myopathy; developmental delay | None |
   226|| **SAHH** | (same as AHCY) | | | None |
   227|| **GATM** | Glycine amidinotransferase | **p.Trp149* (c.447G>A)**; p.Arg386* | Guanidinoacetate methyltransferase deficiency precursor | None |
   228|| **GAMT** | Guanidinoacetate methyltransferase | **p.Arg270* (c.808C>T)**; p.Trp21* | GAMT deficiency; creatine deficiency syndrome; epilepsy | **SAM** |
   229|| **SLC6A8** | Creatine transporter | **c.1481C>T (p.Thr494Met)**; c.1202G>A (p.Arg401His) | Creatine transporter deficiency; X-linked; developmental delay | None |
   230|| **SOD1** | Superoxide dismutase 1 (Cu/Zn) | **p.Ala4Val (c.11C>T)**; **p.Gly93Ala (c.278G>C)** | ALS (20% familial); oxidative stress; short half-life variants | **Copper/Zinc** |
   231|| **SOD2** | Superoxide dismutase 2 (Mn) | **p.Ala16Val (rs4880 c.47T>C)**; rs2758331 | Val/Val = less efficient mitochondrial targeting; cancer risk variable | **Manganese** |
   232|| **GPX1** | Glutathione peroxidase 1 | **p.Pro200Leu (rs1050450 c.599C>T)**; rs1800668 | Reduced enzyme activity; cancer risk associations; selenium responsive | **Selenium** |
   233|| **GPX4** | Glutathione peroxidase 4 (phospholipid hydroperoxide) | rs713041; rs2074451 | Membrane lipid peroxidation protection; ferroptosis regulation | **Selenium** |
   234|| **NQO1** | NAD(P)H quinone oxidoreductase 1 | **p.Pro187Ser (rs1800566 c.559C>T)**; **p.Arg139Trp (rs1131341)** | Null/null = ↓ detox of quinones; benzene toxicity; cancer susceptibility | **FAD** |
   235|| **PON1** | Paraoxonase 1 | **p.Gln192Arg (rs662 c.575A>G)**; **p.Leu55Met (rs854560)**; rs705379 | Q192R = arylesterase/paraoxonase activity tradeoff; CVD protection; OP detox | **Calcium** |
   236|| **PON2** | Paraoxonase 2 | **p.Ala148Gly (rs12026)**; rs7493 | Cellular antioxidant; type 2 diabetes associations | None |
   237|| **CAT** | Catalase | **p.Ala16Val (rs7943316)**; rs1001179; rs769217 | Hydrogen peroxide detoxification; vitiligo; aging | **Heme** (Iron) |
   238|
   239|---
   240|
   241|## 8. Oxalate Metabolism & Glyoxylate Pathway
   242|
   243|Oxalate is an end-product of metabolism with no further catabolism in humans. Primary hyperoxalurias (PH) are inborn errors causing oxalate overproduction and renal stone disease.
   244|
   245|### Key Enzymes & Transporters
   246|| Gene | Enzyme | SNP / Variant | Function | Cofactors | Clinical Notes |
   247||------|--------|---------------|----------|-----------|----------------|
   248|| **AGXT** | Alanine-glyoxylate aminotransferase | **p.Gly170Arg (c.508G>A)** — G170R (most common); **p.Phe152Ile (c.454T>A)**; p.Ile244Thr | Converts glyoxylate → glycine (peroxisomal) | **Vitamin B6** (PLP) | PH Type I; G170R ~50% B6-responsive; European ancestry hotspot |
   249|| **GRHPR** | Glyoxylate reductase/hydroxypyruvate reductase | **c.864delG (p.Ala289fs)**; c.403dupG (p.Asp135fs) | Converts glyoxylate → glycolate; hydroxypyruvate → glycerate | **NADPH** | PH Type II; B6 non-responsive; recessive |
   250|| **HOGA1** | 4-hydroxy-2-oxoglutarate aldolase | **c.700-5T>G** (splice); c.834_834+1del (splice) | Cleaves 4-OH-2-oxoglutarate → pyruvate + glyoxylate | None (lyase) | PH Type III; milder; often resolves post-transplant |
   251|| **SLC26A1** | Sulfate/oxalate transporter Sat1 | rs142936877; rs141125087 | Oxalate secretion into urine | None | Modulates urinary oxalate; modifier of PH phenotype |
   252|| **SLC26A6** | Chloride/oxalate exchanger CFEX | **rs115686933**; rs3818246; rs478055 | Oxalate secretion in intestine/kidney | None | Calcium oxalate stone risk; intestinal oxalate absorption |
   253|| **LDHA** | Lactate dehydrogenase A | **p.Gln28Arg (c.83A>G)**; rs200455948 | Glyoxylate → oxalate (minor overflow pathway) | None | Contributes to oxalate when glyoxylate pools overflow |
   254|| **MUT** | Methylmalonyl-CoA mutase | **p.Gln174* (c.520C>T)**; p.Arg93Cys (c.277C>T) | Propionate metabolism; prevents glyoxylate accumulation | **B12** (adenosylcobalamin) | Methylmalonic aciduria; secondary oxalate risk |
   255|| **AGXT2** | Mitochondrial 2-aminoadipate aminotransferase | rs37370 (common variant); rs16868208 | Mitochondrial glyoxylate metabolism; modifier | **PLP** (B6) | Minor PH modifier; less severe than AGXT |
   256|
   257|### Oxalate Pathway Flow
   258|```
   259|Glycine ↔ Glyoxylate ─AGXT/PLP─→ Alanine
   260|      ↓
   261|  Glycolate (GRHPR/NADPH)
   262|      ↓
   263|  Oxalate (irreversible end-product)
   264|      ↓
   265|  Urinary excretion (or Ca/Mg precipitation → stones)
   266|
   267|Hydroxyproline ─HOGA1─→ Pyruvate + Glyoxylate (prevents overflow)
   268|```
   269|
   270|### Nutritional Modulators
   271|| Factor | Effect | Mechanism |
   272||--------|--------|-----------|
   273|| **Vitamin B6** (pyridoxine/PLP) | ↓ Urinary oxalate | AGXT cofactor; enhances glyoxylate → glycine conversion |
   274|| **Magnesium** | ↓ Stone formation | Inhibits calcium oxalate crystallization; Mg-oxalate more soluble |
   275|| **Calcium** (dietary) | ↓ Stone risk (counterintuitive) | Binds oxalate in gut, prevents absorption |
   276|| **Vitamin C** (>1g/day) | ↑ Urinary oxalate | Ascorbate → oxalate via dehydroascorbate |
   277|| **High oxalate foods** | ↑ Urinary oxalate | Spinach, beets, nuts, chocolate, tea, rhubarb |
   278|| **Probiotics** (O. formigenes) | Variable | Oxalate-degrading gut bacteria depleted by antibiotics |
   279|
   280|---
   281|
   282|## 9. Vitamin C (Ascorbate) Transport & Recycling
   283|
   284|Humans cannot synthesize ascorbate (lost GULO enzyme). Transport and recycling are critical for antioxidant status.
   285|
   286|### Transport Proteins
   287|| Gene | Protein | Key SNP | Function | Tissue |
   288||------|---------|---------|----------|--------|
   289|| **SLC23A1** | SVCT1 (sodium-dependent vitamin C transporter 1) | **rs33972313 (p.Pro264Leu)**; rs6596473; rs1776964 | Ascorbate uptake (high capacity, low affinity) | Intestine, kidney, liver |
   290|| **SLC23A2** | SVCT2 (sodium-dependent vitamin C transporter 2) | **rs1279683**; **rs1414747**; rs2619681 | Ascorbate uptake (high affinity) | Brain, eye, placenta, adrenal |
   291|| **SLC2A1** | GLUT1 | **rs841853**; rs1385129; rs3763980 | Dehydroascorbate (DHA) uptake | Ubiquitous (DHA recycled to AA intracellularly) |
   292|| **SLC2A3** | GLUT3 | rs11603773; rs2674737 | DHA uptake | Neurons, high-demand tissues |
   293|
   294|### Recycling Enzymes
   295|| Gene | Enzyme | Key SNP | Function | Cofactors | Clinical Notes |
   296||------|--------|---------|----------|-----------|----------------|
   297|| **GSR** | Glutathione reductase | **rs1002149**; **rs2253409**; rs4125434 | Maintains GSH pool for redox cycling | **FAD**, **NADPH** | DHA reduction requires GSH; oxidative stress susceptibility |
   298|| **TXNRD1** | Thioredoxin reductase 1 | **rs4964728**; rs11938412 | Alternative DHA reduction pathway (cytosolic) | **FAD**, **NADPH**, **Selenium** | Selenoprotein; Se status affects recycling |
   299|| **TXNRD2** | Thioredoxin reductase 2 | **rs9500466**; rs2074448 | Mitochondrial DHA reduction | **FAD**, **NADPH**, **Selenium** | Mitochondrial antioxidant defense |
   300|| **GLRX1** | Glutaredoxin 1 (cytosolic) | rs3811692; rs10483924 | Reduce DHA → AA using GSH | **Iron** (Fe-S cluster) | Cytosolic redox regulation |
   301|| **GLRX2** | Glutaredoxin 2 (mitochondrial) | rs12294133; rs11604820 | Mitochondrial DHA reduction | **Iron** (Fe-S cluster) | Mitochondrial redox regulation |
   302|| **AKR1A1** | Aldose reductase | **rs123489**; rs157002 | DHA reduction (minor pathway) | None | Polyol pathway overlap |
   303|| **DHCR24** | 3β-hydroxysterol-Δ24-reductase | **rs2260862**; rs2260863 | DHA reduction (neuroprotective) | None | Anti-apoptotic; AD associations |
   304|
   305|### Vitamin C Metabolic Flow
   306|```
   307|Dietary Ascorbate ─SLC23A1/2─→ Intracellular AA
   308|                                        ↓ Oxidative stress
   309|                               Dehydroascorbate (DHA)
   310|                                        ↓
   311|                           ┌────────────┴────────────┐
   312|                           ↓                         ↓
   313|                      GSH/Glutaredoxin          Thioredoxin/Seleno
   314|                           ↓                         ↓
   315|                      Ascorbate (recycled) ←───────┘
   316|```
   317|
   318|### Key SNPs & Functional Impacts
   319|| Variant | Effect | Clinical Relevance |
   320||---------|--------|-------------------|
   321|| **SLC23A1 rs33972313 (p.Pro264Leu)** | ↓ Intestinal uptake | Lower plasma vitamin C; scurvy risk with marginal intake; European specific |
   322|| **SLC23A2 rs1279683** | Impaired tissue uptake | Poor ascorbate penetration to CNS, eye, adrenal; oxidative stress susceptibility |
   323|| **GSR rs1002149** | Reduced GSH regeneration | Impaired DHA recycling; oxidative stress susceptibility; cardiovascular risk |
   324|| **TXNRD2 rs9500466** | Impaired thioredoxin system | Selenium-dependent vitamin C recycling compromised; mitochondrial dysfunction |
   325|
   326|---
   327|
   328|## 10. Cofactor / Vitamin & Mineral Processing Enzymes
   329|
   330|| Gene | Cofactor | Key SNP / Variant | Functional Note | Mineral Dependent |
   331||------|----------|-------------------|-----------------|-------------------|
   332|| **GC** | Vitamin D binding protein | **rs2282679** (intron 12); **rs7041** (p.Asp416Glu Gc1f/Gc1s); **rs4588** (p.Thr420Lys Gc2) | Bioavailable 25-OH-D levels vary; Gc1f = highest; Gc2 = lowest | No |
   333|| **CYP2R1** | Vitamin D 25-hydroxylase | **rs10741657** (5' near gene); **rs2060793**; rs1562952 | Affects 25-OH-D levels; hypovitaminosis D risk | **Iron** (heme-thiolate) |
   334|| **CYP27B1** | Vitamin D 1α-hydroxylase | **c.2T>C (p.Met1Thr)**; c.1182_1186dup (p.Ile396fs) | Autoimmune polyendocrine syndrome; renal activation defect | **Iron** |
   335|| **VDR** | Vitamin D receptor | **FokI** | rs2228570 c.2T>C (p.Met1Thr) | Protein length variant; F allele = 3 amino acids shorter; ↑ transcriptional activity | F/F = highest VDR activity; f/f = reduced activity; bone density, immune response, cancer risk | No |
   336|| **VDR** | | **BsmI** | rs1544410 c.1024+283G>A (Intron 8) | Affects mRNA stability | B allele = more stable mRNA; linked to BMD; haplotype with TaqI | No |
   337|| **VDR** | | **TaqI** | rs731236 c.1056T>C (p.Ser352Ser, synonymous) | Affects mRNA translation efficiency | t allele = reduced translation; osteoporosis risk; vitamin D responsiveness | No |
   338|| **VDR** | | **ApaI** | rs7975232 c.1024+16C>A (Intron 8) | Splicing regulation | A allele affects intron retention; linked to autoimmune disease | No |
   339|| **VDR** | | **Poly(A)** | 3'UTR variable repeat | mRNA stability | Longer repeats = less stable mRNA; variable vitamin D response | No |
   340|| **VDR** | | **Cdx2** | rs11568820 c.-373A>G (Promoter) | Transcription factor binding | G allele = stronger promoter; ↑ intestinal VDR expression; calcium absorption | No |
   341|| **CYP24A1** | Vitamin D 24-hydroxylase (catabolism) | **rs2248137**; rs2762939; rs6013897 | Hypercalcemia risk; 25-OH-D catabolism rate | **Iron** |
   342|| **DHCR7** | 7-dehydrocholesterol reductase | **rs12785878** (intron); rs7944926; rs3829251 | Vitamin D3 synthesis from 7-DHC; Lichtenstein-Knorr syndrome | **NADPH** |
   343|| **TCN2** | Transcobalamin II | **c.776C>G (p.Pro259Arg rs1801198)**; rs9606756 | B12 transport; functional B12 deficiency despite normal serum B12 | No |
   344|| **FUT2** | Fucosyltransferase 2 | **c.428G>A (p.Trp143* rs601338)** "non-secretor"; rs492602 | Gut B12 synthesis/absorption; microbiome composition; IBD risk | **Manganese** |
   345|| **MMAA** | Methylmalonic aciduria cbIA type | **p.Arg145* (c.433C>T)**; p.Leu309Val | B12 trafficking to MUT; methylmalonic aciduria | **B12** |
   346|| **MMAB** | Methylmalonic aciduria cobalamin B | **p.Arg143Trp (c.427C>T)**; p.Arg190Trp | B12 adenosylcobalamin synthesis defect | **B12** |
   347|| **MMACHC** | Methylmalonic aciduria CblC | **c.271dupA (p.Arg91fs)**; **c.394C>T (p.Arg132*)** | Combined methylmalonic aciduria/homocystinuria; hydroxocobalamin responsive | **B12** |
   348|| **MTRR** | Methionine synthase reductase | **c.524C>T (p.Ile175Met rs1801394)**; c.66A>G (p.Ile22Met) | B12 functional deficiency; NTD risk; homocysteine elevation | **FAD**, **NADPH** |
   349|| **ALPL** | Alkaline phosphatase, tissue-nonspecific | **c.571G>A (p.Glu191Lys)**; c.1559delT; p.Asp377Val | Hypophosphatasia; B6 vitamer PP (PLP) depletion; rickets | **Zinc**, **Magnesium** |
   350|| **ATP7A** | Copper-transporting ATPase (Menkes) | **p.Ser637Leu**; c.4006-2A>G; large deletions | Menkes disease; copper deficiency; kinky hair; fatal | **Copper** |
   351|| **ATP7B** | Copper-transporting ATPase (Wilson) | **p.His1069Gln (c.3207C>A)** (European); **p.Arg778Leu** (Asian); p.Thr935Met | Wilson disease; copper toxicity; liver/neuro; penicillamine/trientine/zinc | **Copper** |
   352|| **SLC31A1 (CTR1)** | Copper transporter 1 | rs1098161; rs12686307 | Intestinal copper uptake; Wilson's modifier | **Copper** |
   353|| **SLC30A2** | Zinc transporter 2 | **c.887G>A (p.Arg296His)**; c.1015C>T | Zinc deficiency in lactation; transient neonatal zinc deficiency | **Zinc** |
   354|| **SLC39A4** | ZIP4 zinc transporter | **c.1315C>T (p.Gln439*)**; c.826+1G>A | Acrodermatitis enteropathica; severe zinc deficiency; zinc responsive | **Zinc** |
   355|| **TRPM6** | Magnesium channel | **c.3208C>T (p.Arg1070Trp)**; c.3408+5G>A | Hypomagnesemia with secondary hypocalcemia; seizures | **Magnesium** |
   356|| **TRPM7** | Magnesium channel | **rs8042919**; rs2274925; rs3783476 | Immune/autonomic dysfunction; Mg absorption modifier | **Magnesium**, **Zinc** |
   357|| **CNNM2** | Cyclin M2 magnesium transporter | **rs3740393**; rs2274924 | Serum magnesium levels; blood pressure regulation | **Magnesium** |
   358|| **SLC40A1** | Ferroportin | **p.Asp181Asn (c.541G>A)**; **p.Val162del (c.485_487del)** | Hemochromatosis type IV; ferroportin disease; macrophage iron loading | **Iron** |
   359|| **HFE** | Hemochromatosis protein | **p.Cys282Tyr (rs1800562)**; **p.His63Asp (rs1799945)** | Hereditary hemochromatosis; C282Y homozygote = penetrance variable | **Iron** |
   360|| **HAMP** | Hepcidin antimicrobial peptide | **c.233G>A (p.Arg77*)**; c.-153C>T | Juvenile hemochromatosis; severe iron overload | **Iron** |
   361|| **HJV** | Hemojuvelin | **c.959G>T (p.Gly320Val)**; p.Ile281Thr | Juvenile hemochromatosis; BMP signaling defect | **Iron** |
   362|| **TFR2** | Transferrin receptor 2 | **p.Ala289Asp (c.866C>A)**; p.Met172Lys | Hemochromatosis type 3; transferrin-mediated iron uptake | **Iron** |
   363|| **SFXN4** | Sideroflexin 4 | **c.875G>A (p.Arg292His)** | Mitochondrial iron homeostasis; sideroblastic anemia | **Iron** |
   364|| **GLRX5** | Glutaredoxin 5 | **c.294A>G (p.Ala98=; affects splicing)** | Sideroblastic anemia; iron-sulfur cluster biogenesis | **Iron** |
   365|| **MOCOS** | Molybdenum cofactor sulfurase | **p.Arg802* (c.2404C>T)** | Combined sulfite oxidase/xanthine dehydrogenase deficiency | **Molybdenum** |
   366|| **MOCS1** | Molybdenum cofactor synthesis 1 | Various | Molybdenum cofactor deficiency; severe neonatal encephalopathy | **Molybdenum** |
   367|| **MOCS2** | Molybdenum cofactor synthesis 2 | c.19_20del (p.Leu7fs) | Molybdenum cofactor deficiency type B | **Molybdenum** |
   368|| **SUOX** | Sulfite oxidase | **c.1186G>A (p.Arg396Cys)**; c.1391G>A | Sulfite toxicity; molybdenum cofactor disorder; seizures | **Molybdenum** (Moco), **Iron** (heme) |
   369|| **XDH** | Xanthine dehydrogenase | Various mutations | Xanthinuria; molybdenum cofactor disorder; kidney stones | **Molybdenum** (Moco), **Iron-Sulfur** |
   370|| **AOC3** | Copper amine oxidase (VAP-1) | rs2070586; rs1046320 | Inflammation; vascular adhesion; diabetes associations | **Copper**, **TPQ cofactor** |
   371|
   372|---
   373|
   374|## 11. Mineral Cofactor Summary by Element
   375|
   376|| Mineral | Key Enzymes/Proteins | Metabolic Role | Deficiency/Excess Impact |
   377||---------|---------------------|----------------|-------------------------|
   378|| **Magnesium** | >300 enzymes (kinases, polymerases, ATPases) | ATP complexation, kinase activation, DNA stability | Stones (CaOx), arrhythmia, migraines, insulin resistance |
   379|| **Zinc** | SOD1, DNA polymerases, metallothioneins | Antioxidant, DNA synthesis, immune function | Dermatitis, immune dysfunction, poor wound healing |
   380|| **Iron** | CYP450s, TCA cycle enzymes, heme synthesis | Oxygen transport, electron transport, detox | Anemia (def); hemochromatosis, oxidative damage (excess) |
   381|| **Copper** | SOD1, cytochrome c oxidase, lysyl oxidase | Antioxidant, energy, collagen crosslinking | Menkes (def); Wilson's, oxidative stress (excess) |
   382|| **Manganese** | SOD2, arginase, pyruvate carboxylase | Mitochondrial antioxidant, gluconeogenesis | Manganism (neurotoxicity), poor glycemic control |
   383|| **Selenium** | GPX1-4, TXNRD1-3, deiodinases | Antioxidant, thyroid hormone conversion | Kashin-Beck disease (def); selenosis (excess) |
   384|| **Molybdenum** | Sulfite oxidase, xanthine dehydrogenase, aldehyde oxidase | Sulfur metabolism, purine catabolism | Sulfite sensitivity, xanthinuria |
   385|| **Calcium** | (Regulatory) | Second messenger, bone structure, exocytosis | Stones (if hypercalciuria), osteoporosis |
   386|| **Chromium** | Chromodulin (low molecular weight) | Glucose tolerance factor (controversial) | Impaired glucose tolerance |
   387|| **Boron** | (Estrogen, vitamin D metabolism) | Steroid hormone metabolism, bone health | Arthritis, cognitive decline |
   388|
   389|---
   390|
   391|## 12. Neurotransmitter / Biogenic Amine Metabolism
   392|
   393|### Monoamine Oxidases (MAOA, MAOB)
   394|| Gene | Enzyme | Key SNP | cDNA/Protein Change | Functional Effect | Clinical Notes | Cofactor |
   395||------|--------|---------|---------------------|-------------------|----------------|----------|
   396|| **MAOA** | Monoamine oxidase A | **rs6323** | c.891T>C (p.Arg297Arg, synonymous) | Affects mRNA stability; G allele = ↓ expression | "Warrior gene" controversy; aggression/impulsivity associations (weak); antidepressant response | **FAD** |
   397|| **MAOA** | | **5'UTR VNTR** | 30bp repeat (2R, 3R, 4R, 5R) | 3.5R/4R = ↓ expression; 5R = ↑ expression | 3R ("low activity") associated with aggression under stress; MAO inhibitors (phenelzine) | **FAD** |
   398|| **MAOA** | | **rs909525** | Promoter region | Transcriptional regulation | Haplotype with VNTR affects expression levels | **FAD** |
   399|| **MAOA** | | **rs2064070** | Intronic | Splicing regulation | Associated with major depression | **FAD** |
   400|| **MAOB** | Monoamine oxidase B | **rs1799836** | Intron 13 | T allele = ↓ enzyme activity | Parkinson's disease protection; dopamine preservation; selegiline response | **FAD** |
   401|| **MAOB** | | **rs6651806** | 3'UTR | Affects mRNA stability | Associated with PD age of onset | **FAD** |
   402|| **MAOB** | | **rs2311013** | Promoter | Transcriptional regulation | Smoking behavior associations | **FAD** |
   403|
   404|### Catechol-O-Methyltransferase (COMT) - Extended
   405|| Gene | SNP | cDNA Change | Protein Change | Function | Clinical Impact | Cofactor |
   406||------|-----|-------------|----------------|----------|-----------------|----------|
   407|| **COMT** | **rs4680** | c.472G>A | p.Val158Met (Val/Met) | **Met = 3-4x ↓ activity**; ↓ dopamine clearance | Met/Met = ↑ pain sensitivity, ↓ stress resilience, better prefrontal cognition; Val/Val = ↑ pain tolerance, better stress resilience | **SAM**, **Magnesium** |
   408|| **COMT** | **rs6267** | c.408C>G | p.Leu136Leu (synonymous) | Affects mRNA stability | Haplotype with rs4680; modifies Val158Met effect | **SAM**, **Magnesium** |
   409|| **COMT** | **rs4818** | c.186C>T | p.Asn62Asn (synonymous) | Affects RNA folding | Part of COMT haplotypes (HPS: high pain sensitivity); epistatic with rs4680 | **SAM**, **Magnesium** |
   410|| **COMT** | **rs4633** | c.186C>T | Synonymous | Haplotype marker | Part of haplotype blocks with rs4680 | **SAM**, **Magnesium** |
   411|| **COMT** | **rs6269** | c.-487C>G | Promoter | Transcriptional regulation | Affects baseline COMT expression levels | **SAM**, **Magnesium** |
   412|| **COMT** | **rs165599** | 3'UTR | Affects mRNA stability | G allele = ↓ expression | Schizophrenia association; antipsychotic response | **SAM**, **Magnesium** |
   413|
   414|#### COMT Haplotypes (Clinical Combinations)
   415|| Haplotype | rs6269 | rs4633 | rs4818 | rs4680 | Activity | Clinical Notes |
   416||-----------|--------|--------|--------|--------|----------|----------------|
   417|| **HPS** (High Pain Sensitivity) | G | C | C | Met | Lowest | ↑ Pain sensitivity; ↓ stress resilience; better executive function |
   418|| **LPS** (Low Pain Sensitivity) | A | T | T | Val | Highest | ↓ Pain sensitivity; ↑ stress resilience; ADHD risk |
   419|| **APS** (Average Pain Sensitivity) | Mixed | Mixed | Mixed | Val/Met | Intermediate | Standard response patterns |
   420|
   421|### Dopamine & Serotonin Synthesis
   422|| Gene | Enzyme | Key SNP | Effect | Clinical Notes | Cofactor |
   423|| **DDC** | DOPA/Aromatic L-amino acid decarboxylase | **rs1451371**; rs3757472; rs927796 | Dopamine/serotonin synthesis; antihypertensive drug response | **PLP** (B6) |
   424|| **DDC** | (rare mutations) | **p.Arg285His**; p.Arg302Trp; c.1077_1078del | AADC deficiency; oculogyric crises; hypotonia; B6 responsive in some | **PLP** (B6) |
   425|| **TH** | Tyrosine hydroxylase | **p.Thr463Met (rs11042938)**; p.Arg233His; c.698G>A | Dopamine synthesis; TH deficiency; dopa-responsive dystonia | **Iron** |
   426|| **TPH1** | Tryptophan hydroxylase 1 (peripheral) | **rs1800532 (A218C)**; **rs1799913 (A779C)**; rs211105 | ↓ Serotonin synthesis; depression associations; SSRI response variable | **Iron** |
   427|| **TPH2** | Tryptophan hydroxylase 2 (neuronal) | **rs7305115**; **rs4570625**; rs11178997 | Brain serotonin synthesis; depression; suicide risk; anxiety | **Iron** |
   428|| **AANAT** | Arylalkylamine N-acetyltransferase | **rs3760138**; rs4238989 | Melatonin synthesis; delayed sleep phase; seasonal affective disorder | **Acetyl-CoA** |
   429|| **ASMT** | Acetylserotonin methyltransferase (HIOMT) | **rs4446909**; **rs5989681** | Melatonin synthesis; delayed sleep phase syndrome | **SAM** |
   430|| **GCH1** | GTP cyclohydrolase 1 | **p.Thr635Met (rs8007267)**; rs10483639 | BH4 synthesis; dopa-responsive dystonia; pain sensitivity (GTPCH haplotype) | **Zinc**, **BH4** |
   431|| **PCBD1** | Pterin-4α-carbinolamine dehydratase | rs381751; rs1718303 | BH4 recycling; transient hyperphenylalaninemia; cofactor for TH/TPH | None |
   432|| **PNMT** | Phenylethanolamine N-methyltransferase | **rs876493**; rs5630 | Epinephrine synthesis from norepinephrine; blood pressure regulation | **SAM** |
   433|| **SLC6A3 (DAT1)** | Dopamine transporter | **3'UTR VNTR (40bp repeat)**; **rs28363170 (9-repeat/10-repeat)** | 10-repeat = ↑ expression; ADHD risk; stimulant response | None |
   434|| **SLC6A4 (SERT)** | Serotonin transporter | **5-HTTLPR (L/S promoter)**; **rs25531**; rs2020934 | L/L = ↑ expression; S/S = ↓ expression; depression; SSRIs response | None |
   435|| **SLC18A2 (VMAT2)** | Vesicular monoamine transporter 2 | rs363276; rs363333; rs363387 | Vesicular packaging; Parkinson's; tardive dyskinesia risk | None |
   436|
   437|---
   438|
   439|## 13. Heme & Porphyrin Metabolism
   440|
   441|| Gene | Enzyme | SNP / Variant | Disorder | Trigger / Feature | Cofactor |
   442||------|--------|---------------|----------|-------------------|----------|
   443|| **ALAD** | δ-aminolevulinic acid dehydratase | **p.Lys59Asn (c.177G>C)**; p.Gly133Arg; c.427_428insAC | ALAD porphyria (rare); lead sensitivity | Lead exposure exacerbates | **Zinc** |
   444|| **HMBS** | Hydroxymethylbilane synthase (PBG deaminase) | **p.Arg149Trp (c.445C>T)**; **p.Arg173Trp (c.517C>T)**; c.1073dupA | Acute intermittent porphyria (AIP) — most common acute porphyria | Drugs (CYP inducers), fasting, hormones, infection | None |
   445|| **CPOX** | Coproporphyrinogen oxidase | **p.Asp400Asn (c.1198G>A)**; c.691-2A>G (splice); p.His327Arg | Hereditary coproporphyria (HCP) | Drugs, fasting, hormones; photosensitivity + neurovisceral | None |
   446|| **PPOX** | Protoporphyrinogen oxidase | **p.Arg232Trp (c.694C>T)**; p.Arg168Cys; c.1189_1190del | Variegate porphyria (VP) — South African founder | Photosensitivity + neurovisceral; acute attacks | None |
   447|| **FECH** | Ferrochelatase | **p.Met1? (c.-23T>G, erythroid promoter)**; p.Pro334Leu; c.315-48T>C (intron) | Erythropoietic protoporphyria (EPP) | Photosensitivity; liver failure risk; afamelanotide | **Iron** (substrate), **Zinc** |
   448|| **ALAS2** | Aminolevulinate synthase 2 (erythroid) | **p.Lys391Asn (c.1173G>C)**; p.Arg452Cys; c.1654_1663dup | X-linked sideroblastic anemia; iron overload; ringed sideroblasts | Pyridoxine responsive in some | **PLP** (B6) |
   449|| **UROS** | Uroporphyrinogen III synthase | **p.Arg232Trp (c.694C>T)**; p.Trt275*; c.1103_1104insT | Congenital erythropoietic porphyria (CEP) — Gunther disease | Severe photosensitivity; hemolytic anemia; bone marrow transplant | None |
   450|| **UROD** | Uroporphyrinogen decarboxylase | **p.Asp86Val (c.257A>T)**; p.Gly281Glu; c.662_663del | Porphyria cutanea tarda (PCT); familial PCT (f-PCT) | Photosensitivity; blistering; liver disease; iron | None |
   451|| **GATA1** | GATA binding protein 1 | Various X-linked mutations | X-linked cytopenia with dyserythropoiesis; porphyria associations | Hematologic abnormalities | **Zinc** (finger domains) |
   452|
   453|### Acute Porphyria Precipitating Drugs (Selected)
   454|| Drug Class | Examples | Mechanism |
   455||------------|----------|-----------|
   456|| Barbiturates | Phenobarbital, secobarbital | CYP450 inducers; ↑ ALA synthase |
   457|| Anticonvulsants | Phenytoin, carbamazepine, valproate | CYP inducers |
   458|| Sulfa antibiotics | TMP-SMX, sulfonamides | Porphyrinogenic |
   459|| Hormonal | Estrogens, progesterone | ↑ ALA synthase |
   460|| Anesthetics | Enflurane, ketamine | CYP induction |
   461|| Safe alternatives | Gabapentin, levetiracetam, acetaminophen | Preferred in acute porphyria |
   462|
   463|---
   464|
   465|## 14. Purine & Pyrimidine Metabolism
   466|
   467|Purines (adenine, guanine) and pyrimidines (cytosine, thymine, uracil) are synthesized de novo or salvaged. Disorders cause gout, immunodeficiency, or neurological disease.
   468|
   469|### Purine Synthesis & Salvage
   470|| Gene | Enzyme | Key SNP / Variant | Disorder / Effect | Cofactor |
   471||------|--------|-------------------|-------------------|----------|
   472|| **HPRT1** | Hypoxanthine-guanine phosphoribosyltransferase | **p.Asn194Ser (c.581A>G)**; p.Leu78Val; large deletions (300+ mutations) | Lesch-Nyhan syndrome (null); severe gout/self-injury; hyperuricemia | **PRPP**, **Magnesium** |
   473|| **PRPS1** | Phosphoribosyl pyrophosphate synthetase 1 | **p.Ile290Thr (c.869T>C)**; p.Leu128Ile; p.Asp52His | Gain-of-function = gout, deafness, neurodevelopmental delay; loss = Arts syndrome | **ATP**, **Magnesium** |
   474|| **APRT** | Adenine phosphoribosyltransferase | **p.Asp65Val (c.194A>T)**; p.Val120Met; p.Leu69Pro | APRT deficiency; 2,8-dihydroxyadeninuria; kidney stones; allopurinol responsive | **PRPP**, **Magnesium** |
   475|| **AMPD1** | AMP deaminase 1 | **c.34C>T (p.Gln12* rs17602729)** "C34T"; c.143G>A (p.Arg48His) | Exercise intolerance; myoadenylate deaminase deficiency; rhabdomyolysis risk | **Zinc** |
   476|| **ATIC** | 5-aminoimidazole-4-carboxamide ribonucleotide transformylase | **p.Arg396Cys (c.1186C>T)**; p.Leu417Pro | AICAR transformylase deficiency; neurological impairment; hepatomegaly | **10-formyl-THF** (folate) |
   477|| **MTHFD1** | (see One-Carbon) | **c.1958G>A (p.Arg653Gln rs2236225)** | Purine synthesis (10-formyl-THF); miscarriage; NTD risk | **NADP**, **Magnesium** |
   478|
   479|### Purine Catabolism & Uric Acid
   480|| Gene | Enzyme / Transporter | Key SNP | Effect | Cofactor |
   481||------|---------------------|---------|--------|----------|
   482|| **XDH** | Xanthine dehydrogenase/oxidase | **p.Arg228Cys (c.682C>T)**; p.Trp318*; c.2059_2060del | Xanthinuria (Type I); hypouricemia; xanthine kidney stones | **Molybdenum** (Moco), **FAD** |
   483|| **MOCS1** | Molybdenum cofactor synthesis 1 | Various | Combined xanthinuria + sulfite oxidase deficiency; severe encephalopathy | **Molybdenum** |
   484|| **SLC2A9** | GLUT9 (urate transporter) | **rs12498742 (p.Thr275Met)**; **rs11722228**; rs16890979 | Gout risk; uric acid levels; hyperuricemia; strongest GWAS signal | None |
   485|| **ABCG2** | ATP-binding cassette G2 | **rs2231142 (p.Gln141Lys)**; rs10011796; rs2725220 | Gout risk; allopurinol response; reduced urate excretion | **ATP** |
   486|| **UMOD** | Uromodulin (Tamm-Horsfall protein) | **p.Cys150Trp (c.450C>G)**; p.Gly366Val; p.Cys579Tyr | Familial juvenile hyperuricemic nephropathy (FJHN); gout; CKD; MCKD2 | **Calcium** (binding) |
   487|| **SLC17A1** | NPT1 (sodium-phosphate cotransporter) | **rs1165196 (p.Ile269Thr)**; rs1183201 | Urate excretion; gout risk | None |
   488|| **SLC22A12** | URAT1 | **p.Trp258* (c.774G>A)**; p.Arg90His; c.774G>A | Urate reabsorption; gout; response to probenecid, lesinurad | None |
   489|| **SLC22A11** | OAT4 | **rs17300741**; rs1156798 | Urate transport; gout modifier | None |
   490|| **SLC17A3** | NPT4 | **rs1165205**; rs13118256 | Urate excretion; gout; renal hypouricemia | None |
   491|| **RFX3** | Regulatory factor X3 | rs11720911; rs12229892 | Gout risk locus; transcriptional regulation | None |
   492|| **INHBC** | Inhibin βC | rs214815 | Gout risk; renal function associations | None |
   493|
   494|### Pyrimidine Metabolism
   495|| Gene | Enzyme | Key SNP / Variant | Disorder | Cofactor |
   496||------|--------|-------------------|----------|----------|
   497|| **DPYD** | Dihydropyrimidine dehydrogenase | **IVS14+1G>A (splice, *2A, rs3918290)**; **c.2846A>T (p.Asp949Val, *13)**; c.557A>G (p.His186Arg); c.703C>T (p.Arg235Trp) | 5-FU/capecitabine fatal toxicity (CPIC); pyrimidinemia; ~3% partial deficiency | **FAD**, **FMN**, **NADPH** |
   498|| **UMPS** | Uridine monophosphate synthetase | **p.Gln456* (c.1366C>T)**; p.Arg96His | Hereditary orotic aciduria; megaloblastic anemia; UMP responsive | None |
   499|| **CAD** | Carbamoyl-phosphate synthetase II | **p.Arg2024* (c.6070C>T)**; p.Glu1053Lys | Congenital disorder of glycosylation; seizures; developmental delay | **ATP**, **Glutamine**, **Magnesium** |
   500|| **DTYMK** | Deoxythymidylate kinase | **p.Ala57Thr (c.209G>A)**; p.Arg161Trp | Neurological impairment; immunodeficiency; mtDNA depletion | **ATP**, **Magnesium** |
   501|| **TK2** | Thymidine kinase 2 (mitochondrial) | **p.Arg172Trp (c.514C>T)**; p.Ile181Asn | Mitochondrial DNA depletion syndrome; myopathic form | **ATP**, **Magnesium** |
   502|| **RRM2B** | Ribonucleotide reductase p53-inducible | **p.Gln116* (c.346C>T)**; p.Arg341Trp | Mitochondrial DNA depletion; PEO; encephalomyopathic | **Iron** |
   503|| **TYMP** | Thymidine phosphorylase | **p.Gly12Ser (c.34G>A)**; p.Phe198Leu; p.Arg202Gln | MNGIE (mitochondrial neurogastrointestinal encephalomyopathy) | **Phosphate** |
   504|| **DGUOK** | Deoxyguanosine kinase | **p.Leu88Ser (c.263T>C)**; p.Arg142* | mtDNA depletion; hepatocerebral syndrome | **ATP**, **Magnesium** |
   505|
   506|### Purine/Pyrimidine Pathway Flow
   507|```
   508|De novo synthesis:
   509|Ribose-5-P → PRPP ─PRPS1/ATP─→ IMP → AMP/GMP ─HPRT1─→ Salvage
   510|                    ↓
   511|               Xanthine ─XDH/Mo─→ Uric acid ─SLC2A9/ABCG2─→ Excretion
   512|                    ↓
   513|              Hypoxanthine ─────────────────────────────┘
   514|```
   515|
   516|### 5-FU Toxicity Risk Alleles (CPIC Guidelines)
   517|| DPYD Variant | Activity | Clinical Action |
   518||--------------|----------|-----------------|
   519|| *1 (normal) | 100% | Standard dosing |
   520|| *2A (IVS14+1G>A) | 0% | Contraindicate 5-FU; strong DPYD deficiency |
   521|| *13 (p.Asp949Val) | <50% | Dose reduction required |
   522|| c.557A>G (p.His186Arg) | ~60% | Dose reduction |
   523|| HapB3 (rs75017182) | ~50% | Dose reduction |
   524|
   525|---
   526|
   527|## 15. Mitochondrial Fatty Acid β-Oxidation
   528|
   529|Critical for energy during fasting; defects cause hypoketotic hypoglycemia, metabolic crisis.
   530|
   531|| Gene | Enzyme | Key SNP / Variant | Disorder | Clinical Features | Cofactor |
   532||------|--------|-------------------|----------|-------------------|----------|
   533|| **ACADM** | Medium-chain acyl-CoA dehydrogenase (MCAD) | **c.985A>G (p.Lys329Glu)** — K329E (90% of alleles); c.199T>C (p.Tyr67His) | MCAD deficiency | Most common FAOD (1:15,000); hypoketotic hypoglycemia; sudden death | **FAD** |
   534|| **ACADVL** | Very-long-chain acyl-CoA dehydrogenase (VLCAD) | **c.848T>C (p.Val283Ala)**; c.553G>A (p.Gly185Arg); c.1532G>A (p.Arg511His) | VLCAD deficiency | Cardiomyopathy; rhabdomyolysis; hypoglycemia | **FAD** |
   535|| **ACADL** | Long-chain acyl-CoA dehydrogenase (LCAD) | **c.380T>C (p.Met127Thr)**; p.Arg243His | LCAD deficiency | Cardiomyopathy; hepatic dysfunction (rare) | **FAD** |
   536|| **ACADS** | Short-chain acyl-CoA dehydrogenase (SCAD) | **c.625G>A (p.Gly209Ser)**; c.511C>T (p.Arg171Trp) | SCAD deficiency | Developmental delay; myopathy; often asymptomatic biochemical markers | **FAD** |
   537|| **HADHA** | Trifunctional protein α-subunit (LCHAD) | **c.1528G>C (p.Glu510Gln)** — E510Q; p.Phe247Leu | LCHAD deficiency | Hypoglycemia; cardiomyopathy; peripheral neuropathy; pigmentary retinopathy | **NAD** |
   538|| **HADHB** | Trifunctional protein β-subunit | **c.1172C>G (p.Thr391Arg)**; p.Arg252His | MTP deficiency | Similar to LCHAD; often more severe; early mortality | **NAD** |
   539|| **CPT1A** | Carnitine palmitoyltransferase IA | **c.1436C>T (p.Pro479Leu)** — P479L (Arctic variant); c.2129G>A (p.Gly710Glu) | CPT1A deficiency | Hypoketotic hypoglycemia; hepatomegaly; normal acylcarnitines | None |
   540|| **CPT2** | Carnitine palmitoyltransferase II | **p.Ser113Leu (c.338C>T)** — common mild; p.Arg631Cys (severe) | CPT2 deficiency | Myopathy; rhabdomyolysis; cardiomyopathy (infantile severe) | None |
   541|| **CACT (SLC25A20)** | Carnitine-acylcarnitine translocase | **c.199-10T>G (splice)**; p.Arg254His; p.Arg285* | CACT deficiency | Severe neonatal; cardiomyopathy; arrhythmias; high mortality | None |
   542|| **SLC22A5** | OCTN2 (carnitine transporter) | **c.136C>T (p.Pro46Ser)**; c.1400C>G (p.Ser467Cys); c.51C>G (p.Phe17Leu) | Primary carnitine deficiency | Cardiomyopathy; weakness; fasting intolerance; carnitine responsive | None |
   543|| **ECHS1** | Enoyl-CoA hydratase, short-chain 1 | **p.Arg181Cys (c.541C>T)**; p.Gly229Arg; c.337-2A>G | ECHS1 deficiency | Leigh-like syndrome; developmental delay; metabolic acidosis | None |
   544|| **HMGCL** | 3-hydroxymethyl-3-methylglutaryl-CoA lyase | **c.1228C>T (p.Arg410*)**; p.Lys46Glu; c.750_751del | HMGCL deficiency | Hypoketotic hypoglycemia; metabolic acidosis; hyperammonemia | None |
   545|| **HMGCS2** | 3-hydroxymethyl-3-methylglutaryl-CoA synthase 2 | **p.Arg41Cys (c.121C>T)**; p.Arg186* | HMGCS2 deficiency | Hypoketotic hypoglycemia; no ketogenesis during fasting | None |
   546|| **ETFA** | Electron transfer flavoprotein α | **p.Glu121Lys (c.361G>A)**; p.Thr266Met | MADD (type II) | Neonatal or late-onset; hypoglycemia; metabolic acidosis | **FAD**, **AMP**, **Riboflavin** |
   547|| **ETFB** | Electron transfer flavoprotein β | **p.Glu165* (c.493G>T)**; p.Pro38Leu | MADD (type II) | Similar to ETFA; riboflavin responsive in some | **FAD**, **Riboflavin** |
   548|| **ETFDH** | ETF dehydrogenase | **p.Ala84Thr (c.250G>A)**; p.Pro456Leu; p.Gly389Arg | MADD (type III) — most common adult form | Late-onset myopathy; lipid storage myopathy; **riboflavin responsive** | **FAD**, **Riboflavin** |
   549|| **ACAD9** | Acyl-CoA dehydrogenase 9 | **p.Arg532Trp (c.1594C>T)**; p.Arg410Cys | ACAD9 deficiency | Complex I deficiency; hypertrophic cardiomyopathy | **FAD** |
   550|| **DECR1** | 2,4-dienoyl-CoA reductase | Various | β-oxidation of unsaturated fatty acids; mild phenotype | **NADPH** |
   551|
   552|### Fatty Acid β-Oxidation Flow
   553|```
   554|Cytosol: Fatty acid + CoA ─────────────────────────────────────────────────→ Acyl-CoA
   555|                                                              ↓
   556|Mitochondrial matrix: Acyl-CoA → Enoyl-CoA → 3-OH-Acyl-CoA → 3-Keto-Acyl-CoA → Acetyl-CoA
   557|                      (ACAD/FAD)    (hydratase)   (HADH/NAD)      (thiolase)
   558|                                                              ↓
   559|                                           Acetyl-CoA → Ketogenesis → TCA cycle
   560|```
   561|
   562|### Riboflavin-Responsive Variants
   563|| Disorder | Gene | Responsive Variant | Clinical Significance |
   564||----------|------|-------------------|----------------------|
   565|| MADD (late-onset) | ETFDH | p.Ala84Thr, others | 100-400 mg riboflavin daily; dramatic improvement |
   566|| MADD | ETF/ETFB | Some missense variants | Variable response to riboflavin |
   567|| SCAD | ACADS | c.625G>A (Gly209Ser) | May benefit from riboflavin; controversial |
   568|
   569|---
   570|
   571|## 16. Mitochondrial Oxidative Phosphorylation (OXPHOS)
   572|
   573|Mitochondrial DNA (mtDNA) encodes 13 core subunits; nuclear DNA encodes remaining ≈1500 mitochondrial proteins.
   574|
   575|### mtDNA-Encoded Complex Subunits (Maternally Inherited)
   576|| Gene | Complex | Key Variant | Clinical Association |
   577||------|---------|-------------|---------------------|
   578|| **MT-ND1** | I | **m.3460G>A (p.Ala52Thr)**; m.3635G>A | LHON (Leber hereditary optic neuropathy); ND1 variants |
   579|| **MT-ND4** | I | **m.11778G>A (p.Arg340His)** — most common LHON | LHON (70% of cases); severe visual loss; male predominance |
   580|| **MT-ND6** | I | **m.14484T>C (p.Met64Val)**; m.14459G>A | LHON (15% of cases); better visual recovery prognosis |
   581|| **MT-ND5** | I | m.12706T>C; m.13708A>G | MELAS; Leigh syndrome; NARP |
   582|| **MT-TL1** | tRNA^Leu(UUR) | **m.3243A>G** — most common mtDNA mutation | MELAS; MIDD (maternally inherited diabetes and deafness); stroke-like episodes |
   583|| **MT-TK** | tRNA^Lys | **m.8344A>G** — most common MERRF | MERRF (myoclonic epilepsy with ragged-red fibers); hearing loss |
   584|| **MT-TC** | tRNA^Cys | **m.5814A>G** | MELAS-like; cardiomyopathy |
   585|| **MT-ATP6** | V | **m.8993T>G (p.Leu156Arg)**; **m.8993T>C** | NARP (neuropathy, ataxia, retinitis pigmentosa); Leigh syndrome (higher heteroplasmy) |
   586|| **MT-CO3** | IV | **m.9438G>A**; m.9947G>A | Exercise intolerance; myopathy |
   587|| **MT-CYB** | III | **m.15579A>G**; m.15043G>A | Complex III deficiency; multisystem disease |
   588|| **MT-TE** | tRNA^Glu | **m.14709T>C** | Maternal HCM; diabetes; deafness |
   589|| **Large deletions** | Multiple | **m.8470_13446del (4.9kb "common deletion")**; m.4389_14812del | Kearns-Sayre syndrome (KSS); CPEO; Pearson syndrome |
   590|
   591|### Nuclear-Encoded OXPHOS Assembly Factors
   592|| Gene | Protein | Key SNP / Variant | Disorder | Cofactor |
   593||------|---------|-------------------|----------|----------|
   594|| **POLG** | mtDNA polymerase γ | **p.Ala467Thr (c.1399G>A)**; **p.Trp748Ser (c.2243G>C)**; p.Gly848Ser | PEO, Alpers syndrome (hepatocerebral); ataxia-neuropathy; valproate hepatotoxicity | **Magnesium** |
   595|| **C10orf2 (TWNK)** | Twinkle helicase | **p.Asn468Ser (c.1403A>G)**; p.Arg374Gln; c.1319_1321del | PEO with mtDNA deletions; infantile-onset spinocerebellar ataxia | **ATP**, **Magnesium** |
   596|| **OPA1** | Dynamin-like GTPase | **p.Arg445His (c.1334G>A)**; p.Gly401Asp; p.Arg290* | Dominant optic atrophy (DOA); Behr syndrome; CPEO-plus | **Magnesium** |
   597|| **MFN2** | Mitofusin 2 | **p.Arg94Trp (c.280C>T)**; **p.His361Tyr (c.1081C>T)**; p.Thr362Ala | Charcot-Marie-Tooth disease 2A (CMT2A); mitochondrial fusion defect | **GTP** |
   598|| **PINK1** | PTEN-induced kinase 1 | **p.Glu240Lys (c.718G>A)**; p.Trp437*; p.Gly309Asp | Early-onset Parkinson's disease (autosomal recessive); mitophagy | **ATP**, **Magnesium** |
   599|| **PRKN (Parkin)** | E3 ubiquitin ligase | **p.Trp453* (c.1359G>A)**; p.Arg275Trp; exon deletions | Early-onset Parkinson's (juvenile); mitophagy; E3 ligase activity | None |
   600|| **SPG7** | Paraplegin | **p.Ala510Val (c.1529C>T)**; p.Ter689Glufs; p.Arg499* | Hereditary spastic paraplegia 7; complex I defect | **Zinc** |
   601|| **AFG3L2** | AAA protease | **p.Tyr616Cys (c.1847A>G)**; p.Gly671Arg | Spinocerebellar ataxia 28 (SCA28) | **Zinc** |
   602|| **NRF1, NFE2L2 (NRF2)** | Transcription factors | **NFE2L2 rs6721961** (promoter); rs35652124 | Mitochondrial biogenesis; oxidative stress response; cancer protection | **Zinc** |
   603|| **TFAM** | Transcription factor A | rs1937; rs2306604 | mtDNA maintenance; D-loop regulation; common variants | **Zinc** |
   604|| **RRM2B** | Ribonucleotide reductase p53-inducible | **p.Gly16Ser (c.46G>A)**; c.541dupA | Mitochondrial DNA depletion syndrome; PEO; encephalomyopathic | **Iron** |
   605|| **TK2** | Thymidine kinase 2 | **p.Ile181Asn (c.542T>A)**; p.Arg225Trp | mtDNA depletion syndrome; myopathic form | **ATP** |
   606|| **TYMP** | Thymidine phosphorylase | **p.Phe199Leu (c.595T>C)**; p.Gly12Ser; c.371-2A>G | MNGIE (mitochondrial neurogastrointestinal encephalomyopathy) | **Phosphate** |
   607|| **DGOUK** | Deoxyguanosine kinase | **p.Leu88Ser (c.263T>C)**; p.Arg142* | mtDNA depletion; hepatocerebral syndrome; liver failure | **ATP** |
   608|| **MPV17** | MPV17 mitochondrial inner membrane protein | **p.Arg50Gln (c.149G>A)**; p.Arg105Trp; c.215-2A>G | Navajo neurohepatopathy; infantile hepatocerebral MDS | None |
   609|| **SUCLA2** | Succinate-CoA ligase ADP-forming β | **p.Arg284Cys (c.850C>T)**; p.Arg258Cys | Mitochondrial DNA depletion; leukoencephalomyopathy | **ATP** |
   610|| **SUCLG1** | Succinate-CoA ligase GDP/ATP-forming α | **p.Arg405* (c.1213C>T)**; p.Arg166Cys | Severe mtDNA depletion; encephalomyopathic | **ATP**, **GTP** |
   611|
   612|---
   613|
   614|## 17. Steroid Hormone Biosynthesis
   615|
   616|Cholesterol-derived hormones: glucocorticoids, mineralocorticoids, androgens, estrogens.
   617|
   618|### Core Steroidogenic Enzymes
   619|| Gene | Enzyme | Key SNP / Variant | Pathway | Clinical Association | Cofactor |
   620||------|--------|-------------------|---------|---------------------|----------|
   621|| **CYP11A1** | Cholesterol side-chain cleavage (P450scc) | **p.Gln258* (c.772C>T)**; c.940-2A>G (splice) | All steroids | Lipoid CAH; adrenal insufficiency; 46,XY DSD | **Iron**, **NADPH** |
   622|| **HSD3B2** | 3β-hydroxysteroid dehydrogenase/Δ5-Δ4 isomerase | **p.Lys382Thr (c.1145A>C)**; p.Gly15*; p.Arg249Trp | All classes | 3β-HSD deficiency; CAH; salt-wasting; 46,XY DSD | **NAD** |
   623|| **CYP17A1** | 17α-hydroxylase/17,20-lyase | **p.Phe53Leu (c.159C>G)**; p.Trp406Arg; p.Pro342Thr | Androgens, cortisol | 17α-hydroxylase deficiency; hypertension, sexual infantilism | **Iron**, **NADPH** |
   624|| **CYP21A2** | 21-hydroxylase | **p.Val281Leu (c.841G>C)** — non-classic; **p.Ile172Asn (c.515T>A)**; large deletions | Cortisol, aldosterone | 21-hydroxylase deficiency (classic CAH); salt-wasting; simple virilizing | **Iron**, **NADPH** |
   625|| **CYP11B1** | 11β-hydroxylase | **p.Arg448His (c.1343G>A)**; p.Arg374Gln; p.Thr318Met | Cortisol | 11β-hydroxylase deficiency; CAH; hypertension; hypokalemia | **Iron**, **NADPH** |
   626|| **CYP11B2** | Aldosterone synthase | **p.Val386Ala (c.1157T>C)**; c.249-2A>G; p.Trp176* | Aldosterone | Aldosterone synthase deficiency; salt-wasting; hyperkalemia | **Iron**, **NADPH** |
   627|| **HSD17B3** | 17β-hydroxysteroid dehydrogenase 3 | **p.Arg80Gln (c.239G>A)**; p.Gly289Ser; c.325+4A>C | Testosterone synthesis | 17β-HSD3 deficiency; 46,XY DSD; virilization at puberty | **NADPH** |
   628|| **SRD5A2** | 5α-reductase type 2 | **p.Gln126Arg (c.377A>G)**; p.Arg227Gln; p.Arg246Gln | DHT synthesis | 5α-reductase deficiency; 46,XY DSD; finasteride response | **NADPH** |
   629|| **CYP19A1** | Aromatase | **p.Arg115Trp (c.343C>T)**; p.Arg192His; c.900-3C>A | Estradiol synthesis | Aromatase deficiency; tall stature; cystic ovaries; estrogen insufficiency | **Iron**, **NADPH** |
   630|| **HSD11B1** | 11β-hydroxysteroid dehydrogenase type 1 | **rs11220256**; rs11119328; rs12569024 | Cortisol activation | Metabolic syndrome; visceral obesity; cortisone → cortisol | **NADPH** |
   631|| **HSD11B2** | 11β-hydroxysteroid dehydrogenase type 2 | **p.Arg208Cys (c.622C>T)**; p.Arg337Cys; p.Ala386Val | Cortisol inactivation | Apparent mineralocorticoid excess; hypertension; Liddle-like | **NAD** |
   632|| **STAR** | Steroidogenic acute regulatory protein | **p.Gln258* (c.772C>T)**; p.Leu260Pro; c.653_654delCA | Cholesterol transport | Lipoid CAH; with CYP11A1 deficiency; severe adrenal insufficiency | None |
   633|
   634|### Steroid Metabolism Pathway Flow
   635|```
   636|Cholesterol ─STAR─→ Pregnenolone ──────────────────────────────────────────────────────────────────────→
   637|                      ┌──────────────────────────────────────────────────────┐
   638|                      ↓                                               ↓
   639|               Progesterone → Corticosterone → Aldosterone     17-OH-Pregnenolone → 17-OH-Progesterone
   640|                      (mineralocorticoid)                               ↓
   641|                                                                     Androstenedione → Testosterone ─SRD5A2─→ DHT
   642|                                                                                          ↓
   643|                                                                                   Estradiol (via CYP19A1)
   644|```
   645|
   646|### Androgen Receptor and Sensitivity
   647|| Gene | Protein | Key SNP | Effect |
   648||------|---------|---------|--------|
   649|| **AR** | Androgen receptor | **CAG repeat (exon 1)** — 9-38 repeats; **p.Gln58* (c.172C>T)**; p.Leu741Phe | Short CAG = ↑ androgen sensitivity; long CAG = ↓ sensitivity; Kennedy disease (expanded) |
   650|
   651|---
   652|
   653|## 18. Glycogen Metabolism & Storage Diseases
   654|
   655|Glycogen storage diseases (GSDs) affect liver, muscle, or both.
   656|
   657|| Gene | Enzyme | Key SNP / Variant | GSD Type | Clinical Features | Cofactor |
   658||------|--------|-------------------|----------|-------------------|----------|
   659|| **G6PC** | Glucose-6-phosphatase | **c.562C>T (p.Arg188Trp)**; c.1176_1177delGA; c.378C>T (p.Thr126=; splicing) | Ia | von Gierke disease; severe hypoglycemia; hepatomegaly; lactic acidosis | None |
   660|| **SLC37A4** | G6P transporter | **c.1192C>T (p.Arg398Trp)**; c.1084C>T (p.Arg362*) | Ib | Similar to Ia + neutropenia; IBD risk; empagliflozin responsive | None |
   661|| **GBE1** | Glycogen branching enzyme | **p.Tyr329Ser (c.986A>C)**; p.Trp616*; IVS9+1G>A | IV (Andersen disease) | Cirrhosis; cardiomyopathy; death in infancy (severe) | None |
   662|| **AGL** | Glycogen debranching enzyme | **p.Arg864* (c.2590C>T)**; p.Arg1459*; c.1887delA | III (Cori disease) | Hypoglycemia; hepatomegaly; myopathy; cardiomyopathy | None |
   663|| **PYGL** | Liver glycogen phosphorylase | **p.Arg44* (c.130C>T)**; p.Arg462Trp | VI (Hers disease) | Mild hepatomegaly; ketotic hypoglycemia; benign course | **PLP** (B6), **AMP** |
   664|| **PYGM** | Muscle glycogen phosphorylase | **p.Arg50* (c.148C>T)**; p.Gly204Ser; p.Gly684Asp | V (McArdle disease) | Exercise intolerance; myoglobinuria; "second wind" phenomenon | **PLP** (B6), **AMP** |
   665|| **PFKM** | Muscle phosphofructokinase | **p.Asp222Val (c.665A>T)**; p.Arg232Trp; p.Pro504Leu | VII (Tarui disease) | Exercise intolerance; hemolytic anemia; myopathy; cramps | **ATP**, **Magnesium** |
   666|| **GAA** | Acid α-glucosidase (acid maltase) | **c.-32-13T>G (IVS1)** — leaky splice; **p.Trp746* (c.2238G>A)**; p.Arg854* | II (Pompe disease) | Cardiomyopathy (infantile); myopathy (adult); ERT (alglucosidase) | None |
   667|| **PHKA2** | Phosphorylase kinase α2 | **p.Arg224Gln (c.671G>A)**; c.2857+1G>A; p.Glu866* | IXa (XL) | Hepatomegaly; fasting hypoglycemia; short stature; resolves at puberty | **Calcium**, **Magnesium**, **ATP** |
   668|| **PHKB** | Phosphorylase kinase β | **p.Arg414* (c.1240C>T)**; p.Gly122Arg | IXb (AR) | Similar to IXa; autosomal recessive | **Calcium**, **Magnesium**, **ATP** |
   669|| **PHKG2** | Phosphorylase kinase γ2 | **p.Arg44Trp (c.130C>T)**; p.Arg306* | IXc (AR) | Similar to IXa; more severe liver disease | **Calcium**, **Magnesium**, **ATP** |
   670|| **LDHA** | Lactate dehydrogenase A | **c.800C>T (p.Thr267Ile)**; p.Arg178Trp | GSD XI | Exercise intolerance; myoglobinuria; high LDH activity | **NADH**, **NAD** |
   671|| **PGM1** | Phosphoglucomutase 1 | **p.Arg422* (c.1264C>T)**; p.Ser107Leu; c.1645+1G>A | GSD XIV | Hypoglycemia; congenital disorders of glycosylation; endocrine abnormalities | **Magnesium**, **G1,6BP** |
   672|| **PGK1** | Phosphoglycerate kinase 1 | **p.Thr387Arg (c.1160C>G)**; p.Arg204*; c.889C>T | GSD with hemolysis | Hemolytic anemia; myopathy; neurological impairment | **ATP**, **Magnesium** |
   673|| **ENO3** | Enolase 3 (β-enolase) | **p.Gly374Asp (c.1121G>A)**; p.Met256Val | GSD XIII | Exercise intolerance; myopathy; milder than others | **Magnesium** |
   674|
   675|### Glycogen Storage Disease Summary Table
   676|| GSD Type | Gene | Defect | Primary Organ | Treatment |
   677||----------|------|--------|---------------|-----------|
   678|| 0 | GYS2 (liver) | Glycogen synthase | Liver | Frequent meals |
   679|| Ia | G6PC | G6Pase | Liver | Cornstarch; liver transplant |
   680|| Ib | SLC37A4 | G6P transporter | Liver | Cornstarch; G-CSF |
   681|| II (Pompe) | GAA | Acid α-glucosidase | Muscle/Heart | ERT (alglucosidase alfa) |
   682|| III (Cori) | AGL | Debranching enzyme | Liver/Muscle | Cornstarch; high protein |
   683|| IV (Andersen) | GBE1 | Branching enzyme | Liver | Liver transplant |
   684|| V (McArdle) | PYGM | Muscle phosphorylase | Muscle | Exercise moderation; B6 |
   685|| VI (Hers) | PYGL | Liver phosphorylase | Liver | Cornstarch |
   686|| VII (Tarui) | PFKM | PFK-1 | Muscle | Avoid high-intensity exercise |
   687|
   688|---
   689|
   690|## 19. Bile Acid Synthesis & Transport
   691|
   692|Primary bile acids (cholic acid, chenodeoxycholic acid) are synthesized from cholesterol.
   693|
   694|### Bile Acid Synthesis Enzymes
   695|| Gene | Enzyme | Key SNP / Variant | Disorder | Clinical Features | Cofactor |
   696||------|--------|-------------------|----------|-------------------|----------|
   697|| **CYP7A1** | Cholesterol 7α-hydroxylase | **c.-203A>C (rs3808607)**; c.646+1G>T (splice); p.Thr439Met | CYP7A1 deficiency | Hyperlipidemia; gallstones; vitamin malabsorption | **Iron**, **NADPH** |
   698|| **CYP27A1** | Sterol 27-hydroxylase | **p.Arg446Trp (c.1336C>T)**; **p.Arg362Leu (c.1085G>T)**; p.Trp282* | CTX | Juvenile cataracts; xanthomas; neurological decline; **chenodeoxycholic acid treatment** | **Iron**, **NADPH** |
   699|| **HSD3B7** | 3β-hydroxy-Δ5-C27-steroid oxidoreductase | **p.Asp38Asn (c.112G>A)**; p.Arg201*; c.45_46delAG | Bile acid synthesis defect 1 | Neonatal cholestasis; fat-soluble vitamin deficiency; cirrhosis | **NAD** |
   700|| **AKR1D1** | Δ4-3-oxosteroid 5β-reductase | **p.Gln257His (c.771G>T)**; p.Arg261*; c.579+1G>A | BASD 2 | Neonatal cholestasis; severe liver disease; Δ4-3-oxo bile acids in urine | **NADPH** |
   701|| **CYP7B1** | 25-hydroxycholesterol 7α-hydroxylase | **p.Arg417Cys (c.1249C>T)**; p.Arg388Trp; p.Tyr275* | SPG5 (HSP) | Hereditary spastic paraplegia 5; bile acid synthesis; motor neuron disease | **Iron**, **NADPH** |
   702|| **AMACR** | α-methylacyl-CoA racemase | **p.Ser52Pro (c.154T>C)**; p.Arg386*; p.Met1? | AMACR deficiency | Adult-onset sensory neuropathy; bile acid synthesis defect; pristanic acid ↑ | None |
   703|| **SLC27A5** | Very-long-chain acyl-CoA synthetase (BACS) | **p.Arg575* (c.1723C>T)**; p.Thr418Met | Bile acid-CoA conjugation defect | Fat-soluble vitamin malabsorption; growth failure; low GGT cholestasis | **ATP**, **Magnesium** |
   704|| **BAAT** | Bile acid-CoA:amino acid N-acyltransferase | **p.Arg131* (c.391C>T)**; p.Arg304* | Conjugation defect | Unconjugated bile acids; malabsorption | None |
   705|
   706|### Bile Acid Transport (Cholestasis Genes)
   707|| Gene | Protein | Key SNP / Variant | Disorder | Clinical Features | Cofactor |
   708||------|---------|-------------------|----------|-------------------|----------|
   709|| **ABCB4 (MDR3)** | Phospholipid floppase | **p.Arg180* (c.538C>T)**; **p.Gly68Arg (c.202G>A)**; p.Arg1056Gln | PFIC3; ICP | Pruritus; elevated GGT; ursodiol responsive; liver failure | **ATP** |
   710|| **ABCB11 (BSEP)** | Bile salt export pump | **p.Glu297Gly (c.890A>G)**; **p.Ala1084Thr (c.3250G>A)**; p.Arg1231* | PFIC2; BRIC2 | Severe cholestasis; HCC risk; GGT normal/low; bile acids ↑↑ | **ATP** |
   711|| **ATP8B1 (FIC1)** | Aminophospholipid flippase | **p.Ala386Val (c.1157C>T)**; **p.Ile661Thr (c.1982T>C)**; p.Arg967* | PFIC1; BRIC1 | Severe cholestasis; GGT normal; diarrhea; poor ursodiol response; hearing loss | **ATP** |
   712|| **ABCG5** | Sterolin-1 | **p.Gln604Glu (c.1812C>G)**; p.Tyr54*; p.Arg446* | Sitosterolemia | Tendon xanthomas; hemolytic anemia; plant sterol accumulation | **ATP** |
   713|| **ABCG8** | Sterolin-2 | **p.Arg263Gln (c.788G>A)**; p.Gln251*; p.Arg446* | Sitosterolemia | Similar to ABCG5; arthritis; premature CAD | **ATP** |
   714|| **NR1H4 (FXR)** | Farnesoid X receptor | rs56163822; rs10860603 | Cholestasis; GGT elevation | Bile acid homeostasis; ursodiol target; metabolic regulation | **Zinc** |
   715|| **TJP2** | Tight junction protein 2 | **p.Gly796Val (c.2387G>T)**; p.Thr236Ala | Familial hypercholanemia | Elevated serum bile acids; pruritus; cholestasis; liver failure | None |
   716|| **VIPAS39** | Vps33b homolog | **p.Arg484Trp (c.1450C>T)**; p.Glu292* | ARC syndrome (arthrogryposis, renal dysfunction, cholestasis) | Cholestasis; platelet dysfunction; renal tubular dysfunction | None |
   717|| **VPS33B** | Vacuolar protein sorting 33B | **p.Arg438* (c.1312C>T)**; p.Arg498* | ARC syndrome | Similar to VIPAS39; cholestasis; platelet dysfunction | None |
   718|
   719|### Progressive Familial Intrahepatic Cholestasis (PFIC) Comparison
   720|| Type | Gene | Defect | GGT | Pruritus | HCC Risk | Treatment |
   721||------|------|--------|-----|----------|----------|-----------|
   722|| PFIC1 | ATP8B1 | FIC1 flippase | Normal | Severe | Low | Biliary diversion; liver transplant |
   723|| PFIC2 | ABCB11 | BSEP | Low/normal | Severe | High | Liver transplant; monitoring |
   724|| PFIC3 | ABCB4 | MDR3 floppase | Elevated | Moderate | Moderate | Ursodiol; liver transplant |
   725|
   726|---
   727|
   728|## 20. Connective Tissue & Collagen Crosslinking
   729|
   730|Collagen structure and post-translational modification genes.
   731|
   732|| Gene | Enzyme / Protein | Key SNP / Variant | Disorder | Clinical Features | Cofactor |
   733||------|------------------|-------------------|----------|-------------------|----------|
   734|| **PLOD1** | Lysyl hydroxylase 1 | **p.Asp144* (c.432G>A)**; p.Arg319*; p.Pro442Leu; exon deletions | Kyphoscoliotic EDS (type VI) | Severe hypotonia; kyphoscoliosis; ocular fragility; B6 responsive | **Iron**, **Ascorbate**, **2-oxoglutarate** |
   735|| **PLOD2** | Lysyl hydroxylase 2 | **p.Gly678Asp (c.2033G>A)**; p.Arg742*; p.Pro631Leu | Bruck syndrome 2 | Joint contractures; bone fragility; wormian bones | **Iron**, **Ascorbate**, **2-oxoglutarate** |
   736|| **PLOD3** | Lysyl hydroxylase 3 | **p.Asp882His (c.2644G>C)**; p.Arg769* | Spondyloocular syndrome | Cataracts; short stature; vertebral abnormalities | **Iron**, **Ascorbate**, **2-oxoglutarate** |
   737|| **B4GALT7** | β-1,4-galactosyltransferase 7 | **p.Arg270Cys (c.808C>T)**; p.Arg270His | EDS progeroid type | Progeroid appearance; short stature; hypermobile EDS | **Manganese** |
   738|| **B3GALT6** | β-1,3-galactosyltransferase 6 | **p.Arg270* (c.808C>T)**; p.Arg211Trp; p.Arg254Gln | SEMD-JL | Short stature; skeletal dysplasia; EDS features; joint laxity | **Manganese** |
   739|| **CHST14** | Dermatan-4-sulfotransferase | **p.Arg307* (c.919C>T)**; **p.Arg304Trp (c.910C>T)** | Musculocontractural EDS (mcEDS) | Distal joint contractures; craniofacial features; scoliosis | **PAPS** |
   740|| **DSE** | Dermatan sulfate epimerase | **p.Gly211Val (c.632G>T)**; p.Arg316Trp | EDS-like | Overlapping CHST14 phenotype; joint contractures | None |
   741|| **LOX** | Lysyl oxidase | **p.Gly217Asp (c.650G>A)**; p.Trp198*; p.Gly400Arg | Aortic aneurysm; cutis laxa | Aortic root dilation; arterial tortuosity; emphysema | **Copper**, **LTQ** |
   742|| **LOXL1** | Lysyl oxidase-like 1 | **p.Arg141Leu (rs1048661)**; **p.Gly153Asp (rs3825942)** | Pseudoexfoliation glaucoma; pelvic organ prolapse | ECM crosslinking; elastin regeneration | **Copper** |
   743|| **LOXL2** | Lysyl oxidase-like 2 | rs11583624; rs13112082 | Liver fibrosis; metastasis | Collagen crosslinking; tumor microenvironment | **Copper** |
   744|| **COL1A1** | Type I collagen α1 | **p.Gly415Ser (c.1243G>A)**; **p.Gly850Ser**; large deletions | OI type I-IV; arthrochalasia EDS | Bone fragility; blue sclerae; short stature; deafness | **Ascorbate**, **Iron** |
   745|| **COL1A2** | Type I collagen α2 | **p.Gly382Arg**; **p.Gly727Asp**; p.Gly751Ser | OI type I-IV; cardiac valvular EDS | Similar to COL1A1; specific valvular disease in cvEDS | **Ascorbate**, **Iron** |
   746|| **COL3A1** | Type III collagen | **p.Gly619Arg**; **p.Gly1003Asp**; exon skipping | Vascular EDS (type IV) | Arterial/uterine rupture; thin skin; characteristic facies; sudden death | **Ascorbate**, **Iron** |
   747|| **COL5A1** | Type V collagen α1 | **p.Gly530Ser**; p.Gly1021Asp; null alleles | Classical EDS (cEDS) | Hypermobile skin; joint laxity; atrophic scarring | **Ascorbate**, **Iron** |
   748|| **COL5A2** | Type V collagen α2 | **p.Gly623Arg**; p.Gly936Ser | Classical EDS | Similar to COL5A1; milder phenotype | **Ascorbate**, **Iron** |
   749|| **FKBP14** | FK506-binding protein 14 | **p.Gly118Asp**; p.Arg116His | EDS with progressive kyphoscoliosis | Kyphoscoliosis; myopathy; hearing loss; B6 responsive | None |
   750|
   751|### EDS Types Summary
   752|| Type | Gene | Inheritance | Key Features |
   753||------|------|-------------|--------------|
   754|| Classical (cEDS) | COL5A1/2, COL1A1 | AD | Skin hyperextensibility; atrophic scars; joint hypermobility |
   755|| Hypermobile (hEDS) | Unknown | AD | Joint hypermobility; pain; fatigue; no genetic test |
   756|| Vascular (vEDS) | COL3A1 | AD | Arterial rupture; thin skin; early mortality |
   757|| Kyphoscoliotic (kEDS) | PLOD1, FKBP14 | AR | Severe hypotonia; scoliosis; ocular fragility |
   758|| Arthrochalasia (aEDS) | COL1A1/2 | AD | Severe joint hypermobility; congenital hip dislocation |
   759|| Dermatosparaxis (dEDS) | ADAMTS2 | AR | Fragile skin; sagging; easy bruising |
   760|| Musculocontractural (mcEDS) | CHST14, DSE | AR | Contractures; scoliosis; distinctive facies |
   761|
   762|---
   763|
   764|## 21. Lysosomal Enzymes (Selected Clinically Actionable)
   765|
   766|Lysosomal storage disorders with enzyme replacement therapy (ERT) or substrate reduction therapy (SRT).
   767|
   768|| Gene | Enzyme | Key SNP / Variant | Disorder | Clinical Features | Cofactor |
   769||------|--------|-------------------|----------|-------------------|----------|
   770|| **GLA** | α-galactosidase A | **p.Arg227* (c.679C>T)**; **p.Arg301Gln (c.902G>A)**; p.Met42Val; large deletions | Fabry disease | Neuropathic pain; angiokeratomas; renal failure; stroke; ERT (agalsidase) | None |
   771|| **GAA** | Acid α-glucosidase | **c.-32-13T>G (IVS1)** — late-onset; **p.Arg854* (c.2560C>T)**; p.Asp645Glu | Pompe disease (GSD II) | Cardiomyopathy (infantile); myopathy (late-onset); ERT (alglucosidase) | None |
   772|| **GALNS** | N-acetylgalactosamine-6-sulfatase | **p.Arg386Cys (c.1156C>T)**; **p.Cys279Tyr (c.836G>A)**; p.Arg94* | Morquio A (MPS IVA) | Skeletal dysplasia; short stature; atlantoaxial instability; ERT (elosulfase) | **Calcium** |
   773|| **GUSB** | β-glucuronidase | **p.Tyr85* (c.255C>G)**; p.Pro250Leu; p.Arg601* | MPS VII (Sly syndrome) | Hepatosplenomegaly; dysostosis multiplex; ERT (vestronidase) | None |
   774|| **IDS** | Iduronate-2-sulfatase | **p.Arg468* (c.1402C>T)**; **p.Arg443* (c.1327C>T)**; large deletions | Hunter syndrome (MPS II) | Coarse facies; hepatomegaly; CNS involvement (severe); ERT (idursulfase) | None |
   775|| **IDUA** | α-L-iduronidase | **p.Trp402* (c.1205G>A)**; **p.Pro533Arg (c.1598C>G)**; p.Ala75Pro | Hurler/Scheie (MPS I/H/S) | Skeletal abnormalities; corneal clouding; ERT (laronidase) | None |
   776|| **SGSH** | N-sulfoglucosamine sulfohydrolase | **p.Arg234Cys (c.700C>T)**; **p.Arg245* (c.733C>T)**; p.Arg74Cys | Sanfilippo A (MPS IIIA) | Severe neurodegeneration; minimal somatic features; no ERT (CNS limited) | None |
   777|| **NAGLU** | α-N-acetylglucosaminidase | **p.Ser690Trp (c.2069C>G)**; p.Arg626*; p.Arg297* | Sanfilippo B (MPS IIIB) | Similar to MPS IIIA; neurodegeneration; aggressive behavior | None |
   778|| **ARSA** | Arylsulfatase A | **p.Arg90* (c.269C>T)**; **p.Arg390Trp (c.1168C>T)**; p.Arg496*; c.459+1G>A | Metachromatic leukodystrophy (MLD) | Demyelination; ataxia; cognitive decline; ERT (atidarsagene) | **Calcium** |
   779|| **GALC** | Galactosylceramidase | **p.Gly270Asp (c.809G>A)**; p.Trp221*; c.1161+653A>G (30kb deletion) | Krabbe disease | Rapid neurodegeneration (infantile); peripheral neuropathy; HSCT curative early | None |
   780|| **HEXA** | Hexosaminidase A α-subunit | **c.1274_1277dupTATC (p.Tyr427fs)** — 80% AJ; **c.1073+1G>A (IVS9)**; p.Arg178His (adult-onset) | Tay-Sachs disease | Cherry-red spot; neurodegeneration; seizures; infantile death | None |
   781|| **HEXB** | Hexosaminidase B β-subunit | **p.Leu385* (c.1153C>T)**; p.Cys534Tyr | Sandhoff disease | Similar to Tay-Sachs + hepatosplenomegaly; no ethnic predilection | None |
   782|| **GM2A** | GM2 activator protein | **p.Arg47* (c.139C>T)**; p.Arg160Trp | GM2 activator deficiency | Atypical GM2 gangliosidosis; later onset | **Calcium** |
   783|| **ASAH1** | Acid ceramidase | **p.Phe285Leu (c.853T>C)**; p.Thr168Ile; p.Arg254* | Farber disease | Joint deformities; subcutaneous nodules; hoarse cry; CNS in severe | None |
   784|| **SMPD1** | Acid sphingomyelinase | **p.Arg496Leu (c.1487G>T)**; **p.Phe333Serfs (c.996delC)**; p.Arg610del | Niemann-Pick A/B | Hepatosplenomegaly; neurodegeneration (A); ERT (olipudase) for B | None |
   785|| **NPC1** | NPC intracellular cholesterol transporter 1 | **p.Ile1061Thr (c.3182T>C)**; p.Gln92*; p.Arg1186* | Niemann-Pick C | Progressive neurodegeneration; vertical gaze palsy; hepatosplenomegaly; miglustat | **Cholesterol**, **Oxysterols** |
   786|| **NPC2** | NPC intracellular cholesterol transporter 2 | **p.Arg58* (c.172C>T)**; p.Thr106Met; p.Thr116Met | Niemann-Pick C | Similar to NPC1; rarer | **Cholesterol** |
   787|| **GBA** | β-glucocerebrosidase | **p.Asn370Ser (c.1226A>G)**; **p.Leu444Pro (c.1448T>C)**; p.Arg48Trp (c.84dupG) | Gaucher disease types 1-3 | Hepatosplenomegaly; cytopenia; bone disease; parkinsonism risk; ERT/CMT | None |
   788|| **HEXB** | Hexosaminidase B | See above | Sandhoff disease | GM2 gangliosidosis variant | None |
   789|| **CTSA** | Cathepsin A | **p.Tyr390* (c.1170C>A)**; p.Ser72Gly | Galactosialidosis | Combined neuraminidase/beta-galactosidase deficiency | None |
   790|
   791|### Lysosomal Storage Disease Treatment Summary
   792|| Disease | Gene | ERT Available | SRT Available | Transplant Curative | Notes |
   793||---------|------|---------------|---------------|---------------------|-------|
   794|| Fabry | GLA | Yes (agalsidase) | Yes (migalastat — Amicus) | No | Chaperone for amenable variants |
   795|| Gaucher | GBA | Yes (imiglucerase, etc.) | Yes (eliglustat, miglustat) | HSCT (rare) | Most common LSD |
   796|| Pompe | GAA | Yes (alglucosidase) | No | No | CRISPR trials ongoing |
   797|| MPS I | IDUA | Yes (laronidase) | No | HSCT (Hurler) | Gene therapy trials |
   798|| MPS II | IDS | Yes (idursulfase) | No | No | IT formulation for CNS |
   799|| MPS IVA | GALNS | Yes (elosulfase) | No | No | Fusions for bone |
   800|| MPS VI | ARSB | Yes (galsulfase) | No | No | Rare |
   801|| MPS VII | GUSB | Yes (vestronidase) | No | No | Ultra-rare |
   802|| Niemann-Pick B | SMPD1 | Yes (olipudase) | No | No | Recently approved |
   803|| Niemann-Pick C | NPC1/2 | No | Yes (miglustat) | No | Cyclodextrin trials |
   804|| Fabry | GLA | Yes | Migalastat | | Chaperone therapy |
   805|| MLD | ARSA | Yes (atidarsagene) | No | HSCT | Gene therapy approved |
   806|
   807|---
   808|
   809|## 22. Melanin & Tyrosine Metabolism
   810|
   811|Melanin synthesis from tyrosine; critical for pigmentation and protection against UV damage.
   812|
   813|| Gene | Enzyme / Protein | Key SNP / Variant | Function | Disorder / Clinical Effect | Cofactor |
   814||------|------------------|-------------------|----------|---------------------------|----------|
   815|| **TYR** | Tyrosinase | **p.Arg77* (c.229C>T)**; **p.Arg402Gln (c.1205G>A)**; p.Ser192Tyr (c.575C>A) | Tyrosine → DOPA → dopaquinone | OCA1A (no pigment); OCA1B (temperature-sensitive); amelanotic albinism | **Copper** |
   816|| **OCA2** | P protein (melanosomal transporter) | **p.Phe487Ser (c.1460T>C)**; **p.Arg419* (c.1255C>T)**; 2.7kb deletion (common) | Melanosomal pH/tyrosine transport | OCA2 (most common OCA); pink-eye dilution; African/European ancestry variants | None |
   817|| **TYRP1** | Tyrosinase-related protein 1 | **p.Ser166* (c.497C>G)**; p.Pro174Leu; p.Cys331* | DOPAchrome tautomerase; melanin stabilization | OCA3 (red/rufous albinism); brown OCA; African ancestry | **Copper** |
   818|| **DCT (TYRP2)** | Dopachrome tautomerase | **p.Trp201* (c.603G>A)**; p.Gly478Val | Eumelanin synthesis | Rare OCA variants; melanoma risk modifier | **Zinc** |
   819|| **MC1R** | Melanocortin-1 receptor | **p.Arg151Cys (c.451C>T)** — RHC; **p.Arg160Trp (c.478C>T)** — RHC; **p.Asp294His (c.880G>C)**; p.Val92Met | Eumelanin vs. pheomelanin switch | Red hair, fair skin (R variants); melanoma risk 2-4x; sun sensitivity | None (GPCR) |
   820|| **SLC45A2** | Membrane-associated transporter | **p.Leu374Phe (c.1122G>T)**; **p.Glu272Lys (c.814G>A)**; p.Phe295Leu | Melanosomal function; protein trafficking | OCA4; variable pigmentation; African/European variants | None |
   821|| **SLC24A5** | NCKX5 (sodium/potassium/calcium exchanger) | **rs1426654 (p.Ala111Thr c.536A>G)** | Melanosomal calcium transport; melanocyte maturation | Light skin in Europeans; strong selection; albinism associations | **Calcium** |
   822|| **KITLG** | KIT ligand (SCF) | **rs642742 (5' regulatory)**; rs12821256 | Melanocyte development; migration | Skin pigmentation; blond hair (European); melanoma risk | None |
   823|| **ASIP** | Agouti signaling protein | **rs6058017 (3' UTR)**; rs1015362 | MC1R antagonist; pheomelanin synthesis | Skin/hair color variation; melanoma risk; tanning response | None |
   824|| **IRF4** | Interferon regulatory factor 4 | **rs12203592 (intron)**; rs1540774 | Melanocyte development; pigmentation gene regulation | Freckling; sun sensitivity; hair color; melanoma | None |
   825|| **TYR** | Tyrosinase | **p.Ser192Tyr (c.575C>A)**; p.Arg402Gln (temperature-sensitive) | Catalytic activity | OCA1B; temperature-sensitive pigment production | **Copper** |
   826|| **HPS1** | Hermansky-Pudlak syndrome 1 | **c.972dupC (p.Val325fs)** — Puerto Rican; p.Met325Val | Lysosome-related organelle biogenesis | HPS1; albinism; bleeding; pulmonary fibrosis; Puerto Rican common | None |
   827|| **HPS3** | Hermansky-Pudlak syndrome 3 | **c.1163+1G>A**; p.Pro491Leu | Lysosomal trafficking | HPS3; milder lung disease; Puerto Rican/German | None |
   828|| **HPS4** | Hermansky-Pudlak syndrome 4 | **p.Arg698* (c.2092C>T)**; p.Glu424* | AP-3 complex | HPS4; mild pulmonary involvement | None |
   829|| **MYO5A** | Myosin VA | **p.Arg634* (c.1900C>T)**; large deletions | Melanosome transport | Elejalde syndrome (neuroectodermal); Griscelli syndrome type 1 | None |
   830|| **RAB27A** | RAB27A (GTPase) | **p.Leu58* (c.173T>A)**; p.Arg145Trp | Melanosome transport | Griscelli syndrome type 2; immunodeficiency; HLH | **GTP** |
   831|| **MLPH** | Melanophilin | **p.Arg163* (c.487C>T)**; p.Arg150Trp | Myosin Va anchor | Griscelli syndrome type 3; isolated hypopigmentation | None |
   832|
   833|### Melanin Synthesis Pathway
   834|```
   835|Tyrosine ─TYR/Cu─→ L-DOPA ─TYR/Cu─→ Dopaquinone
   836|                                              ↓
   837|                                    Cyclodopa (leucodopachrome)
   838|                                              ↓
   839|                                    Dopachrome ─DCT/Zn─→ 5,6-dihydroxyindole
   840|                                              ↓
   841|                                    Eumelanin (brown/black)
   842|                                              ─────────────────────────────────────────┘
   843|                                              ↓ Alternative pathway
   844|                                    Cysteinyldopa → Pheomelanin (red/yellow)
   845|```
   846|
   847|### OCA Types Summary
   848|| Type | Gene | Inheritance | Pigment | Vision | Other |
   849||------|------|-------------|---------|--------|-------|
   850|| OCA1A | TYR | AR | None | Severe | Lifelong amelanotic |
   851|| OCA1B | TYR | AR | Temperature-sensitive | Severe | Tyrosine responsive |
   852|| OCA2 | OCA2 | AR | Minimal-moderate | Severe | Most common worldwide |
   853|| OCA3 | TYRP1 | AR | Red-brown | Moderate | Rufous; African common |
   854|| OCA4 | SLC45A2 | AR | Minimal | Severe | Japanese/East Asian |
   855|| HPS1 | HPS1 | AR | Minimal | Moderate | Bleeding; pulmonary fibrosis |
   856|| CHS | LYST | AR | Minimal | Moderate | Immunodeficiency; neuropathy |
   857|
   858|---
   859|
   860|

---

## 23. DNA Repair & Tumor Suppressor Variants

Functionally relevant variants in genes controlling cell cycle, DNA repair, and tumor suppression. These affect cancer risk, treatment response, and DNA damage sensitivity.

### TP53 (Tumor Protein p53) - Guardian of the Genome

| SNP | cDNA Change | Protein Change | Functional Effect | Clinical Impact | Cancer Association |
|-----|-------------|----------------|-------------------|-----------------|-------------------|
| **rs1042522** | c.215C>G | **p.Pro72Arg (Pro/Arg)** | Arg variant = ↑ apoptotic activity but ↓ cell cycle arrest; Pro = better DNA repair | Arg/Arg = ↑ cancer risk (various); Pro/Pro = ↑ longevity, ↑ chemotherapy resistance | Breast, lung, colorectal, prostate |
| **rs17878362** | c.1189+7_1189+8dupA (IVS3 16bp duplication) | Splicing defect (PIN3) | Affects p53 isoform expression | Risk modifier; interacts with other variants | Breast cancer risk |
| **rs1625895** | c.74+38A>C (Intron 2) | Regulatory | Affects p53 expression levels | Modulates cancer risk | Various cancers |
| **rs12947788** | c.-29C>A (Promoter) | Transcriptional | ↑ or ↓ p53 expression | Risk modifier | Colorectal cancer |
| **rs8079544** | c.13494G>C (3'UTR) | mRNA stability | Affects mRNA turnover | Risk modifier | Hepatocellular carcinoma |

#### TP53 Pro72Arg Clinical Interpretation
| Genotype | Population Frequency | Effect | Clinical Considerations |
|----------|---------------------|--------|------------------------|
| **Pro/Pro** | ~35% Caucasian | ↑ DNA repair; ↓ apoptosis | Better DNA damage response; may resist chemotherapy; ↑ longevity |
| **Pro/Arg** | ~45% Caucasian | Intermediate | Balanced phenotype; standard cancer risk |
| **Arg/Arg** | ~20% Caucasian | ↑ Apoptosis; ↓ cell cycle arrest | ↑ Cancer susceptibility; better chemotherapy response |

**Population Differences:**
- Arg72 more common in African populations (~60%)
- Pro72 more common in European populations (~70%)

### MDM2 (p53 Negative Regulator)
| SNP | Location | Effect | Clinical Impact |
|-----|----------|--------|-----------------|
| **rs2279744** | Promoter (SNP309 T>G) | ↑ MDM2 transcription; ↓ p53 activity | ↑ Cancer risk; earlier tumor onset; ↑ chemoresistance |

### BRCA1 / BRCA2 (Homologous Recombination Repair)
| Gene | Key Variants | Effect | Clinical Impact |
|------|--------------|--------|-----------------|
| **BRCA1** | c.68_69delAG; c.5266dupC; c.181T>G | Pathogenic LOF | ↑ Breast (60-70%), ovarian (40-50%) cancer risk; PARP inhibitor sensitive |
| **BRCA2** | c.9097_9098del; c.771_775del; c.9382C>T | Pathogenic LOF | ↑ Breast (50%), ovarian (15%), prostate, pancreatic; PARP inhibitor sensitive |

### ATM (Ataxia Telangiectasia Mutated) - DNA Damage Sensor
| SNP | cDNA/Protein | Effect | Clinical Impact |
|-----|--------------|--------|-----------------|
| **rs1801516** | c.5557G>A (p.Asp1853Asn) | Reduced kinase activity | ↑ Breast cancer risk; radiosensitivity; ataxia telangiectasia if compound het |
| **rs3092992** | c.-111G>A (Promoter) | ↓ ATM expression | Cancer risk modifier | 
| **rs664677** | Intronic | Splicing modulation | Lymphoma risk |

### XRCC1 (Base Excision Repair)
| SNP | cDNA/Protein | Effect | Clinical Impact |
|-----|--------------|--------|-----------------|
| **rs1799782** | c.26304C>T (p.Arg194Trp) | ↓ DNA repair efficiency | ↑ Cancer risk with carcinogen exposure; radiation sensitivity |
| **rs25487** | c.1196A>G (p.Arg399Gln) | Altered repair kinetics | Cancer risk modifier; platinum chemotherapy response |

### ERCC1 (Nucleotide Excision Repair)
| SNP | cDNA/Protein | Effect | Clinical Impact |
|-----|--------------|--------|-----------------|
| **rs11615** | c.354T>C (p.Asn118Asn, synonymous) | ↓ ERCC1 expression | ↑ Platinum sensitivity; better ovarian cancer outcomes |
| **rs3212986** | 3'UTR | mRNA stability | Platinum response modifier |

### GST Family (Detoxification & DNA Protection)
| Gene | Key Variants | Effect | Clinical Impact |
|------|--------------|--------|-----------------|
| **GSTM1** | Gene deletion (*0/*0) | No enzyme | ↑ Cancer risk (various); ↑ sensitivity to alkylating agents |
| **GSTT1** | Gene deletion (*0/*0) | No enzyme | ↑ Cancer risk; busulfan toxicity risk |
| **GSTP1** | rs1695 (p.Ile105Val) | ↓ activity | Cancer risk modifier; platinum response |

### Clinical Application of DNA Repair Variants
| Clinical Scenario | Key Genes | Action |
|-------------------|-----------|--------|
| **High-dose chemotherapy** | TPMT, DPYD, GSTs | Dose adjust to prevent toxicity |
| **Radiation therapy** | ATM, XRCC1 | Monitor for enhanced toxicity |
| **PARP inhibitor therapy** | BRCA1/2, ATM, PALB2 | Identify responders |
| **Platinum-based therapy** | ERCC1, XRCC1, GSTP1 | Predict resistance/sensitivity |
| **Cancer risk assessment** | TP53, BRCA1/2, ATM | Enhanced screening protocols |


## Query Response Patterns
   861|
   862|### Pattern A: "What does [SNP] in [GENE] do?"
   863|1. Identify the gene family/ pathway from tables above
   864|2. State the rs number if known
   865|3. Describe the biochemical effect (kinetic change, expression change, thermolability)
   866|4. Note the phenotype (PM/IM/EM/UM for CYPs; enzymatic % activity for others)
   867|5. List clinical implications (drug dose, nutrient requirement, disease risk)
   868|6. Mention cofactors that may compensate if relevant
   869|
   870|### Pattern B: "Which enzymes are in the [pathway]?"
   871|1. Name the pathway from the metabolic flow diagrams
   872|2. List each enzyme in sequence
   873|3. Note rate-limiting / regulated steps
   874|4. Mention key SNPs that bottleneck the pathway
   875|5. Note required cofactors (B vitamins, minerals, SAM, etc.)
   876|
   877|### Pattern C: "How does [Pathway A] interact with [Pathway B]?"
   878|1. Identify shared intermediates (e.g. SAM links folate + methylation + phosphatidylcholine)
   879|2. Identify competing reactions for the same substrate
   880|3. Note transcriptional co-regulation if known
   881|4. Describe the clinical scenario where one pathway's SNP burdens the other
   882|
   883|### Pattern D: "What should I watch for with [gene variant]?"
   884|1. State the variant's metabolic consequence
   885|2. List drug classes affected (if any)
   886|3. List nutrient supports or antagonists
   887|4. Note contraindicated or dose-adjust medications
   888|5. Suggest monitoring parameters (homocysteine, ammonia, drug levels)
   889|
   890|---
   891|
   892|## Important Caveats
   893|- Always remember: **"Very few single SNPs have actionable consequences"** (Opus23 principle). Most phenotypes require multi-SNP haplotype/epistatic analysis.
   894|- CYP phenotyping requires *activity score* methodology (CPIC guidelines), not single-SNP calls.
   895|- Population frequencies matter: a "rare" variant in one ancestry may be common in another.
   896|- This skill provides **reference information only**, not diagnosis or prescribing guidance. The licensed clinician (Walker) approves all clinical decisions.
   897|- For complex patients, recommend **multi-gene pharmacogenomic panel** (e.g. Genomind, Tempus, GeneSight, or Opus23 Pro import) rather than single-SNP interpretation.
   898|
   899|---
   900|
   901|## External References
   902|- CPIC (Clinical Pharmacogenetics Implementation Consortium): cpicpgx.org
   903|- PharmGKB: pharmgkb.org
   904|- dbSNP / ClinVar: ncbi.nlm.nih.gov
   905|- KEGG Pathway: genome.jp/kegg/pathway.html
   906|- Reactome: reactome.org
   907|- Opus23 Pro (Datapunk): runs 300+ algorithms on multi-SNP clusters with pathway mapping (MAPPER), pharmacogenomics (DRUGGIE), and natural product matching (PSYCHIC) — licensed physician platform
   908|
   909|---
   910|*Skill version 1.3 — comprehensive update with clinically relevant SNPs (rs numbers, cDNA/protein changes) for all 22 pathway sections. All enzymes now include specific actionable variants, allele frequencies where relevant, and CPIC/guideline-backed pharmacogenomic annotations.*
   911|