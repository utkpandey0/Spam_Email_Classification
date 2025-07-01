# Spam_Email_Classification
This project aims to automatically detect whether an email is spam or not spam (ham) using machine learning. Spam detection is important to protect users from unwanted or harmful emails.

We use a labeled dataset of emails, where each email is marked as spam or ham. The email text is first cleaned and processed using Natural Language Processing (NLP) techniques such as lowercasing, removing punctuation, stopwords removal, and tokenization. Then, the text is converted into numerical features using techniques like Bag of Words or TF-IDF (Term Frequency-Inverse Document Frequency).

We train machine learning models like Naive Bayes, Logistic Regression, or Support Vector Machine (SVM) on this data. The models are evaluated using metrics such as accuracy, precision, recall, and F1-score.

A simple user interface is created using Gradio, where users can enter an email and the app will classify it as spam or not spam instantly.
