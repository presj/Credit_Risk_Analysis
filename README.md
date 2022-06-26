Credit_Risk_Analysis

Overview of the analysis

This challenge involved building and evaluating select machine learning models to predict credit risk.

Results

One way of validating a model's performance is by its accuracy score. The following is a list of three models for predicting credit risk and their associated accuracy scores and the precision and recall scores:


Resampling model (RandomOverSampler) accuracy score:

![image](https://user-images.githubusercontent.com/100803302/175835763-3b7b69c7-7ffe-4155-b9f1-496528312adf.png)
  
Resampling (RandomOverSampler) precision and recall:

![image](https://user-images.githubusercontent.com/100803302/175837433-9e99f03e-4973-4502-9271-42e8d82cf4d7.png)
![image](https://user-images.githubusercontent.com/100803302/175837454-4d67252b-2480-46e4-9e05-d22d139fe780.png)
  
SMOTEENN (Combination Sampling) algorithm accuracy score:

![image](https://user-images.githubusercontent.com/100803302/175835936-3b53d4fb-3287-4d08-8fd5-c05bd08a7714.png)
 
SMOTEENN (Combination Sampling) algorithm precision and recall:

![image](https://user-images.githubusercontent.com/100803302/175837494-2e915549-189f-40dd-8761-00e500afb1c4.png)

Ensembler Classifiers (BalancedRandomForestClassifer) accuracy score:

![image](https://user-images.githubusercontent.com/100803302/175836037-63026fcb-0f68-469f-b141-73a55a50d843.png)
  
Ensembler Classifiers (BalancedRandomForestClassifer) precision and recall:

![image](https://user-images.githubusercontent.com/100803302/175837350-7a87067e-d010-41e1-a468-8dbaf5bf6a84.png)

  

Summary 

Of the three models reviewed, the BalancedRandomForestClassifer yielded the best overall results with an accuracy rate of 79% when predicting high risk candidates. With a precision rate of 3% and sensitivity rate that was the second highest of the three models at 70%, this is the model that would be recommended.  Note: Although  
the EasyEnsembleClassifier was not considered for recommendation, it resulted in an accuracy rate of 93%, a precision score of 9%, and recall of 92%.

Models based on "High Risk"

Resample: 62.0% accuracy, 1% precision, 64% recall 
SMOTEENN: 51% accuracy, 1% precision, 73% recall
BalancedRandomForestClassifer: 79% accuracy, 3% precision, 70% recall

