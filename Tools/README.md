# Bias, variance decomposition tool
This tool enables the estimation of the loss in error derived from filtering samples of dubious quality from the training set. It requires reference samples (y-labels) and predictions made with a trained classifier (x-labels).

# SHAP_Feature_Contributions
The GCC model's feature importance's file computes the predictive performance of a model by detracting a single feature from the set of features to estimate their predictive importance. 

This tool applies SHAP values (SHapley Additive exPlanations) to determine the importance of a single feature to the overall predicitive capacity of a model. The GCC model takes advanatage of the localized precision of SHAP values to determine which features expedite the highest predictive capacity of land use classes. 

Data input: Datasets and georeferenced files can be found in our Mendeley repository (https://data.mendeley.com/datasets/mzp3k6fmtz/5) under GCC model > codes > Feature Importances_SHAP.

# User's Guide I & II
User's Guide I: Step-wise guide to facilitate the accumulation of regional data metrics for automated label supervision. 
User's Guide II: Step-wise guide to source incrementally-reliable regional training datasets.

# Additional Information
We recommend use of raw multitemporal metrics given the frequency of amplitude signals carefully derived from Sentinel-2 satellite images. Optionally, new metric samples can be easily retrieved following our User's Guide I and candidate training samples can be gathered following our User's Guide II.

For collaborations, contact us at: globalgroundcoverchange@gmail.com
