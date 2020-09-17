## Classifying Disease Mutation data

Created machine learning models in R and Python to classify curves of disease data as mutation or no mutation. 

#### The data
<img src="img/pcr.jpg" alt="drawing" width="300" align ="right"/>

7 variables for learning and response variable True (is mutation) and False (is not).

#### R workflow
<img src="img/r_flow.png" alt="drawing" width="600"/>

#### R results
All models show promising mean accuracy over 90%
Random Forest performs the best with mean accuracy of 0.99
Yeo-johnson transformation gave best results
<img src="img/r_results.png" alt="drawing" />

#### Python workflow
<img src="img/python_flow.png" alt="drawing" width="600"/>

#### Exploratory analysis in Python 
In both the training and validation set, there appears to be correlation variables 
Variation is greater in certain variables 
<img src="img/explore1.png" alt="drawing" width="250"/><img src="img/explore2.png" alt="drawing" width="250"/><img src="img/explore3.png" alt="drawing" width="250"/><img src="img/explore4.png" alt="drawing" width="250"/><img src="img/explore5.png" alt="drawing" width="250"/>

#### Preliminary model comparison Python 
<img src="img/models1.png" alt="drawing"/>
<img src="img/roc1.png" alt="drawing"/>
<img src="img/tree_1.png" alt="drawing" width="420"/><img src="img/tree_2.png" alt="drawing" width="350"/>


#### Final results (Python and R)
Visualized final predictions as a binary heat map. Out of the 100 test samples, 99 samples were curves were classified correctly--with models in close agreeance. 


<img src="img/results.png" alt="drawing" width="400"/>

#### Best performing models (in no particular order): 
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
