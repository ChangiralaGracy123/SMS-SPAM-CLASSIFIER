# SMS-SPAM-CLASSIFIER
The SMS Spam Classifier is a machine learning project designed to detect spam messages sent via Short Message Service (SMS). By leveraging natural language processing (NLP) techniques and a supervised learning approach, this classifier accurately identifies whether an SMS is spam or not.

Key Features
Dataset Utilized

The classifier was built using the Email/SMS Spam Classifier dataset for training and evaluation.
Data Preprocessing

Cleaned and processed raw text data by:
Converting to lowercase.
Removing punctuation.
Handling stop words to eliminate irrelevant words and improve model efficiency.
Feature Engineering

Converted text data into numerical form using TF-IDF (Term Frequency-Inverse Document Frequency) vectors to effectively capture word importance for classification tasks.
Model Selection and Training

Implemented a Naive Bayes Classifier (Multinomial), known for its effectiveness in text-based classification tasks, to categorize SMS messages as spam or non-spam.
Model Evaluation

Assessed model accuracy and reliability using:
Accuracy metrics.
Classification reports to analyze precision, recall, and F1 scores.
Tools and Technologies Used
Python: Primary programming language.
pandas: For data manipulation and analysis.
scikit-learn: For feature engineering and machine learning implementation.
Natural Language Processing (NLP): For text cleaning, preprocessing, and vectorization.
Outcome
The SMS Spam Classifier provides an efficient and accurate mechanism to detect and filter spam messages, showcasing robust machine learning and NLP capabilities. This project is an excellent demonstration of end-to-end text classification, from raw data preprocessing to model deployment.






