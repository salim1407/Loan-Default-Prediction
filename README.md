# Loan-Default-Prediction
This the ML project build to predict the candidate who will default on Loan payments


We have trained the models by using 3 different methodology

   Vanilla Model
   Hyperparameter Tuning
   Oversampling the minority class using SMOTE
   
Acccuracy of Decision Tree improves by tuning the Hyperparameters

However, the accuracy remains the same for Random Forest, Logistic Regression and K-Nearest Neighbours

K-Nearest Neighbours performs worst compared to other Algorithm

Oversampling decreases the accuracy and performance of Logistic Regression and KNN

We can choose any model among Logistic Regression, Decision Tree and Random Forest Classifier that are Hyperparameter tuned

Among the Vanilla, Hyperparameter Tuning and Oversampling, following models are best and have equal performance

Vanilla Model
   Logistic Regression
   Random Forest Classifier
Hyperparameter Tuning
   Logistic Regression
   Decision Tree Classifier
   Random Forest Classifier
Oversampling using SMOTE
   Decision Tree Classifier
   Random Forest Classifier
   
Below are the Model Evaluation Metrics for all 4 algorithms after tuning the algorithm and Oversampling the minority class using SMOTE

Tuned Logistic Regression: precision recall f1-score support

   0                  0.94      0.39      0.55        41
   1                  0.76      0.99      0.86        82
   accuracy                               0.79       123
   macro avg          0.85      0.69      0.71       123
   weighted avg       0.82      0.79      0.76       123

Decision Tree: precision recall f1-score support

   0                  0.94      0.39      0.55        41
   1                  0.76      0.99      0.86        82
   accuracy                               0.79       123
   macro avg          0.85      0.69      0.71       123
   weighted avg       0.82      0.79      0.76       123

KNears Neighbors: precision recall f1-score support

   0                  0.82      0.44      0.57        41
   1                  0.77      0.95      0.85        82
   accuracy                               0.78       123
   macro avg          0.80      0.70      0.71       123
   weighted avg       0.79      0.78      0.76       123

Random Forest Classifier: precision recall f1-score support

   0                  0.94      0.39      0.55        41
   1                  0.76      0.99      0.86        82
   accuracy                               0.79       123
   macro avg          0.85      0.69      0.71       123
   weighted avg       0.82      0.79      0.76       123
