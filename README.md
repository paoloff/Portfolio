# Portfolio
A list of some of my projects

## Sentiment Analysis of IMDB Movie Reviews (R and Python)

In this project, my team and I developed a machine learning model to perform Sentiment Analysis on movie reviews. The model was trained from a database of reviews taken from iMDB. Specifically, given the review text, the model will identify whether the review is a positive or a negative one. For this purpose, we utilized techniques such as text vectorization, Logistic Lasso Regression and Neural Networks. 

Part 1 (R): https://nbviewer.org/github/paoloff/UIUC_DSE/blob/main/STAT542-Statistical-Learning/Projects/Project%203%20-%20Movie%20Review%20Sentiment%20Analysis/PartI_R.ipynb

Part 2 (Python): https://nbviewer.org/github/paoloff/UIUC_DSE/blob/main/STAT542-Statistical-Learning/Projects/Project%203%20-%20Movie%20Review%20Sentiment%20Analysis/PartII_Python.ipynb

---

## Movie Recommendation App from Users Reviews (Python, R and Shiny)

Here, we developed a model and an app to recommend movies using machine learning. To receive recommendation, a user is asked to either rate a couple of movies or specify a gender, then the algorithm will return a list of movies which the user will probably like. The main recommendation method is the [IBCF](https://en.wikipedia.org/wiki/Item-item_collaborative_filtering). Both Python and R were used. The recommendation methods were first manually coded in Python for validation and later implemented in R using external packages. The app was deployed using ShinyApps (link below).

Python Notebook for testing the recommendation methods: https://nbviewer.org/github/paoloff/UIUC_DSE/blob/main/STAT542-Statistical-Learning/Projects/Project%204%20-%20Movie%20Recommendation%20App/main.ipynb

Movie Recommender website: https://paoloff.shinyapps.io/movierec/

R code for the app: https://github.com/paoloff/UIUC_DSE/tree/main/STAT542-Statistical-Learning/Projects/Project%204%20-%20Movie%20Recommendation%20App/MovieRec

---

## Statistics Projects in R

Here are some statistics projects I made in R primarily utilizing linear regression and ANOVA:

1. In this project, I predicted the grades of the last exam of the course Statistical Modeling I at UIUC using Multiple Linear Regression (MLR):
https://nbviewer.org/github/paoloff/UIUC_DSE/blob/main/STAT425-Statistical-Modeling/cs1_R.ipynb

2. Again using MLR, I analyzed the Crime Rates in the US for the year 1960 and built a model to predict it using other geographical data:
https://nbviewer.org/github/paoloff/UIUC_DSE/blob/main/STAT425-Statistical-Modeling/cs2_R.ipynb

3. Using one-way and two-way ANOVA, I investigated the effects of different variables in the length-of-stay in hospitals for patients which contracted nosocomial infections:
https://nbviewer.org/github/paoloff/UIUC_DSE/blob/main/STAT425-Statistical-Modeling/cs3_R.ipynb

--- 
## Tower - a platform for developing and testing Trading Bots using Reinforcement Learning (Python, Torch and Gym)

This is an on-going project for an open source Python library of Reinforcement Learning algorithms (Q-learning, Policy gradient, Multi-armed bandit, etc) applied to the problem of trading securities in financial markets. So far I used Torch and OpenAI's Gym environments to develop the trading agents.

Link to repo: https://github.com/paoloff/Tower

---
## Predicting the Success of SpaceX Falcon 9 Landing using Machine Learning (Python, Plotly Dash and Docker)

In this project I executed a full Data Science pipeline to predict the outcome of SpaceX Falcon 9 landings. As the first step I extracted data about Falcon 9 missions using REST APIs and web scraping; followed by data cleaning and EDA to identify relevant variables and their relatioships; then I trained and tested a number of different ML models to come up with the most accurate prediction technique; finally, I deployed a dashboard containing interactive graphics as a Docker container.

Part I (Data Extraction): https://nbviewer.org/github/paoloff/Coursera/blob/main/Capstone%20DS%20project/Consolidated/ExtractAndTransform.ipynb

Part II (Visualization): https://nbviewer.org/github/paoloff/Coursera/blob/main/Capstone%20DS%20project/Consolidated/DataVisualization.ipynb

Part III (ML Modeling): https://nbviewer.org/github/paoloff/Coursera/blob/main/Capstone%20DS%20project/Consolidated/Models.ipynb

Docker Container for Dash App: https://github.com/paoloff/Coursera/tree/main/Capstone%20DS%20project/Consolidated/docker_dashapp

This project was the final project for IBM's Data Science Professional Certificate (2023).


