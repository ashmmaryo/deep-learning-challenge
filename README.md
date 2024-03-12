# deep-learning-challenge

# Overview
This project aims to develop an algorithm utilizing machine learning and neural networks to forecast the potential success of applicants funded by non-profit organization, Alphabet Soup.

The examination utilizes historical data from funding campaigns and entails data preprocessing with Python and Pandas to segregate, categorize, and generate dummy variables for categorical data, which serve as model features for predictive analysis. 
Following preprocessing, a neural network is constructed using Keras, and the model is fine-tuned to attain a predictive accuracy target surpassing 75%

Steps:
Imported a CSV file into Pandas containing data on 34,000+ organizations funded by a fictional foundation.
Preprocessed the data by removing non-beneficial columns and handling rare categorical values.
Converted categorical data into numerical format and split the data into target and feature arrays.
Further divided the data into training and testing datasets and standardized them using StandardScaler.
Model Compilation, Training, and Evaluation:

Objective: 
Achieve predictive accuracy >75% using machine learning and neural networks.
After three attempts, accuracy ranged from 72.45% (test1) to 72.44% (test2) to 72.45%(test3), falling short of the target of 75%. Even after adjusting activation code between relu and tanh, the result didn't touch 75%.
To achieve target beyond 75%, it's worth noting to utilize other classification model to improve prrediction model and perhaps adding more layers/neorons to the machine learning model. 
