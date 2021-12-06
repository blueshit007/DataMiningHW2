# DataMiningHW2
10 models for Polish+companies+bankruptcy+data

### Table 1 Final Results of all-5-years data for Comparative Models

| ModelName | acc	| ROC_AUC	| PR_AUC	| F1_score	| time_used |
| :--------  | :-----  | :----:  | :--------  | :-----  | :----:  |
| BernoulliNB |	0.897 |	0.627 |	0.046 |	0.542 |	0.011 |
| GaussianNB |	0.863 |	0.66 |	0.049 |	0.531 |	0.012  |
| SVM |	0.976 |	0.5 |	0.024 |	0.494 |	1.470 |
| DecisionTree |	0.965	 |0.657 |	0.114 |	0.647 |	0.750  |
| SGD |	0.876 |	0.642 |	0.046 |	0.533 |	0.042 |
| Nearest_Neighbors |	0.723 |	0.675 |	0.042 |	0.467 |	0.007  |
| AdaBoost |	0.978 |	0.582 |	0.131 |	0.628 |	7.771 |
| GradientBoosting |	0.978 |	0.588 |	0.145 |	0.636 |	6.518 |
| **HistGradientBoosting** |	**0.982** |	**0.64** |	**0.262** |	**0.708** |	**9.174** |
| MLP |	0.977 |	0.623 |	0.158 |	0.667 |	113.919 |







### Table 1year.arff
| ModelName | Precision | Recall | ROC_AUC	| PR_AUC	| F1_score	| Time_Used |
| :--------  | :-----  | :----:  | :----:  | :--------  | :-----  | :----:  |
| BernoulliNB | 0.991 |0.000 | 0.500 | 0.009 | 0.498 | 0.003 |
| GaussianNB | 0.634 |0.444 | 0.540 | 0.010 | 0.399 | 0.003 |
| SVM | 0.991 |0.000 | 0.500 | 0.009 | 0.498 | 0.039 |
| DecisionTree | 0.979 |0.000 | 0.494 | 0.009 | 0.495 | 0.065 |
| SGD | 0.991 |0.000 | 0.500 | 0.009 | 0.498 | 0.009 |
| NearestCentroid | 0.638 |0.444 | 0.542 | 0.010 | 0.400 | 0.003 |
| AdaBoost | 0.987 |0.111 | 0.553 | 0.031 | 0.568 | 1.281 |
| GradientBoosting | 0.989 |0.000 | 0.499 | 0.009 | 0.497 | 0.929 |
| HistGradientBoosting | 0.990 |0.000 | 0.499 | 0.009 | 0.497 | 75.487 |
| MLP | 0.983 |0.222 | 0.606 | 0.048 | 0.596 | 41.899 |
| LogisticRegression(Ours) | 0.710 |0.143 | 0.430 | 0.011 | 0.421 | 1.581 |


### Table 2year.arff
| ModelName | Precision | Recall | ROC_AUC	| PR_AUC	| F1_score	| Time_Used |
| :--------  | :-----  | :----:  | :----:  | :--------  | :-----  | :----:  |
| BernoulliNB | 0.983 |0.000 | 0.500 | 0.017 | 0.496 | 0.004 |
| GaussianNB | 0.636 |0.667 | 0.651 | 0.026 | 0.417 | 0.006 |
| SVM | 0.983 |0.000 | 0.500 | 0.017 | 0.496 | 0.127 |
| DecisionTree | 0.966 |0.095 | 0.538 | 0.023 | 0.535 | 0.110 |
| SGD | 0.983 |0.000 | 0.500 | 0.017 | 0.496 | 0.015 |
| NearestCentroid | 0.666 |0.714 | 0.690 | 0.030 | 0.432 | 0.006 |
| AdaBoost | 0.978 |0.048 | 0.521 | 0.022 | 0.529 | 1.601 |
| GradientBoosting | 0.980 |0.000 | 0.499 | 0.017 | 0.495 | 1.190 |
| HistGradientBoosting | 0.984 |0.095 | 0.547 | 0.079 | 0.579 | 35.028 |
| MLP | 0.963 |0.143 | 0.560 | 0.029 | 0.549 | 38.195 |
| LogisticRegression(Ours) | 0.787 |0.231 | 0.514 | 0.018 | 0.458 | 1.690 |


### Table 3year.arff
| ModelName | Precision | Recall | ROC_AUC	| PR_AUC	| F1_score	| Time_Used |
| :--------  | :-----  | :----:  | :----:  | :--------  | :-----  | :----:  |
| BernoulliNB | 0.979 |0.000 | 0.500 | 0.020 | 0.495 | 0.004 |
| GaussianNB | 0.557 |0.800 | 0.676 | 0.033 | 0.389 | 0.005 |
| SVM | 0.980 |0.000 | 0.500 | 0.020 | 0.495 | 0.136 |
| DecisionTree | 0.956 |0.133 | 0.553 | 0.030 | 0.543 | 0.128 |
| SGD | 0.980 |0.000 | 0.500 | 0.020 | 0.495 | 0.018 |
| NearestCentroid | 0.664 |0.533 | 0.600 | 0.027 | 0.428 | 0.001 |
| AdaBoost | 0.981 |0.167 | 0.582 | 0.121 | 0.627 | 1.857 |
| GradientBoosting | 0.977 |0.133 | 0.564 | 0.066 | 0.592 | 1.443 |
| HistGradientBoosting | 0.981 |0.133 | 0.566 | 0.107 | 0.606 | 44.544 |
| MLP | 0.965 |0.233 | 0.607 | 0.061 | 0.597 | 37.008 |
| LogisticRegression(Ours) |  0.872 |0.182 | 0.536 | 0.028 | 0.499 | 1.868 |


### Table 4year.arff
| ModelName | Precision | Recall | ROC_AUC	| PR_AUC	| F1_score	| Time_Used |
| :--------  | :-----  | :----:  | :----:  | :--------  | :-----  | :----:  |
| BernoulliNB | 0.973 |0.000 | 0.500 | 0.026 | 0.493 | 0.005 |
| GaussianNB | 0.847 |0.432 | 0.645 | 0.047 | 0.522 | 0.006 |
| SVM | 0.974 |0.000 | 0.500 | 0.026 | 0.493 | 0.164 |
| DecisionTree | 0.948 |0.108 | 0.539 | 0.033 | 0.535 | 0.104 |
| SGD | 0.974 |0.000 | 0.500 | 0.026 | 0.493 | 0.015 |
| NearestCentroid | 0.735 |0.622 | 0.680 | 0.047 | 0.476 | 0.003 |
| AdaBoost | 0.970 |0.108 | 0.550 | 0.054 | 0.571 | 1.836 |
| GradientBoosting | 0.968 |0.108 | 0.549 | 0.048 | 0.566 | 1.395 |
| HistGradientBoosting | 0.974 |0.054 | 0.526 | 0.051 | 0.542 | 90.590 |
| MLP | 0.958 |0.189 | 0.584 | 0.057 | 0.584 | 35.594 |
| LogisticRegression(Ours) | 0.924 |0.179 | 0.564 | 0.046 | 0.547 | 1.787 |


### Table 5year.arff
| ModelName | Precision | Recall | ROC_AUC	| PR_AUC	| F1_score	| Time_Used |
| :--------  | :-----  | :----:  | :----:  | :--------  | :-----  | :----:  |
| BernoulliNB | 0.973 |0.000 | 0.500 | 0.027 | 0.493 | 0.002 |
| GaussianNB | 0.867 |0.640 | 0.757 | 0.090 | 0.568 | 0.002 |
| SVM | 0.973 |0.000 | 0.500 | 0.027 | 0.493 | 0.062 |
| DecisionTree | 0.947 |0.480 | 0.720 | 0.137 | 0.653 | 0.076 |
| SGD | 0.975 |0.080 | 0.540 | 0.105 | 0.568 | 0.018 |
| NearestCentroid | 0.771 |0.760 | 0.766 | 0.072 | 0.511 | 0.003 |
| AdaBoost | 0.978 |0.360 | 0.678 | 0.267 | 0.731 | 1.187 |
| GradientBoosting | 0.946 |0.600 | 0.778 | 0.178 | 0.676 | 0.852 |
| HistGradientBoosting | 0.978 |0.280 | 0.639 | 0.238 | 0.700 | 78.478 |
| LogisticRegression(Ours) | 0.925 |0.421 | 0.682 | 0.109 | 0.621 | 1.026 |