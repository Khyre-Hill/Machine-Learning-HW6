# Machine-Learning-HW6

Khyre Hill. hillkh19@students.ecu.edu

Carlos Ochoa. ochoac19@students.ecu.edu

Mason Garrett. garrettm19@students.ecu.edu


Number of features (original) :  64
Number of features (reduced) :  51
Fitting 5 folds for each of 10 candidates, totalling 50 fits
The best parameters after RandomSearchCV:  {'kernel': 'linear', 'gamma': 0.01, 'C': 0.1}
The best estimator:  SVC(C=0.1, gamma=0.01, kernel='linear')
Classifier report:
              precision    recall  f1-score   support

           0       0.95      0.99      0.97        88
           1       0.89      0.93      0.91        91
           2       0.95      0.97      0.96        86
           3       0.93      0.87      0.90        91
           4       0.97      0.90      0.93        92
           5       0.87      0.93      0.90        91
           6       0.95      0.95      0.95        91
           7       0.96      0.92      0.94        89
           8       0.89      0.83      0.86        88
           9       0.87      0.91      0.89        92

    accuracy                           0.92       899
   macro avg       0.92      0.92      0.92       899
weighted avg       0.92      0.92      0.92       899

 
Fitting 5 folds for each of 10 candidates, totalling 50 fits
The best parameters after RandomSearchCV:  {'kernel': 'rbf', 'gamma': 0.01, 'C': 100}
The best estimator:  SVC(C=100, gamma=0.01)
Classifier report:
              precision    recall  f1-score   support

           0       0.98      0.99      0.98        88
           1       0.94      0.96      0.95        91
           2       0.96      0.95      0.96        86
           3       0.99      0.84      0.90        91
           4       0.87      0.91      0.89        92
           5       0.89      0.96      0.92        91
           6       0.98      0.92      0.95        91
           7       0.95      0.97      0.96        89
           8       0.92      0.90      0.91        88
           9       0.90      0.95      0.92        92

    accuracy                           0.93       899
   macro avg       0.94      0.93      0.93       899
weighted avg       0.94      0.93      0.93       899
