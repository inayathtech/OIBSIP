# Iris Flower Classification

## Objective
The objective of this project is to build a machine learning model that can classify Iris flowers into different species based on their sepal and petal measurements.

## Dataset
The Iris dataset from Scikit-learn was used for this project.

- Number of samples: 150
- Features: 4
  - Sepal length
  - Sepal width
  - Petal length
  - Petal width
- Target: Iris species

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Steps

1. Loaded the Iris dataset.
2. Converted the dataset into a Pandas DataFrame.
3. Performed exploratory data analysis.
4. Checked for missing values.
5. Created pairplots and boxplots.
6. Split the data into 80% training and 20% testing sets.
7. Trained multiple machine learning models.
8. Evaluated the models using accuracy, confusion matrix, and classification reports.
9. Compared the performance of the models.

## Machine Learning Models

The following models were used:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest

## Results

| Model | Accuracy |
|---|---:|
| Logistic Regression | 96.67% |
| KNN | 100.00% |
| Decision Tree | 93.33% |
| Random Forest | 90.00% |

For this particular train-test split, KNN achieved the highest test accuracy of 100%.

## Conclusion

The machine learning models were able to classify Iris flower species using their sepal and petal measurements. Among the tested models, KNN produced the highest accuracy on the test set used in this project.

## Internship
This project was completed as part of the Oasis Infobyte Internship Program (OIBSIP).  