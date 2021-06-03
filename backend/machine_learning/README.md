# Bangkit_CapstoneProject_Majors.Id
Bangkit Capstone Project for Majors.Id Chatbot Development

In Developing This Chatbot we used a kaggle dataset which is listed below:

https://www.kaggle.com/fivethirtyeight/fivethirtyeight-college-majors-dataset?select=majors-list.csv

Steps involved in creating this chatbot are listed below :

1. Preprocessed the raw dataset, this include in adding new FAQ question and also creating artificial question from the raw dataset.
2. Export the dataset created in the form of json file
3. We can start developing model with the dataset that has been created
4. The model used in this project are simple DNN with input layer, 2 fully connected layer and an output layer
5. Export the model created in the form of tensorflow saved model (.h5)
6. Create data pipeline for the model input and test for deployment.

For Details intruction of the step above:
1. For step 1 & 2 can be seen in Dataset Preparation.ipynb
2. For step 3, 4, and 5 can be seen in Chatbot Development.ipynb
3. For step 6 can be seen in Deployment Test.ipynb


This project is heavily inspired from the article listed below :

https://towardsdatascience.com/how-to-create-a-chatbot-with-python-deep-learning-in-less-than-an-hour-56a063bdfc44
