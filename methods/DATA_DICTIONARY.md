# Master extraction data dictionary

The definitive workbook is `data/AI_Dermatologic_Ultrasound_Master_Extraction.xlsx`.

Key fields:

| Field | Meaning |
|---|---|
| `Study_ID` | Stable study identifier within this repository |
| `Scope` | Core clinical / technical-workflow / aesthetic / physiology-aging / other cutaneous scope |
| `Clinical_domain` | Disease or clinical/technical application |
| `US_modality_frequency` | Ultrasound modality and reported frequency when available |
| `Patients`, `Lesions`, `Images` | Study sample sizes as reported |
| `Design` | Retrospective/prospective/technical/model-development description |
| `Centers_n`, `Countries_n`, `Multisite_Data` | Acquisition/evaluation geography |
| `Task` | Classification, staging, segmentation, measurement, etc. |
| `Model` | AI/ML/DL/radiomics method |
| `Ground_truth` | Histology, expert annotation, clinical labels, etc. |
| `Validation_strategy` | Cross-validation, holdout, external test, prospective validation, etc. |
| `Strict_external_clinical_validation` | Conservative clinical external-validation indicator |
| `Prospective_multicentre_validation` | Prospective multicentre clinical-validation indicator |
| `Public_code_repo` | Study-specific public code/repository identified |
| `Study_specific_weights_public` | Study-specific trained weights/model publicly available |
| `Study_specific_full_data_public` | Full study analysis data publicly available |
| `Dataset_reuse_cluster` | Confirmed dataset-lineage cluster, when applicable |
| `Independent_new_cohort` | Whether the publication contributes an independent new cohort |
| `Point_of_care_workflow` | Integrated real-time/near-real-time AI workflow |
| `Routine_clinical_deployment` | Published routine clinical use |
| `Primary_performance` | Main reported performance summary |
| `Limitations_notes` | Study-specific translational caveats |
| `Primary_source_URL`, `Code_URL`, `Data_URL` | Audit links |
| `Extraction_confidence` | Confidence in extracted fields based on accessible source material |

The workbook also contains dashboards, core-clinical metrics, cohort-reuse audit, operational definitions, and source-audit sheets.
