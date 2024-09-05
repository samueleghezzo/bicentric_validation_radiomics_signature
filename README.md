# **Bicentric Validation of Radiomics Signature**

This repository contains code and resources used in the paper <TO_BE_UPDATED_AFTER_PUBLICATION>.

**Overview**

This repository includes two Jupyter notebooks and a fully trained machine learning model developed in the study Role of "[68Ga]Ga-PSMA-11 PET Radiomics to Predict Post-Surgical ISUP Grade in Primary Prostate Cancer". 

**Notebooks**

aim_1_fully_trained_model_validation.ipynb
- This notebook contains the code used to achieve the first aim of the study. Specifically, it validates the fully trained model from the previous study (doi:10.1007/s00259-023-06187-3) on a larger internal cohort, an external independent cohort, and a combined cohort. This step is crucial for evaluating the generalizability of the model.

aim_2_newly_trained_models.ipynb
- This notebook covers the second aim of the study. Here, the radiomics features identified in the previous investigation are utilized as inputs for several newly trained machine learning models, applied to the cohorts explored in this study.

**Model**

svm_model_trained_on_hsr.joblib
- This is a Support Vector Machine (SVM) model trained on a cohort of 47 patients from San Raffaele Hospital. The model uses two radiomics features, "original_glszm_ZoneEntropy" and "original_shape_LeastAxisLength", as input for predicting outcomes. This model serves as a key component in the analysis described in the paper.
