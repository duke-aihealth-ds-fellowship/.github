## Overview

Welcome to the Duke AI Health Data Science Fellowship repository. Our projects focus on various aspects of healthcare data analysis, machine learning, and AI implementation in clinical settings.

Below is a summary of the available sub-repositories and folders, each covering different aspects of the fellowship's work. Part I contains stand-alone functions/notebooks that can be used for other projects. Part II contains example projects that utilize one or more functions in the first part. The first part will reference the projects in the second part.

## Summary Table


## Part I: Data Science/AI Tools

| Title                                                         | People in charge | Reference Project | Status                | Notes                                |
|---------------------------------------------------------------|------------------|-------------------|-----------------------|--------------------------------------|
| [1. Feature engineering (please indicate source data is CRDM or others)](https://github.com/duke-aihealth-ds-fellowship/repo_1_feature_engineering) |                  |                   |                       |                                      |
| - [1.1 Demographics (sex, race-eth, payer, encounter type, etc.)](https://github.com/duke-aihealth-ds-fellowship/repo_1_feature_engineering/tree/main/1.1_demographics) |                  |                   |                       |                                      |
| - [1.2 Diagnosis and Procedure codes to CCS](https://github.com/duke-aihealth-ds-fellowship/repo_1_feature_engineering/tree/main/1.2_diagnosis_and_procedure_codes_to_ccs) | Angel            |                   | Completed             |                                      |
| - [1.3 Diagnosis and Procedure codes to embeddings](https://github.com/duke-aihealth-ds-fellowship/repo_1_feature_engineering/tree/main/1.3_diagnosis_and_procedure_codes_to_embeddings) | Angel            |                   | Completed             |                                      |
| - [1.4 Vital signs](https://github.com/duke-aihealth-ds-fellowship/repo_1_feature_engineering/tree/main/1.4_vital_signs) | Angel            |                   | Completed             | Very basic, others can add           |
| - [1.5 Lab results](https://github.com/duke-aihealth-ds-fellowship/repo_1_feature_engineering/tree/main/1.5_lab_results) |                  |                   |                       |                                      |
| - [1.6 Medications](https://github.com/duke-aihealth-ds-fellowship/repo_1_feature_engineering/tree/main/1.6_medications) |                  |                   |                       |                                      |
| - [1.7 Doctor notes](https://github.com/duke-aihealth-ds-fellowship/repo_1_feature_engineering/tree/main/1.7_doctor_notes) |                  |                   |                       |                                      |
| - [1.8 Sequence data in pytorch](https://github.com/duke-aihealth-ds-fellowship/repo_1_feature_engineering/tree/main/1.8_sequence_data_in_pytorch) | Elliot           |                   |                       |                                      |
| [2. Data processing and simulation techniques](https://github.com/duke-aihealth-ds-fellowship/repo_2_data_processing_and_simulation_techniques) |                  |                   |                       |                                      |
| - [2.1 Common Pipeline (normalization, etc.)](https://github.com/duke-aihealth-ds-fellowship/repo_2_data_processing_and_simulation_techniques/tree/main/2.1_common_pipeline) | Elliot           |                   |                       | This is going to vary a lot by project |
| - [2.2 Handling Missing Data (imputation techniques)](https://github.com/duke-aihealth-ds-fellowship/repo_2_data_processing_and_simulation_techniques/tree/main/2.2_handling_missing_data) | Scott            |                   |                       |                                      |
| - [2.3 Sampling Methods for Imbalanced Data](https://github.com/duke-aihealth-ds-fellowship/repo_2_data_processing_and_simulation_techniques/tree/main/2.3_sampling_methods_for_imbalanced_data) | Scott            |                   |                       |                                      |
| - [2.4 Structured Data Simulation](https://github.com/duke-aihealth-ds-fellowship/repo_2_data_processing_and_simulation_techniques/tree/main/2.4_structured_data_simulation) | Angel/Qin        | P1                | Completed             |                                      |
| - [2.5 Observability estimation](https://github.com/duke-aihealth-ds-fellowship/repo_2_data_processing_and_simulation_techniques/tree/main/2.5_observability_estimation) | Mengying         |                   |                       |                                      |
| - [2.6 Formatting sequence data in pytorch](https://github.com/duke-aihealth-ds-fellowship/repo_2_data_processing_and_simulation_techniques/tree/main/2.6_formatting_sequence_data_in_pytorch) | Elliot           |                   |                       |                                      |
| [3. Modeling](https://github.com/duke-aihealth-ds-fellowship/repo_3_modeling) |                  |                   |                       |                                      |
| - [3.0 Pytorch project template](https://github.com/duke-aihealth-ds-fellowship/repo_3_modeling/tree/main/3.0_pytorch_project_template) | Elliot           |                   |                       |                                      |
| - [3.1 Hyperparameter tuning (Optuna)](https://github.com/duke-aihealth-ds-fellowship/repo_3_modeling/tree/main/3.1_hyperparameter_tuning_optuna) | Elliot           |                   |                       |                                      |
| - [3.2 Multi-label Classification tutorial](https://github.com/duke-aihealth-ds-fellowship/repo_3_modeling/tree/main/3.2_multi-label_classification_tutorial) | Yuqi             |                   |                       |                                      |
| - [3.3 Multi-Label Classification](https://github.com/duke-aihealth-ds-fellowship/repo_3_modeling/tree/main/3.3_multi-label_classification) | Qin              |                   |                       |                                      |
| - [3.4 Conditional Multi-Label Classification](https://github.com/duke-aihealth-ds-fellowship/repo_3_modeling/tree/main/3.4_conditional_multi-label_classification) | Angel            | P1                | Completed             |                                      |
| - [3.5 Pytorch Embedding models](https://github.com/duke-aihealth-ds-fellowship/repo_3_modeling/tree/main/3.5_pytorch_embedding_models) | Elliot           |                   |                       |                                      |
| - [3.6 Transfer Learning](https://github.com/duke-aihealth-ds-fellowship/repo_3_modeling/tree/main/3.6_transfer_learning) | Mengying         |                   |                       |                                      |
| - [3.7 Time-to-event (survival analysis) in pytorch](https://github.com/duke-aihealth-ds-fellowship/repo_3_modeling/tree/main/3.7_time-to-event_in_pytorch) | Elliot           |                   |                       |                                      |
| - [3.8 Discrete Time Survival Neural Network in pytorch](https://github.com/duke-aihealth-ds-fellowship/repo_3_modeling/tree/main/3.8_discrete_time_survival_neural_network_in_pytorch) | Angel            |                   |                       |                                      |
| [4. NLP](https://github.com/duke-aihealth-ds-fellowship/repo_4_nlp) |                  |                   |                       |                                      |
| - [4.1 TF-IDF and Other Traditional NLP Methods](https://github.com/duke-aihealth-ds-fellowship/repo_4_nlp/tree/main/4.1_tf-idf_and_other_traditional_nlp_methods) |                  |                   |                       |                                      |
| - [4.2 Pre-trained Models Prediction (GPT, BERT) without finetuning](https://github.com/duke-aihealth-ds-fellowship/repo_4_nlp/tree/main/4.2_pre-trained_models_prediction_without_finetuning) |                  |                   |                       |                                      |
| - [4.3 Finetune LLM](https://github.com/duke-aihealth-ds-fellowship/repo_4_nlp/tree/main/4.3_finetune_llm) |                  |                   |                       |                                      |
| [5. Model evaluation](https://github.com/duke-aihealth-ds-fellowship/repo_5_model_evaluation) |                  |                   |                       |                                      |
| - [5.1 Common metrics, e.g., AUC, AP, ROC, PR](https://github.com/duke-aihealth-ds-fellowship/repo_5_model_evaluation/tree/main/5.1_common_metrics) | Elliot           |                   |                       |                                      |
| - [5.2 Bootstrapping](https://github.com/duke-aihealth-ds-fellowship/repo_5_model_evaluation/tree/main/5.2_bootstrapping) | Elliot           |                   |                       |                                      |
| - [5.3 Stratifying metrics by subsets](https://github.com/duke-aihealth-ds-fellowship/repo_5_model_evaluation/tree/main/5.3_stratifying_metrics_by_subsets) | Elliot           |                   |                       |                                      |
| - [5.4 Forest plots](https://github.com/duke-aihealth-ds-fellowship/repo_5_model_evaluation/tree/main/5.4_forest_plots) |                  |                   |                       |                                      |
| [6. Feature importance](https://github.com/duke-aihealth-ds-fellowship/repo_6_feature_importance) |                  |                   |                       |                                      |
| - [6.1 Shap values for embedding models](https://github.com/duke-aihealth-ds-fellowship/repo_6_feature_importance/tree/main/6.1_shap_values_for_embedding_models) | Elliot           |                   |                       |                                      |
| - [6.2 Regressed shap values](https://github.com/duke-aihealth-ds-fellowship/repo_6_feature_importance/tree/main/6.2_regressed_shap_values) | Elliot           |                   |                       |                                      |

## Part II: Projects and Case Studies

| Title                                                                                     | People in charge | Reference Project | Status       | Notes |
|-------------------------------------------------------------------------------------------|------------------|-------------------|--------------|-------|
| [P1 Conditional Multi-label Model to Boost Rare Event Classification](https://github.com/duke-aihealth-ds-fellowship/repo_p1_conditional_multi-label_model_to_boost_rare_event_classification) | Angel            |                   | Completed    |       |
| [P2 Navigating the manifold of single-cell gene coexpression to discover interpretable gene programs.](https://github.com/duke-aihealth-ds-fellowship/repo_p2_navigating_single-cell_gene_coexpression) | Aditya           |                   | Completed    |       |
| [P3 Fusion protein design optimization: first steps towards a computational approach](https://github.com/duke-aihealth-ds-fellowship/repo_p3_fusion_protein_design_optimization) | Aditya           |                   | In-Progress  |       |
| [P4 ABCD - Forecasting adolescent mental health](https://github.com/duke-aihealth-ds-fellowship/repo_p4_abcd_forecasting_adolescent_mental_health) | Elliot           |                   | In-Progress  |       |
| [P5 Longitudinal EHR-based ADHD/autism prediction](https://github.com/duke-aihealth-ds-fellowship/repo_p5_longitudinal_ehr-based_adhd_autism_prediction) | Elliot           |                   |              |       |





## How to Navigate

Each title in the table above links to a specific subfolder within the repository containing code, documentation, and data (when necessary) related to that aspect of data analysis. Click on any title to explore more.
