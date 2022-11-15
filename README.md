# Project-4-Data-Doctors


Overview

According to the World Health Organization (WHO) stroke is the 2nd leading cause of death globally, responsible for approximately 11% of total deaths.We are data Doctors, and we will be focusing on analysing stroke disease.  Our data is obtained from Kaggle https://www.kaggle.com/datasets/fedesoriano/stroke-prediction-dataset?select=healthcare-dataset-stroke-data.csv.



OBJECTIVES 

We are analysing several factors that could affect the possibility of having a stroke.
Analysing to show the likely and unlikely possibility of an individual having a stroke.
Our model will be able to predict  an outcome for new patients based on new data.
Our analysis and predictions will be produced in easy to read and understand visualisation.


CONCLUSION 

We can conclude that logistic regression with with .35 threshold performed best among all the algorithms with
True positives = 59
False positives  = 439
True Negatives = 725
False Negatives = 4
And the classification report also has high recall value.       
Precision  recall f1-score  support      
0    0.99   0.74   0.85   1164
1    0.15   0.84   0.25    63
The confusion Matrix above is the best in all our models as it gives the best False Negative(FN) to True Positive(TP) Ratio (low FN and high TP).
FALSE NEGATIVES: In Layman’s term people who had stroke wrongly predicted as negative by the model.
TRUE POSITIVES: In Layman’s term, people who had stroke correctly predicted as positive by the model.
