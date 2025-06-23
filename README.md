**Car Rental Customer Feedback Analyzer**
This project analyzes customer feedback from car rental services. It uses Natural Language Processing (NLP) to identify the sentiment of each review (positive, negative, or neutral) and highlights common issues like car condition, delivery delays, or customer service problems. The goal is to help service teams improve the customer experience through automated insights.

**Project Features**
1) Performs sentiment analysis on feedback using a transformer model
2) Supports automatic tagging of unlabeled feedback
3) Generates a final report with predicted sentiments
4) Fully compatible with Google Colab for ease of use

**Dataset Description**
_car_train.csv_
This file contains 500 labeled feedback entries with the following columns:
1) sr_no
2) feedback
3) sentiment

_car_test.csv_
This file contains 50 feedback entries where the sentiment column is left blank. The model will predict and fill these values.

**How to Use the Project**
Step 1- Open the provided Google Colab notebook.
Step 2- Upload the car_test.csv and car_train.csv file when on colab.
Step 3- The notebook will:
        a. Read the feedback
        b. Predict the sentiment using a pretrained transformer model
        c.Save the updated file as car_test_with_sentiment.csv
Step 4- You can then download the final CSV file with the predicted sentiments.

**Tools and Technologies Used**
1. Google Colab
2. Python (pandas, transformers)
3. HuggingFace Transformers
4. CSV/XLS files

