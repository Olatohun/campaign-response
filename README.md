# Title: Prediction of Users’ Responses to Marketing Campaigns

1.	Project Motivation
2.	Installation
3.	Data
4.	Implementation
5.	Results

### Project Motivation
The aim of this project is to analyse  user information and build a model capable of predicting users’ responses to marketing campaigns based on the features in the provided dataset. 1 means ‘Yes’, and 0 means ‘No’

### Installation
Python V-3.

**Libraries:**
-	Scikit Learn.
-	Imblearn. 
-	Pandas. 
-	Numpy.
-	Seaborn
-	Matplotlib.


### Data
The data was gotten from the private hackathon by to Data Science Nigeria for AI+ members to qualify for the 2021 AI Bootcamp. The hackathon took place on Zindi. Full description of the data is available on [Zindi]( https://zindi.africa/competitions/ai-bootcamp-2021).

### Implementation
Three classification models were run on the data, including Decision Tree, Random Forest and Logistic Regression. The target variable was made balanced using SMOTE and make_imbalanced from the Imblearn library. Details about the models’ performance on the different sets of data is available in the notebook. 
The models were run on selected features data with a ratio of 70:30 and the performance of the model was reviewed using the classification_report metric to display a summary of accuracy score, precision score, recall score and f1_score as shown in the notebook

### Results
The output of the prediction result is in the ‘predicted_response.csv’ above and in the notebook as well
