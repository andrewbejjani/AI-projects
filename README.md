# AI-projects
This repository includes two AI based projects which will be briefly explained below:

## Titanic Survival Prediction (Classical ML)
* This project aims at predicting whether a Titanic passenger survived the incident or not given some information which include the age, sex, number of family members aboard, ticket class, etc.
* It involves data loading, visualization, analysis, transformation, cleaning, feature engineering, model training, and model evaluation. The dataset for each notebook is provided and analysis of the data is provided in the notebooks as well.
* Feature engineering was done which included studying the data, finding outliers, null data, and possible transformations. Graphs and correlation matrices were also used to support the analysis.
* Training was then done which allowed me to test the model with Logistic Regression, AdaBoost classifier, Decision Trees, and Artificial Neural Networks.
* Hyperparameter tuning was also done via Grid Search for both L1 and L2 penalties. Details are commented inside the notebook. 

## Predicting Food Score via Reviews (NLP)
* This project aims at cleaning Text Reviews for various food items and training on that data to guess newly given unrated data. The "Reviews.csv" dataset was used which includes over 568k reviews which can be found **[here](https://www.kaggle.com/code/naushads/1-2-amazon-fine-food-reviews-eda-data-cleaning-fe/input)**.
* Proper feature engineering methods were first used to remove duplicates and to change the ratings from (1-5) to either 0 or 1.
* Then, text cleaning functions were introduced to decontract words, remove special characters or URLs, remove stopwords, and convert everything to lowercase.
* Then, I lemmatized the text and vectorized it through built in libraries before training and testing on Logistic Regression and Random Forest algorithms.
* However, the data was not balanced since more users had ratings above 3 than below 3. So I had to balance the data by removing some high ratings which would improve the recall and precision for the low ratings. All details and analysis are commented in the notebook. 
