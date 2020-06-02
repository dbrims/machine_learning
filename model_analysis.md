
Resampling
> Which model had the best balanced accuracy score?

The Naive resampling method was the accuracy
Accuracy Score RF sample: 0.5197727472700497
Accuracy Score RF combo: 0.7169743167020163
Accuracy Score RF under: 0.7206510086228455
Accuracy Score RF SMOTE: 0.7232784989209866
Accuracy Score RF naive over: 0.7273520061313896


> Which model had the best recall score?

The SMOTE and naive resampling methods gave the best recall score
Recall Score centroid undersampling: 0.67
Recall Score combo: 0.74
Recall Score naive oversampling: 0.76
Recall Score SMOTE: 0.76
Recall Score  before resampling: .99


>
> Which model had the best geometric mean score?

The naive resampling method gave the best geometic mean
Geometric Mean before resampling: 0.20
Geometric Mean SMOTE: 0.72
Geometric Mean centroid undersampling: .72
Geometric Mean combo: 0.72
Geometric Mean naive oversampling: 0.73


Ensemble
> Which model had the best balanced accuracy score?

The adaboost model had the best accuracy
Accuracy Score Random Forest: 0.6830513851198029
Accuracy Score Boost: 0.9213509780585168
>
> Which model had the best recall score?

the random forest had the best recall
Recall score Random forest: 1.0
Recall score adaBoost: 0.91

> Which model had the best geometric mean score?

The adaboost model had the best accuracy
Geographic Mean Random forest: 0.61
Geographic Mean adaBoost: 0.92

> What are the top three features?

total_pymnt_inv(0.08152326395136766)
last_pymnt_amnt(0.06600050687368304)
total_pymnt(0.057378035520553455)
