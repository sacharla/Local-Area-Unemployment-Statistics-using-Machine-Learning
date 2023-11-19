# Local-Area-Unemployment-Statistics-using-Machine-Learning

Overview:
The project focuses on predicting unemployment statistics in the United States at a local level, specifically based on states. Leveraging machine learning techniques, the goal is to develop accurate predictions using classification models. Two primary tools employed for this task are the SKLearn MLPClassifier/Regressor and Keras techniques. The intention is to provide insights into the factors influencing unemployment rates in different states, enabling more informed decision-making.

Narrative:
In this comprehensive endeavor, the project begins by sourcing Local Area Unemployment Statistics (LAUS) data for various states in the US. This dataset serves as the foundation for the machine learning models. The next step involves preprocessing and cleaning the data to ensure its suitability for training and evaluation.

The machine learning models employed for this prediction task include the SKLearn MLPClassifier/Regressor and Keras techniques. The choice of these models is driven by their ability to handle complex relationships within the data, making them well-suited for predicting unemployment trends.

The feature selection process involves identifying key variables that significantly impact unemployment rates. Factors such as economic indicators, population demographics, and historical employment data are considered to build a robust predictive model. This step is crucial for enhancing the accuracy and interpretability of the machine learning algorithms.

The training phase involves feeding the preprocessed data into the selected classifiers and regressors. The models learn from historical patterns and relationships within the data to make predictions about future unemployment statistics. Rigorous testing and validation procedures are implemented to assess the performance and generalization capabilities of the models.

The results obtained from the machine learning models are then analyzed to derive meaningful insights. The project aims to uncover patterns and trends that contribute to variations in unemployment rates across different states. This analysis provides valuable information for policymakers, businesses, and researchers seeking a deeper understanding of the dynamics influencing local labor markets.

The final stage of the project involves presenting the findings in a clear and comprehensible manner. Visualizations, statistical summaries, and interpretative narratives are utilized to communicate the predictions and insights effectively. Additionally, the project may include recommendations for targeted interventions or policies based on the identified factors influencing unemployment.

In conclusion, the Local Area Unemployment Statistics using Machine Learning project combines data science, machine learning techniques, and domain knowledge to create a predictive model for understanding and forecasting unemployment trends at the state level in the United States. Through a detailed overview and narrative, the project aims to contribute valuable insights to the field of labor market analysis.

Findings:
The f1 score for Random Search on Logistic Regression is 0.9762289562289563

The f1 score for grid search on the logistic regression is 0.9742068308729206

The f1 score for Random Search on Linear SVM is 0.9724053296218781

The f1 score for Grid Search on Linear SVM is 0.9776157863464366

The f1 score for Random Search on Poly SVM is 0.9736799574694313

The f1 score for Grid Search on Poly SVM is 0.9724053296218781

The f1 score for Random Search on RBF SVM is 0.9757976045282547

The f1 score for Grid Search on RBF SVM is 0.9872873200854851

The f1 score for Random Search on Decision tree classifier is 0.9891221824708063

The f1 score for exhaustive Grid Search on Decision tree classifier is 0.9891221824708063
Based on the above results, it can be clearly seen that when we compare all the f1 score metrics with the models while using both the random search and the grid search to test the range of best parameters, we see that the F1 score is highest for the Decision Tree classifier with almost same testing score. The f1 score for the decision tree classifier using the best parameter tuning using the random search testing and the grid search testing is 98.91. Hence it can be concluded that this is the best performing model out of the rest. SVM RBF appears to be the second best performing model based on the f1 score of 98.72 for the Grid Search test and 97.57 for the Random search test.
