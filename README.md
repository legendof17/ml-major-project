# **ML-Major-Project**
**ML-MAJOR-FEB-ML-02-BM4** <br>
SmartKnower Machine Learning Internship's **Major Project**
***
🚀 The website is live on Heroku [**Sentiment-Analysis**](https://sentiment-analysis-ml-major.herokuapp.com/) <br>
This is my [Machine Learning - Major Project](https://colab.research.google.com/drive/1TysED8609mKTLsVENhYhB9aVHhR5td7Q?usp=sharing), I have worked on **SKLEARN Logistic Regression** library to do sentiment analysis on Amazon Review dataset.
***
**Links:**
---
* Colab File    :   [Sentiment Analysis](https://colab.research.google.com/drive/1TysED8609mKTLsVENhYhB9aVHhR5td7Q?usp=sharing)
* Train Dataset :   [Amazon Review Dataset](dataset/amazon_baby.csv)
* Test Dataset  :   [Example Review Dataset](dataset/small_csv_data.csv)
* Pickle Model  :   [Pickle Model](model/Amazon_reviews.sav)
* Joblib Model  :   [Joblib Model](model/Amazon_reviews)
* Heroku Github :   [Heroku](https://github.com/legendof17/sentiment-analysis)
***
I have used **Count Vectorizer** to convert string into number array.

Algorithm:
* SKLEARN - Logistic Regression

Accuracy: **93%**
***
**Description**
----
I have created model using **Logistic Regression** with an accuracy of **93%** and saved the model using **Pickle** for later use. <br>
The Pickle saved model is used for **Streamlit** & **Ngrok** hostings.

Since Pickle model is suit well with Heroku, another model created with **Joblib** for heroku hosting.
