TITLE
Comparing various Machine Learning models used to Detect and Diagonize Breast Cancer

ABSTRACT

The main purpose of this project is to compare the performance of various machine learning classification models on Breast Cancer Dataset. Accuracy, Precision and F1 scores are calculated for every model. ROC curves and Precision-Recall curves are plotted for every ML model. Based on the Accuracy and F1 scores of the various models, the best ML model is chosen for the classification purpose of Breast Cancer.

INTRODUCTION

Classification models used for this project are:
                   
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. K Nearest Neighbor
5. Support Vector Machine
6. Naive Bayes

About Dataset:

The dataset used for this project is Breast Cancer Wisconsin Data Set. It contains 569 instances of tumour samples and 33 features. 'Diagnosis' feature is our target label which uses 'M' and 'B' variables to classify the input tumour sample. 'M' represents Malignant and is used to represent cancerous tumours. 'B' represents Benign and is used to represent non-cancerous tumours. Dataset used in this project can be found here: https://www.kaggle.com/uciml/breast-cancer-wisconsin-data

PROJECT

Exploratory Data Analysis:

-Missing values: There is a feature named 'Unnamed: 32' which contains 'NaN' in its entire                  column. So, it is removed. The column 'id' is also removed. 

-'Diagnosis' feature is of 'object' type, so it is converted into 'int' type. Here in this   project, 'B' and 'M' label variables are converted into '0' and '1' respectively. Therefore,   0 represents Benign tumour and 1 represents Malignant tumour.

-In total, there are 357 Benign tumours and 212 Malignant tumours in the dataset.

-Correlation between various features is found out and a heatmap is plotted.

Training and Test set:

-70% of the data is taken as training data set and 30% of the data is taken as test data set.
 random_state is taken as 0.

-Training and Test data are scaled before fitting the model.

VISUALIZATIONS

-ROC curves and Precision-Recall curves are plotted for every model.

-Group bar plot is plotted for Accuracy and F1 scores of every model.

RESULTS

-For Logistic Regression, an Accuracy of 1 and F1 score of 1 is obtained. Also, the area under  the ROC curve is 1. So, Logistic Regression model works best for this classification purpose. 

-For DecisionTreeClassifier, an Accuracy of 0.988 and F1 score of 0.983 is obtained. The area   under the ROC curve is 0.984.

-For RandomForestClassifier, an Accuracy of 1 and F1 score of 1 is obtained. Also, the area  under the ROC curve is 1. So, Random Forest also works best for this classification purpose.

-For KNN, an Accuracy of 0.947 and F1 score of 0.923 is obtained. The area under the curve  obtained is 0.928.

-For SVM, an Accuracy of 0.976 and F1 score of 0.967 is obtained. The area under the curve is  0.968.

-For Naive Bayes, an Accuracy of 0.936 and F1 score of 0.912 is obtained. The area under the  ROC curve is 0.929.  

CONCLUSION

From the above results, one can conclude that Logistic Regression and Random Forest Classifier models work best for the classification purpose of Breast Cancer. 






