# Credit_Risk_Analysis

### Project Overview
The purpose of this analysis is to perform various analyses using several supervised machine learning techniques in order to determine varying levels of credit risk. The algorithms used in said in analysis include SMOTE, SMOTEENN, Cluster Centroids, RandomOverSampler, and Easy Ensemble Classifier. As per Jill, we've been asked to determine which loans can be considered high or low risk, which can be a challenge due to the fact that there are more low risk loans as opposed to high risk loans. With these machine learning techniques we can get a clearer picture of which loans are high or low risk.
  
### Results of Analysis

NaiveRandomOversampling results came back with a balanced accuracy score of 66 percent. Precision for high risk loans came out to 1 percent along with a recall of 73 percent. Low risk precision was 99 percent with a recall of 58 percent. 
<img width="619" alt="naive random oversampling" src="https://user-images.githubusercontent.com/111616227/222040394-7a69c426-8fc1-4d1f-a8d2-65f6699e8ed5.png">

SMOTE Oversampling has a balanced accuracy score of 66 percent. High risk loans bore 1 percent precision with a recall of 63 percent. Low risk loans resulted in 99 percent precision with recall of 69 percent.

<img width="485" alt="SMOTE Oversampling" src="https://user-images.githubusercontent.com/111616227/222041003-adc832d0-784e-42f6-a1b8-82918e720dd8.png">

The ClusterCentroids model came back with a balanced accuracy score of 66 percent as well. High risk loans had 1 percent precision with 69 percent recall. Low risk loans had 99 percent precision with a 40 percent recall. 

<img width="418" alt="ClusterCentroids" src="https://user-images.githubusercontent.com/111616227/222058209-b0479989-f324-4c15-9212-d903285a12ec.png">

The SMOTEENN model yielded a balanced accuracy of 54 percent. High risk loans had a precision of 1 percent and a recall of 73 percent, while low risk loans had shown a precision of 99 percent and a recall of 57 percent.

<img width="417" alt="SMOTEENN" src="https://user-images.githubusercontent.com/111616227/222092900-5dd374d9-ccbf-4cef-b409-35e3f1aebcbf.png">

BalancedRandomForestClassifier came back with a balanced accuracy of 80 percent. High risk loans came back with 4 percent precision and 72 percent recall, while low risk loans had a 99 percent precision and 89 percent recall. 

<img width="625" alt="BalancedRandomForestClassifier" src="https://user-images.githubusercontent.com/111616227/222094454-bc20cb96-2ce6-46ae-86c1-7467ec04b45a.png">

Lastly, the EasyEnsembleClassifier came back with a balanced accuracy of 92 percent. High risk loans yielded 9 percent precision and a recall of 89 percent. Low risk loans came out to 99 percent precision and 94 percent recall.

<img width="379" alt="EasyEnsembleClassifier" src="https://user-images.githubusercontent.com/111616227/222108925-6534c8e4-bbc1-47d4-99c6-0d540dc4b001.png">


### Summary



