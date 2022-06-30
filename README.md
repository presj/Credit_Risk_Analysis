Credit_Risk_Analysis

Overview of the analysis

This challenge involved building and evaluating select machine learning models to predict the credit risk of loan applicants.

Results

One way of validating a model's performance is by its accuracy score. The following is a list of three models for predicting credit risk and their associated accuracy scores and the precision and recall scores:


Resampling model (RandomOverSampler) accuracy score, precision, and recall:

![image](https://user-images.githubusercontent.com/100803302/176680398-c80687b8-bf62-47b8-afe8-9d8ddd37036c.png)
  
SMOTE (Oversampling) accuracy, precision, and recall:

![image](https://user-images.githubusercontent.com/100803302/176679400-fb93339d-367a-4cd3-8b2a-6a6e458f1232.png)

ClusterCentroid: accuracy, precision, and recall:

![image](https://user-images.githubusercontent.com/100803302/176679719-8fda544e-2bbf-496f-88f7-5b7a00a8c0b7.png)

SMOTEENN (Combination Sampling) accuracy score, precision, and recall:

![image](https://user-images.githubusercontent.com/100803302/176680064-67f05368-809a-4aa2-a3cc-bdb73540a130.png)

Ensembler Classifiers (BalancedRandomForestClassifer) accuracy score:

![image](https://user-images.githubusercontent.com/100803302/175836037-63026fcb-0f68-469f-b141-73a55a50d843.png)
  
Ensembler Classifiers (BalancedRandomForestClassifer) precision and recall:

![image](https://user-images.githubusercontent.com/100803302/175837350-7a87067e-d010-41e1-a468-8dbaf5bf6a84.png)

  

Summary 

Of the three models reviewed, the BalancedRandomForestClassifer yielded the best overall results with an accuracy rate of 79% when predicting high risk candidates. With a precision rate of 3% and sensitivity rate that was the second highest of the three models at 70%, this is the model that would be recommended.  Note: Although the EasyEnsembleClassifier was not considered for recommendation, it resulted in an accuracy rate of 93%, a precision score of 9%, and recall of 92%.

Models based on "High Risk"

Resample: 62.0% accuracy, 1% precision, 64% recall

SMOTEENN: 51% accuracy, 1% precision, 73% recall

BalancedRandomForestClassifer: 79% accuracy, 3% precision, 70% recall

