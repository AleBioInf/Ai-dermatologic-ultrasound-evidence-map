# AI-Enhanced Ultrasound in Dermatology — Structured Evidence Map

Reproducibility package for a structured evidence mapping of **artificial intelligence / machine learning / deep learning applied to dermatologic ultrasound**.

**Search date:** 1 September 2026  
**Databases:** PubMed/MEDLINE + Scopus  
**Additional identification:** backward/forward citation chasing and dataset-lineage chasing.

## Current evidence base

- **324** PubMed/MEDLINE records
- **6,412** Scopus records
- **6,523** unique records after cross-database deduplication
- **35** original studies in the final whole-field corpus
- **23** disease-oriented **core clinical** studies

Conservative translational findings in the core clinical subset:

- **1/23 (4.3%)** strict external clinical validation
- **1/23 (4.3%)** prospective multicentre validation
- **4/23 (17.4%)** public study-specific code/repository identified
- **0/23** complete open reproducibility packages
- **5/23 (21.7%)** full study-specific datasets publicly available
- **0/23** published point-of-care AI workflow within the core-clinical subset
- **0/23** published routine clinical deployment
- **6/23 (26.1%)** belong to directly confirmed dataset-reuse clusters

The central methodological distinction is that **publication count is not equivalent to independent clinical evidence**. Dataset reuse and internal-only validation are tracked explicitly.

## Repository structure

```text
AI_Dermatologic_Ultrasound_GitHub/
├── README.md
├── .gitignore
├── queries/
│   ├── PubMed_MEDLINE_query_2026-09-01.txt
│   ├── Scopus_query_2026-09-01.txt
│   └── SEARCH_NOTES.md
├── raw_search_exports/
│   ├── PubMed_MEDLINE_export_2026-09-01.txt
│   └── Scopus_export_2026-09-01.csv
├── data/
│   └── AI_Dermatologic_Ultrasound_Master_Extraction.xlsx
├── methods/
│   ├── WORKFLOW.md
│   ├── ELIGIBILITY_CRITERIA.md
│   ├── OPERATIONAL_DEFINITIONS.md
│   └── DATA_DICTIONARY.md
└── results/
    ├── screening_flow.csv
    ├── key_metrics.csv
    ├── confirmed_dataset_reuse_clusters.csv
    └── evidence_augmentation_log.csv
```

## Definitive workbook

`data/AI_Dermatologic_Ultrasound_Master_Extraction.xlsx` is the authoritative analysis file. It contains:

- master study-level extraction;
- whole-field dashboard (`n=35`);
- core-clinical dashboard (`n=23`);
- conservative slide-ready metrics;
- cohort-reuse audit;
- source audit;
- operational definitions.

## Search strategy rationale

The final PubMed exclusion terms are applied to the **title only**. Applying them to title/abstract caused a known false negative because relevant dermatologic-ultrasound studies can mention breast or other ultrasound applications in their background text.

Citation chasing was retained as a formal component because historical engineering papers often use terminology such as *CAD*, *sonogram*, *neural network*, or frequency analysis rather than modern AI terminology.

## Scope and limitations

This is a **structured evidence map**, not a registered systematic review. The current version independently searches PubMed/MEDLINE and Scopus and supplements them with citation chasing. Embase and IEEE Xplore were not run as separate database searches in this release.

The repository uses conservative definitions of external validation and reproducibility. External image-set testing and cross-device technical validation are intentionally **not** counted as strict external clinical validation.

## Raw Scopus export — licensing note

The raw Scopus export is included in this local package because it is part of the reproducibility workflow. **Before publishing the repository publicly, verify your institutional Scopus/Elsevier licence and redistribution terms.** If redistribution is not permitted, remove the raw Scopus CSV from the public GitHub repository while retaining the exact query, search date, record count, and derived screening data.

## Suggested repository title

`ai-dermatologic-ultrasound-evidence-map`
