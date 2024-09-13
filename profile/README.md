## Overview

Welcome to the Duke AI Health Data Science Fellowship repository. Our projects focus on various aspects of healthcare data analysis, machine learning, and AI implementation in clinical settings.

Below is a summary of the available sub-repositories and folders, each covering different aspects of the fellowship's work. Part I contains stand-alone functions/notebooks that can be used for other projects. Part II contains example projects that utilize one or more functions in the first part. The first part will reference the projects in the second part.

## Summary Table


## Part I: Data Science/AI Tools

| Title                                                         | Reference project |
|---------------------------------------------------------------|--------------------|
| [0. Best practice](https://github.com/duke-aihealth-ds-fellowship/best-practice) |
| [1. Feature engineering](https://github.com/duke-aihealth-ds-fellowship/1-feature-engineering) |	|
| - 1.1 Demographics (sex, race-eth, payer, encounter type, etc.) |	|
| - 1.2 Diagnosis and Procedure codes to CCS |	|
| - 1.3 Diagnosis and Procedure codes to embeddings | [P1](https://github.com/duke-aihealth-ds-fellowship/conditional-multilabel-model) |
| - 1.4 Vital signs | [P1](https://github.com/duke-aihealth-ds-fellowship/conditional-multilabel-model) |
| - 1.5 Lab results |	|
| - 1.6 Medications |	|
| - 1.7 Doctor notes |	|
| [2. Data processing and simulation techniques](https://github.com/duke-aihealth-ds-fellowship/2-data-processing) |	|
| - 2.1 Common Pipeline (normalization, etc.) |	|
| - 2.2 Handling Missing Data (imputation techniques) | [P7](https://github.com/duke-aihealth-ds-fellowship/longitudinal-missingness-embedding) |
| - 2.3 Sampling Methods for Imbalanced Data |
| - 2.4 Structured Data Simulation | [P1](https://github.com/duke-aihealth-ds-fellowship/conditional-multilabel-model) |
| - 2.5 Observability Estimation |	|
| - 2.6 Formatting Sequence Data in Pytorch | [7](https://github.com/duke-aihealth-ds-fellowship/pytorch-template) |
| [3. Modeling](https://github.com/duke-aihealth-ds-fellowship/3-modeling) |	|
| - 3.1 Hyperparameter tuning (Optuna) | [7](https://github.com/duke-aihealth-ds-fellowship/pytorch-template) |
| - 3.2 Pytorch Embedding Models | [7](https://github.com/duke-aihealth-ds-fellowship/pytorch-template) |
| - 3.3 Multi-Label Classification Tutorial |	|
| - 3.4 Conditional Multi-Label Classification | [P1](https://github.com/duke-aihealth-ds-fellowship/conditional-multilabel-model) |
| - 3.5 Discrete Time Neural Survival Model |	|
| - 3.6 Contrastive Learning |	|
| - 3.7 Transfer Learning |	|
| [4. NLP](https://github.com/duke-aihealth-ds-fellowship/4-nlp) |	|
| - 4.1 TF-IDF and Other Traditional NLP Methods |	|
| - 4.2 Train Tokenizers in HuggingFace |	|
| - 4.3 Pretraining a HuggingFace Model |	|
| - 4.4 LLM (GPT, BERT) Finetuning and Prediction |	|
| [5. Model evaluation](https://github.com/duke-aihealth-ds-fellowship/5-model-evaluation) |	|
| - 5.1 Common metrics, e.g., AUC, AP, ROC, PR | [7](https://github.com/duke-aihealth-ds-fellowship/pytorch-template) |
| - 5.2 Bootstrapping |	[7](https://github.com/duke-aihealth-ds-fellowship/pytorch-template) |
| - 5.3 Stratifying Metrics by Subsets |	|
| - 5.4 Forest plots |	|
| [6. Feature importance](https://github.com/duke-aihealth-ds-fellowship/6-feature-importance) |	|
| - 6.1 Shap values for embedding models |	|
| - 6.2 Regressed shap values |	|
| [7. Pytorch template](https://github.com/duke-aihealth-ds-fellowship/pytorch-template) |	|

## Part II: Projects and Case Studies

| Title                                                                                     |
|-------------------------------------------------------------------------------------------|
| [P1 Conditional Multi-label Model to Boost Rare Event Classification](https://github.com/duke-aihealth-ds-fellowship/conditional-multilabel-model) |
| [P2 Navigating the manifold of single-cell gene coexpression to discover interpretable gene programs.] | <(https://github.com/duke-aihealth-ds-fellowship/navigating-single-cell-gene-coexpression)>
| [P3 Fusion protein design optimization: first steps towards a computational approach] | <(https://github.com/duke-aihealth-ds-fellowship/fusion-protein-design-optimization)>
| [P4 ABCD - Forecasting adolescent mental health] | <(https://github.com/duke-aihealth-ds-fellowship/abcd-forecasting-adolescent-mental-health)>
| [P5 Longitudinal EHR-based ADHD/autism prediction] | <(https://github.com/duke-aihealth-ds-fellowship/longitudinal-ehr-based-adhd-autism-prediction)>
| [P6 Majority-Guided Variational Autoencoder](https://github.com/duke-aihealth-ds-fellowship/majority-guided-vae) |
| [P7 Longitudinal Missingness Embedding (TF/Keras)](https://github.com/duke-aihealth-ds-fellowship/longitudinal-missingness-embedding) |



## How to Navigate

Each title in the table above links to a specific repository containing code, documentation, and data (when necessary) related to that aspect of data analysis. Click on any title to explore more.