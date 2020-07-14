## Classifying qPCR Cancer Mutation data

#### The data
qPCR curve variables for learning: 
1. Cq
2. Baseline
3. Plateau
4. Slope
5. Inflection
6. Asymmetry
7. Drift

![alt text](https://github.com/Finterly/qPCR-CurveCall-Classification-Cancer-Mutation/blob/img/pcr.png)
To predict: 
CurveCall. If True, this curve represents a mutation. If False, it does not





### Best performing models (in no particular order): 
- Random Forest
- Naive Bayes
- XGBoost Classifier 
- Gradient Boosting Classifier 
- AdaBoost
- K-Nearest Neighbor 
- Voting Classifier 
- Bagging Classifier

Less well performing models(with more tuning better models may be possible):
- Decision Tree (would have been nice and interpretable) 
- Support Vector Machine Classifier
- Log Regression
