Spam Detection using Naive Bayes

This project implements a spam detection system using the Naive Bayes classifier. It utilizes the sklearn library to preprocess text messages and classify them as spam or ham (not spam).

Dataset

The dataset used is mail_data.csv, which contains two columns:

Category: Labels for messages (ham or spam)

Message: The text content of the messages.

Implementation Steps

Load Dataset: The dataset is read using Pandas.

Data Preprocessing:

Convert categorical labels (ham, spam) into numerical values (0, 1).

Check for missing values and clean the data.

Train-Test Split:

The dataset is split into training (90%) and testing (10%) sets.

Feature Extraction:

Convert text messages into numerical features using TfidfVectorizer.

Model Training:

A MultinomialNB classifier is trained using the extracted features.

Prediction & Evaluation:

The trained model is used to predict labels for test data.

The accuracy of the model is evaluated.

Code Usage

Run the script using:

python spam_detection.py

Expected Output

The model will classify messages as spam or ham.

The accuracy of the model will be displayed.

Results:

The model achieves high accuracy in classifying messages as spam or ham using Naive Bayes.
