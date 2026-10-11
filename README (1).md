# Email Spam Detection Using Machine Learning

## Internship
Oasis Infobyte Internship (OIBSIP)

## Project Overview
This project uses machine learning and natural language processing
to classify SMS messages as Spam or Ham (Legitimate).

## Dataset
SMS Spam Collection dataset containing labeled SMS messages.

Labels:
- Ham: Legitimate message
- Spam: Unwanted message

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- TF-IDF Vectorization
- WordCloud
- Google Colab

## Project Workflow
1. Load the SMS dataset.
2. Explore the dataset and check missing values and duplicates.
3. Visualize the distribution of Spam and Ham messages.
4. Clean the text messages.
5. Convert text into numerical features using TF-IDF.
6. Split the dataset into training and testing sets.
7. Train Multinomial Naive Bayes and Logistic Regression models.
8. Evaluate both models using accuracy, precision, recall and F1-score.
9. Plot confusion matrices and compare model accuracy.
10. Generate word clouds and test new messages.

## Machine Learning Models
1. Multinomial Naive Bayes
2. Logistic Regression

## Evaluation
The notebook displays the accuracy, classification reports,
confusion matrices and accuracy comparison graph for both models.
Actual scores are available in the notebook output.

## Prediction
The trained model predicts whether a new SMS message is Spam
or Ham. Predictions are not guaranteed to be correct for every message.

## How to Run
Open Email_Spam_Detection.ipynb in Google Colab.
Run the notebook cells in order from top to bottom.

## Conclusion
This project demonstrates how machine learning and text
processing can help identify potential spam messages.
