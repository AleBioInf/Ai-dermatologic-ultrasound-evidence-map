# Workflow

1. Run the final PubMed/MEDLINE and Scopus searches.
2. Export all records without date/language/document-type restrictions.
3. Deduplicate across databases: normalized DOI first; exact normalized title second when DOI is absent or unmatched.
4. Screen titles/abstracts against prespecified eligibility criteria.
5. Review full texts for potentially eligible studies.
6. Perform backward/forward citation chasing and dataset-lineage chasing to identify studies missed by terminology-sensitive database queries.
7. Extract study design, cohort size, ultrasound modality/device, AI task/model, ground truth, validation strategy, transparency/reproducibility variables, dataset lineage, and implementation status.
8. Separate the **whole-field corpus (n=35)** from the **core clinical subset (n=23)**.
9. Quantify external validation, prospective multicentre evaluation, open code/data, reproducibility, dataset reuse, point-of-care integration, and routine deployment using conservative operational definitions.

This repository is a **structured evidence map**, not a registered systematic review. The current database scope is PubMed/MEDLINE + Scopus, supplemented by citation chasing.
