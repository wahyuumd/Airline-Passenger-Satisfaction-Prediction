# Airline Passenger Satisfaction Prediction

## Introduction
Airline customer satisfaction is important element for the success and growth of the company. Satisfied customers are more likely to become loyal, spread positive word-of-mouth, and contribute to increased revenue. Additionally, high customer satisfaction can provide a competitive advantage, result in cost savings, and improve employee morale.

The business problem are:

1.    What are the main factors influencing airline customer satisfaction?
2.    Which machine learning models are best suited for predicting customer satisfaction?
3.    How accurate and reliable are the predictions made by the model?

## Methodologies
- Data Collection: Download data [Airline Passenger Satisfaction](https://www.kaggle.com/datasets/teejmahal20/airline-passenger-satisfaction) repository on Kaggle.
- Exploratory Data Analysis (EDA): Understanding the patterns, distributions, and relationships within the dataset, including identifying key factors that influence passenger satisfaction.
- Data Preprocessing: Cleaning and transforming the dataset to handle missing values, encode categorical variables, and normalize numerical features.
- Model Training: Using various machine learning algorithms, including Logistic Regression, Decision Tree, Random Forest, XGBoost, and Gaussian Naive Bayes, to train predictive models.
- Feature Selection: Identifying the most relevant features that significantly impact passenger satisfaction.
- Model Evaluation: Comparing model performance using metrics such as accuracy, F1 score, and AUC to select the best model.
- Deployment: Saving the selected model for deployment in live applications to support real-time decision-making by the airline.

## Results
- Customers who choose personal travel are more satisfied than those who choose business travel. Eco and eco plus class customers are more satisfied than those who take business class.
  <p align="center"> <img src= https://github.com/wahyuumd/Airline-Passenger-Satisfaction-Prediction/assets/88516571/843f0433-7ed1-40af-a91f-bd91b9b1f850> </p>
  
- Inflight entertainment, seat comfort, online boarding and cleanliness have quite high positive correlation values ​​and are large in number compared to other variables.
  <p align="center"> <img src= https://github.com/wahyuumd/Airline-Passenger-Satisfaction-Prediction/assets/88516571/bdedf9da-553a-44ae-9255-03f63fec953a> </p>

- By taking several columns as sample, customers feel satisfied with survey scores starting from 4.
  <p align="center"> <img src= https://github.com/wahyuumd/Airline-Passenger-Satisfaction-Prediction/assets/88516571/41b95356-7fcf-46b8-ab69-a9c72634cd36> </p>

- Random Forest has the highest accuracy score at 0.9586. This indicates that it is the best-performing model in terms of correctly classifying the instances.

  <p align="center"> <img src= https://github.com/wahyuumd/Airline-Passenger-Satisfaction-Prediction/assets/88516571/ed828832-d1c3-470e-9c6b-099f322ce6f0> </p>

- Test data accuracy of random forest (default features) is  0.9586 & test data accuracy of random forest (selected features) is 0.9334. When the selected features are used instead of all features, the accuracy decreases significantly.

- Compared with all models, Random Forest has the highest accuracy and AUC scores. We have decided to use the Random Forest model with default parameters to predict customer airline satisfaction.
<p align="center"> <img src= https://github.com/wahyuumd/Airline-Passenger-Satisfaction-Prediction/assets/88516571/1cc8419e-a06c-49c5-8e68-ffdade237573> </p>

## Conclusion
- Several factors significantly impact airline customer satisfaction, including flight distance, age, in-flight entertainment, and more.
- The Random Forest model achieved the highest accuracy score of 0.9586, making it the best-performing model for correctly classifying customer satisfaction levels.
- The high accuracy scores of Decision Tree, Random Forest, and XGBoost indicate that these models are well-suited for the dataset. The default Random Forest model outperformed the Random Forest model with selected features, as indicated by a decrease in test data accuracy when using the latter.
