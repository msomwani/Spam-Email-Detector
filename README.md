Spam Email Detector

This project is a result of my experiments and learning journey with machine learning and text classification in Python. It detects whether an email is spam or not, using the spam.csv dataset from Kaggle.

About

This repository is primarily a collection of my practice, exploration, and notebook experiments with:

Data preprocessing using pandas and NumPy

Feature extraction with CountVectorizer

Training a simple Naive Bayes model (MultinomialNB) to classify spam

Interactive, hands-on code for learning and tinkering

Getting Started

Clone the repository:

bash
git clone https://github.com/msomwani/Spam-Email-Detector.git
cd Spam-Email-Detector
Install requirements:

bash
pip install pandas numpy scikit-learn
Make sure you have the spam.csv file in this project folder.

Open and run the Jupyter notebook:

bash
jupyter notebook spam-email-detector.ipynb
What the Notebook Shows
Loading and reviewing a real-world spam email dataset

Converting the category labels to 0/1

Splitting for training/testing

Vectorizing email text for machine learning

Building a spam classifier and viewing its accuracy

Writing a prediction function

Experimenting with new email samples to see how the model performs

Notes

The notebook is a sandbox for learning—feel free to explore, modify code, and try new things!

Accuracy and performance may vary depending on the experiments you run.

The code and structure are meant for learning, not production.
