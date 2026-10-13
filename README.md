# qm640-hcv-capstone
Explainable machine learning for hepatitis C–related liver disease classification using routine laboratory data.

**Project Overview**

This QM640 Data Analytics Capstone project investigates the use of explainable machine learning to classify hepatitis C–related liver disease categories using demographic and routine laboratory data.

The study compares statistical and machine learning approaches, evaluates performance across classes and demographic subgroups, and examines model explanations to support transparent research findings.

**Research Objectives**

1. Explore relationships between demographic and laboratory variables and the recorded HCV data categories.
2. Develop and compare multiclass classification models.
3. Evaluate macro-F1, balanced accuracy, class-level precision and recall, and other appropriate metrics.
4. Investigate model interpretability and performance across age and sex subgroups.
5. Document the analysis to support reproducibility.

**Dataset and Attribution**

Source: UCI Machine Learning Repository — HCV Data
Dataset page: https://archive.ics.uci.edu/dataset/571/hcv+data
Dataset licence: CC BY 4.0, as identified by the repository.

The dataset contains 615 records and demographic and laboratory variables, with a categorical outcome. The analysis will exclude the ID field from model predictors and address missing values and class imbalance.

Dataset attribution: Lichtinghagen, R., Klawonn, F., and Hoffmann, G. (2020). HCV data [Data set]. UCI Machine Learning Repository. https://doi.org/10.24432/C5D612 

**Project Structure**

1. data/raw/ — Original downloaded dataset
2. data/processed/ — Processed data, where appropriate
3. notebooks/ — Exploratory analysis and model development
4. figures/ — Figures and visualizations
5. README.md — Project overview and reproducibility instructions
6. requirements.txt — Python dependencies

**Reproducibility**

The project will document data preparation, missing-value handling, model development, cross-validation, evaluation metrics, and explainability methods. Any imputation, scaling, feature selection, or resampling will be fitted within training folds to reduce data leakage.

**Limitations and Responsible Use**

This project is an academic research prototype, not a clinical diagnostic system. Results may be affected by sample size, class imbalance, missing values, and dataset representativeness. Model performance does not establish causation or clinical suitability.

**Academic Context**

Walsh College
QM640: Data Analytics Capstone
Fall 2026 Term
