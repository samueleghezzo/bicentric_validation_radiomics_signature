# **Bicentric Validation of Radiomics Signature**

This repository contains code and resources used in the paper "The Challenge of External Generalisability: Insights from the Bicentric Validation of a [68Ga]Ga-PSMA-11 PET Based Radiomics Signature for Primary Prostate Cancer Characterisation Using Histopathology as Reference".

**Overview**

This repository includes two fully trained machine learning models developed in the study Role of "[68Ga]Ga-PSMA-11 PET Radiomics to Predict Post-Surgical ISUP Grade in Primary Prostate Cancer" and in this paper. 

**Models**

svm_model_trained_on_hsr.joblib
- This is a Support Vector Machine (SVM) model trained on a cohort of 47 patients from San Raffaele Hospital. The model uses two radiomics features, "original_glszm_ZoneEntropy" and "original_shape_LeastAxisLength", as input for predicting ISUP grade.

trained_bicentric_rdx_model.joblib
- This is a Random Forest Classifier trained on 127 patients enrolled at San Raffaele Hospital (62 patients) and at Stanford Hospital (65 patients). The model uses four radiomics features, "original_glcm_ClusterProminence", "original_firstorder_Energy", "original_shape_VoxelVolume", "original_glszm_LargeAreaEmphasis", as input for predicting ISUP grade.
