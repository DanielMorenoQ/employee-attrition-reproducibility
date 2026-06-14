# Employee Attrition Reproducibility Artifact

This repository is reserved for the reproducibility artifact associated with the paper:

**Predicting Software Engineer Attrition Risk Using Machine Learning and AutoML: A Case Study with HR Data**

## Current Status

The reproducibility artifacts are **not uploaded yet**.

Publication of the synthetic dataset and supporting analysis files is pending company approval. Until that approval is granted, this repository intentionally contains only documentation.

## Planned Contents

If approved, this repository will contain:

- A synthetic HR attrition dataset with English column names.
- A script for regenerating the synthetic dataset.
- A Jupyter notebook that reproduces the preprocessing and evaluation workflow.
- Minimal dependency files needed to run the notebook.

## Privacy Boundary

This repository will not include:

- Real employee records.
- Private HR datasets.
- Company identifiers.
- Uploaded HR files.
- Prediction exports.
- Trained production models.
- Databases or application storage.
- Private web application or backend source code.

The planned dataset is synthetic and intended only to support reproducibility of the paper's data-processing and model-evaluation workflow. It is not a row-level anonymization or perturbation of private employee records.

## Intended Reproducibility Scope

The public artifact is intended to help reviewers and researchers inspect:

- The expected dataset schema.
- The target-definition logic.
- The preprocessing steps.
- The fixed machine learning pipeline selected through AutoML.
- The repeated train/test evaluation procedure.

Synthetic-data results should not be interpreted as evidence of real-world deployment performance. The empirical case-study results reported in the paper are based on a private HR dataset that cannot be released publicly.

## Approval Notice

Artifacts will be added only after authorization is obtained to publish synthetic data and supporting reproducibility code.
