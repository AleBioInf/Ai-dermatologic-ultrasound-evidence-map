# Operational definitions

- **Internal validation:** random/stratified split, cross-validation, or holdout derived from the same institution/cohort/data source.
- **External image-set test:** evaluation on an image set outside the development split, but not necessarily a prospectively acquired independent clinical cohort.
- **Cross-centre/device technical validation:** technical validation across different machines, datasets, or centres, typically for segmentation/measurement.
- **Strict external clinical validation:** independent patient cohort from different centre(s), held out from development, evaluating the same clinical task.
- **Prospective multicentre validation:** prospectively enrolled/tested independent clinical cohort across >1 centre after model development.
- **Public study-specific code/repository:** a public repository specific to the study is identifiable; completeness is assessed separately.
- **Complete open reproducibility package:** public study-specific code + public study-specific trained model/weights + public evaluation data.
- **Study-specific full data public:** the full study analysis dataset is openly accessible.
- **Confirmed dataset reuse:** direct evidence that at least two publications use the same source dataset or an explicitly expanded version. Shared authorship alone is insufficient.
- **Point-of-care workflow:** AI is integrated into a real-time or near-real-time clinical ultrasound workflow within the publication.
- **Routine clinical deployment:** published evidence that the exact AI system is used in routine care beyond a research evaluation.
