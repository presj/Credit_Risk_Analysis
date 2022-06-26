Credit_Risk_Analysis

Overview of the analysis

This challenge involved building and evaluating select machine learning models to predict credit risk.

Results

One way of validating a model's performance is by its accuracy score. The following is a list of three models for predicting credit risk and their associated accuracy scores and the precision and recall scores:


Resampling model accuracy score:

![image](https://user-images.githubusercontent.com/100803302/175835763-3b7b69c7-7ffe-4155-b9f1-496528312adf.png)
  
Resampling precision:

![image](https://user-images.githubusercontent.com/100803302/175836239-211c4ad7-eb50-4db3-b4bf-8c41b4667a53.png)
  
SMOTEENN algorithm accuracy score:

![image](https://user-images.githubusercontent.com/100803302/175835936-3b53d4fb-3287-4d08-8fd5-c05bd08a7714.png)
 
SMOTEENN algorithm precision:

![image](https://user-images.githubusercontent.com/100803302/175836211-68fe71e8-3307-444b-8a83-607f6e43893a.png)
   
Ensemble Classifiers accuracy score:

![image](https://user-images.githubusercontent.com/100803302/175836037-63026fcb-0f68-469f-b141-73a55a50d843.png)
  
Ensembler Classifiers precision and recall:

![image](https://user-images.githubusercontent.com/100803302/175837350-7a87067e-d010-41e1-a468-8dbaf5bf6a84.png)

  

Summary 

Of the models reviewed, the EasyEnsembleClassifer model yielded the best results with an accuracy rate of 79% and a 9% precision rate when predicting "High Risk candidates. The sensitivity rate (aka recall) was also the highest at 92% compared to the other models. The result for predicting "Low Risk" was also the highest with the sensitivity rate at 94% and an F1 score of 97%. Therefore, if a model needed to be recommended to perform this type of analysis, then this one would be the clear choice.

Ranking of models in descending order based on "High Risk" results:

EasyEnsembleClassifer: 93.2% accuracy, 9% precision, 92% recall, and 16% F1 Score
BalancedRandomForestClassifer: 78.9% accuracy, 3% precision, 70% recall and 6% F1 Score
SMOTE: 65.2% accuracy, 1% precision, 61% recall and 2% F1 Score
SMOTEENN: 64.5% accuracy, 1% precision, 72% recall and 2% F1 Score
RandomOverSampler: 64.0% accuracy, 1% precision, 66% recall and 2% F1 Score
ClusterCentroids: 54.5% accuracy, 1% precision, 69% recall and 1% F1 Score
