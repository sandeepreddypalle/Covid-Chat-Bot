Covid dataset from Kaggle was used in this project (https://www.kaggle.com/hemanthhari/symptoms-and-covid-presence). Developed Naive Bayes (0.81 f1 score) and RandomForest algorithms using data from the Kaggle data set (0.66 f1 score).
After training the model, used Flask to create COVID Chatbot UI, which receives user input and returns a response after accessing his condition using the parameters he provided.
Data from users who agreed to share their data is saved in a new CSV file.

Process to setup the project in local:
In order to setup this project in your local, Upload Covid Dataset.csv files,  Covid_Chatbot_MLModel.ipynb,  user_covid_data.csv files in a folder in the Jupyter notebook, then create a new folder inside that folder and rename it to templates. Add home.html file in templates folder.
