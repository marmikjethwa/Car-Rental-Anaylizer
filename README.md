Car Rental Customer Feedback Analyzer
This project analyzes customer feedback from car rental services. It uses Natural Language Processing (NLP) to identify the sentiment of each review (positive, negative, or neutral) and highlights common issues like car condition, delivery delays, or customer service problems. The goal is to help service teams improve the customer experience through automated insights.

Project Features
Performs sentiment analysis on feedback using a transformer model

Supports automatic tagging of unlabeled feedback

Generates a final report with predicted sentiments

Fully compatible with Google Colab for ease of use

Dataset Description
car_train.csv
This file contains 500 labeled feedback entries with the following columns:

sr_no

feedback

sentiment

car_test.csv
This file contains 50 feedback entries where the sentiment column is left blank. The model will predict and fill these values.

How to Use the Project
Open the provided Google Colab notebook.

Upload the car_test.csv file when prompted.

The notebook will:

Read the feedback

Predict the sentiment using a pretrained transformer model

Save the updated file as car_test_with_sentiment.csv

You can then download the final CSV file with the predicted sentiments.

Tools and Technologies Used
Google Colab

Python (pandas, transformers)

HuggingFace Transformers

CSV/XLS files

