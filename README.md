# Mirai_Botnet_Detection_Using_Machine_Learning
This research presents a systematic comparative analysis of five diverse machine learning architectures, providing insights into the feature sets most indicative of botnet activity, thereby addressing the lack of interpretability in black-box detection models. 

data_preprocossing.ipynb  : Code that cleans the data and allows for model use.
preprocessing_crossvalidation.ipynb : Code that cleans the data and allows for model use in cross-validation.
training_code.ipynb : Code that trains the models using held-out dataset.
train_crossvalidation.ipynb : Code that trains the models using cross-validation dataset.
test_code.ipynb : Code that evaluates best model from training_code.
test_code_cv.ipynb : Code that evaluates best model from train_crossvalidation.

Classifaction_Report : Classification Report for RF model on held out dataset
Classifaction_Report_CV : Classification Report for RF model on cross-validation dataset
Confusion_Matrix_RF : Confusion Martix for RF model on held out dataset
Confusion_Matrix_RF_CV : Confusion Matrix for RF model on cross-validation dataset

RF_50trees_12depth : RF model
Crossvalid_RF_50trees_12depth : RF model for cross-validation
