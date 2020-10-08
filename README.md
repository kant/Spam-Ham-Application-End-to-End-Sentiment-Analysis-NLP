# Spam-Ham-Application-End-to-End-Sentiment-Analysis-NLP

Project Overview

• Created a machine learning model that detects/classifies a SMS into SPAM or HAM (normal) based on the textual data using Natural Language Processing. • Engineered features like word_count, contains_currency_symbol, and contains_number from the text SMS. How will this project help?

• This project helps in filtering/cleaning the SMS from the phone. Resources Used

• Packages: pandas, numpy, sklearn, matplotlib, seaborn, nltk.

Data Gathering: • Dataset by UCI Machine Learing on Kaggle: https://www.kaggle.com/uciml/sms-spam-collection-dataset

Data Preporcessing:

Exploratory Data Analysis (EDA) • Exploring NaN values in dataset • Plotted countplot for SMS labels Spam vs. Ham

Data Cleaning

• Removing special character and numbers using regular expression • Converting the entire sms into lower case • Tokenizing the sms by words • Removing the stop words • Lemmatizing the words • Joining the lemmatized words • Building a corpus of messages

Model Building and Evaluation • Multinomial Naive Bayes • Decision Tree • Random Forest

Model Deployment • AWS EC2 Instance ubutu - using Putty, PuttyZen, Winsip.

• Web App Link: https://emailapplicationnlp.herokuapp.com/
