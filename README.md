# Rain-Prediction
A project on predicting whether it will rain tomorrow or not by using the Rainfall in Australia dataset
This project is tested over lot of ml models like catboost, xgboost, random forest, support vector classifier.
I also made this project with the help of PyCaret Library which is an Auto MAchine Learning Technique
I have not done much Auto Tuninng because I wanted to demonstrate how we can do this project with the help of Auto Machine Learning i.e. PyCaret Librayy.
You can do the Hypertuning , it is highly recommended and also use other functions of PyCaret library.
It's pretty Interesting



# Main Page of the web application
![Rain Prediction - Brave 9_19_2021 11_26_17 AM](https://user-images.githubusercontent.com/65214856/133917170-dd3e4264-2925-4316-9c43-061111886a0f.png)


# Tech Stack
* Front-End: HTML, CSS, Bootstrap
* Back-End: Flask
* IDE: Jupyter notebook, Pycharm

# How to run this app
* First create a virtual environment by using this command:
* conda create -n myenv python=3.6
* Activate the environment using the below command:
* conda activate myenv
* Then install all the packages by using the following command
* pip install -r requirements.txt
* Now for the final step. Run the app
* python app.py


# Workflow

# Data Collection: 
[Rainfall Prediction in Australia dataset](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package) from Kaggle
# Data Preprocessing: 
* Missing Values Handled by Random Sample imputation to maintain the variance
* Categorical Values like location, wind direction are handled by using Target guided encoding
* Outliers are handled using IQR and boxplot
* Feature Selection and was done but didnt perform well it can be seen in testing_notebook/Prediction.ipynb
* Feature Scaling didnt give a lot of difference it also can be seen in testing_notebook/RainPrediction1.ipynb
* Imbalanced Dataset was handled using SMOTE
# Model Creation:
* Different types of models were tried like catboost, random forest, logistic regression, xgboost, support vector machines, knn, naive bayes.
* Out of these catboost, random forest and support vector machines were top 3
* The conclusion were made using classification metrics. roc curve and auc score
# Model Deployment
* The model is deployed using Flask at Heroku server





