# The Silent Killer: Underlying Factors in Soccer Injuries

The following study was done as final project project for MIE368: Analytics in Action, a course offered by the University of Toronto

## Abstract

The present study aims to assess whether a professional soccer player is at risk of injury through the use of specific features ranging from player biometrics to in-game statistics. As a result, prediction can then be used to provide insight for coaching staff to deploy appropriate measures to mitigate injury risk. It can also help management staff in evaluating injury proneness for players that they want to sign. Player data from Europe’s top five soccer leagues was scraped using various websites and merged to compile a list of features possibly relevant to injury risk. Exploratory data analysis (EDA) uncovered the imbalanced nature of the data set as well as the relatively small number of rows within it. To counteract this, random oversampling was used to generate more data points for currently injured players. Feature engineering was also implemented after discovering a lack of correlation between injury risk and the initial features within the dataset. To generate predictions, five supervised learning models were used: Artificial Neural Network (ANN); Classification And Regression Tree (CART); Random Forest; Logistic Regression using Lasso (L1) and Ridge (L2) regularization. All models were implemented using a threshold of 50 percent. Feature scaling was implemented to optimize the algorithm and training for the Neural Network. To assess fitting, loss curves were created which graphed epochs with respect to loss. Compared to the baseline models, on average, the feature engineering models performed better. The ANN model performed the best in terms of accuracy and recall, however, it was the most prone to overfitting due to the substantial amounts of parameters learnt during fitting. Baseline performance was inline with initial EDA as L1 Regression seemed to perform better than L2 regression as many features were not significant. The results also showed that various features relating to in-game player behaviour were the most relevant indicators of injury risk. In turn, this provided insight into the significance of player positioning due to the distinct workloads and demands of different positions on the field. Given the complexity of the problem, more research and analysis is needed to determine the threshold level of injury risk that is worth addressing. As a result, coaching staff and team resources are able to be optimally deployed to assess injury risk that is serious enough to have a significant impact on the player and subsequently the team. 
