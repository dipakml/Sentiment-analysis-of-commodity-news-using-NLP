## End-to-End NLP Machine Learning Project- Sentiment analysis of commodity news using NLP


<img target="_blank" src="https://github.com/dipakml/Prediction-of-Concrete-Compressive-Strength/blob/master/Logo_Images/sentiment_analysis2.jpeg" width=600>

### Table of Content
  * [Overview](#overview)
  * [Dataset Information](#dataset)
  * [Motivation](#motivation)
  * [Demo](#demo)
  * [Steps in the project execution](#Learning-Objective)
  * [Technical Aspect](#technical-aspect)
  * [Technologies Used](#technologies-used)
  * [Installation](#installation)
  * [Note](#note)



### Overview 
With the rapid development of the Internet and big data technologies, a rich of online data (including news releases) can helpfully facilitate evaluating the sentiment of commodities at given day. Accordingly, this study introduces sentiment analysis, a useful analysis tool, to understand the relevant information of online news articles and predicts the sentiment which can be further used to formulate a gold price trend prediction.

In this project, let's apply machine learning techniques and develop a web based application to predict the sentiment of the given news.


### Dataset Information

This is a news dataset for the commodity market where we have manually annotated 10,000+ news headlines across multiple dimensions into various classes. The dataset has been sampled from a period of 20+ years (2000-2021).


Dataset used in this project can be found here : [Dataset](https://www.kaggle.com/datasets/ankurzing/sentiment-analysis-in-commodity-market-gold)


### Motivation
The motivation was to use machine learning experiments to try to predict the sentiment of the news so that it can be used for commodity trading.

Idea is to implement the end to end machine learning project while using free deployment platform like Heroku.



Web application Snapshot:

<img target="_blank" src="https://github.com/dipakml/Prediction-of-Concrete-Compressive-Strength/blob/master/Logo_Images/webapp.PNG" width=1200>



### Steps in the project execution

- Data gathering 
- Data Visualizations 
- Data Preprocessing 
- Data Modelling 
- Model Evaluation 
- Model Deployment 

### Technical Aspect 

- Training a machine learning model using scikit-learn. 
- Building and hosting a streamlit web app on Heroku. 
- A user has to the news.
- Once it gets the input news , the sentiment prediction is displayed. 


### Technologies Used  
![](https://forthebadge.com/images/badges/made-with-python.svg) 

<img target="_blank" src="https://github.com/dipakml/Prediction-of-Concrete-Compressive-Strength/blob/master/Logo_Images/streamlit.png" width=160>
<img target="_blank" src="https://github.com/dipakml/Prediction-of-Concrete-Compressive-Strength/blob/master/Logo_Images/heroku.png" width=160>
<img target="_blank" src="https://github.com/dipakml/Prediction-of-Concrete-Compressive-Strength/blob/master/Logo_Images/numpy.png" width=160>
<img target="_blank" src="https://github.com/dipakml/Prediction-of-Concrete-Compressive-Strength/blob/master/Logo_Images/pandas.jpeg" width=160>

### Installation 
- Clone this repository and unzip it.
- After downloading, cd into the working directory.
- Begin a new virtual environment with Python 3 and activate it.
- Install the required packages using pip install -r requirements.txt
- Execute the command: streamlit run app.py


### Note:
- Webapp can handle concurrency upto some extent but can be scaled.

