# Churn-Customer-Classification

The notebook contains the EDA, feature selection, preprocessing, PCA for best features, and implementation of the KNN model, RandomForestClassifier model, and GridSearch CV.


## Metrics for each model
#### KNN 
       precision    recall  f1-score  
0       0.93      0.98      0.95      
1       0.84      0.59      0.70       

accuracy: 0.92

#### RandomForestClassifier with default parameters
      precision    recall  f1-score  
0       0.97      0.99      0.98      
1       0.92      0.83      0.88     

accuracy: 0.96      

#### RandomForestClassifier with GridSearch parameters
best_params: n_estimators=1000, max_depth = 20

      precision    recall  f1-score   
0       0.97      0.99      0.98      
1       0.92      0.84      0.88       

accuracy                           0.96      
  
