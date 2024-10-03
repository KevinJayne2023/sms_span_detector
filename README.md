#SMS Spam Detector with Gradio and Scikit-Learn

#Project Overview
This project refactors an SMS text classification solution into a function that builds a linear Support Vector Classification (SVC) model. The model is trained to classify SMS text messages as either spam or ham (not spam). The project also integrates a Gradio web application, allowing users to input text messages and test the classification model's performance in real-time.

Project Features
SVC Model: The project constructs a linear Support Vector Classification model to classify SMS messages.
Gradio Interface: A user-friendly web app built using Gradio that allows real-time input and classification of SMS text messages.
SMS Classification: The app predicts whether a given message is spam or not, providing clear feedback to the user.

Files Included
gradio_sms_text_classification.ipynb: Jupyter notebook containing the SMS classification function and Gradio interface.
sms_text_classification_solution.ipynb: Solution notebook with initial code for classification.
SMSSpamCollection.csv: Dataset containing SMS messages labeled as spam or ham.

Load the dataset (SMSSpamCollection.csv) and run the gradio_sms_text_classification.ipynb notebook to build the model and launch the Gradio app. Dataset: https://archive.ics.uci.edu/ml/datasets/SMS+Spam+Collection

Model Development
SMS Classification Function: Extracts features from the text message and trains an SVC model on labeled data.
SMS Prediction Function: Predicts whether a new SMS message is spam or ham, and returns a formatted message to the user.
Gradio Interface: A web-based interface that takes text message inputs and displays classification results.

How to Use
Launch the Gradio app from the Jupyter notebook.
Enter an SMS message into the input box.
The app will classify the message as spam or ham and display the result.

Example Messages for Testing:
You are a lucky winner of $5000!
You won 2 free tickets to the Super Bowl.
You won 2 free tickets to the Super Bowl text us to claim your prize.
Thanks for registering. Text 4343 to receive free updates on medicare.
