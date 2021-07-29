We have uploaded two data files:
1) data.csv contains original data set.
2) final_encoded_data.csv contains encoded data which was necessary for running RandomForestClassifier 
SVM and KNN as the python libraries don't work on categorical data.

Source code description:
1)"imputation_source_code" contains code for imputing data as original data set contains missing values.
2) "encoded_data_source_code" contains source code for encoding data using LabelEncoder.
3) "final_encoding_source_code" contains source code where we convert the problem into binary classification.
4) "feature_selection_igain" contains source code to evaluate features using Information Gain.
5) "pca_code" contains source code to perform PCA to calculate the number of dimensions to capture.
6)"RFE_source_code","IG_source_code" and "ETC_source_code" implements RandomForest and KNN on features selected by
Recursive feature elimination, Information Gain and Extra Trees Classifier respectively.
NOTE: We have separate folder with name "svm_code" which contains source code for implementing SVM on features selected
by Recursive feature elimination, Information Gain and Extra Trees Classifier respectively.Also this folder has output files 
and subset of dataset on which svm should be performed. For running svm please refer "svm_steps.docx" file.