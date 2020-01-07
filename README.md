EEG Seizure Analysis 

Project Goal: 
     To predict whether a given EEG reading would lead to a seizure or not.

Kaggle dataset source: https://www.kaggle.com/harunshimanto/epileptic-seizure-recognition

Prediction Algorithms Tested:
linearSVM
multiclass KNN
binary class LDA
binary class tf-ANN
multiclass tf-ANN
logistic regression

Issues:
There was relative problems with inflated accuracy values (LDA, logistic regression, first trial of SVM). 

Potential Resolve:
Utilizing subsampling of the data to get a balance between the two classes before training and testing. 

Moving Forward:
There is definitely potential to improve and implement in a real BCI. A real BCI environment that runs on streaming data and a system that tailors responses to patient. 


