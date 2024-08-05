SUMMARY

LOGISTIC REGRESSION WITH PCA
ANALYSIS
Train set Accuracy: - 0.9680563075257174 Sensitivity: - 0.09641873278236915 Specificity:- 0.9975744005970706
Test set Accuracy: - 0.9621007038440714 Sensitivity: - 0.06310679611650485 Specificity:- 0.996813495782568

The model shows high accuracy and specificity, indicating it correctly identifies non-churners. However, the low sensitivity on both train and test sets indicates poor performance in detecting churners. The model is biased towards predicting the non-churn class, making it ineffective for identifying potential churners. Overall, the model's performance is inadequate for the intended purpose of detecting churn.
Overall, while the model performs well in some areas, its inability to accurately identify churners suggests the need for further refinement and potentially more sophisticated techniques to address the class imbalance.

SVM WITH PCA
ANALYSIS
The best test score is 0.9672441797509475 corresponding to hyperparameters {'C': 1, 'gamma': 0.01}
The model's accuracy of 96.72% with C: 1 and gamma: 0.01 suggests that these hyperparameters provide a good balance between bias and variance. The moderate C value indicates that the model isn't overly focused on fitting the training data perfectly, which helps to generalize better to new, unseen data

DECISION TREE WITH PCA
ANALYSIS
Train Set Accuracy: - 0.9681916621548456 Sensitivity: - 0.15564738292011018 Specificity: - 0.9957085549025095
Test Set Accuracy: - 0.9615592853275582 Sensitivity: - 0.09223300970873786 Specificity: - 0.9951265229615746

The model is effective at predicting non-churn cases but fails to adequately detect churners. The low sensitivity on both sets is a significant issue, making the model less useful for predicting churn.

RANDOM FOREST WITH PCA
Train set Accuracy: - 0.9672441797509475 Sensitivity: - 0.0 Specificity: - 1.0
Test set Accuracy: - 0.9628225951994225 Sensitivity: - 0.0 Specificity: - 1.0
Despite the high accuracy and specificity, the model's zero sensitivity means it does not identify churn cases at all. This makes the model ineffective for predicting churn, which is a critical failure if churn prediction is the primary goal
