# Task 1: Movie Genre Classification

## 📌 Project Overview

The objective of this project is to build a Machine Learning model that can predict the genre of a movie based on its plot summary. The project uses Natural Language Processing (NLP) techniques to preprocess text data and convert it into numerical features for training a classification model.

## 🎯 Objective

To develop a supervised machine learning model that accurately classifies movie genres from textual descriptions.

## 📂 Dataset

The dataset consists of movie plot summaries along with their corresponding genres. It is used to train and evaluate the classification model.

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Jupyter Notebook

## 🔍 Machine Learning Workflow

1. Import the required libraries.
2. Load the movie dataset.
3. Preprocess the text data.
4. Convert text into numerical features using TF-IDF Vectorization.
5. Split the dataset into training and testing sets.
6. Train the machine learning model.
7. Evaluate the model using appropriate performance metrics.
8. Predict the genre of new movie plot summaries.

## 📊 Model Used

* TF-IDF Vectorizer
* Logistic Regression

> **Note:** You can replace **Logistic Regression** with the classifier you actually use (such as Naive Bayes or Support Vector Machine).

## 📈 Results

The trained model successfully predicts movie genres based on plot summaries. The model's performance is evaluated using standard classification metrics such as Accuracy, Precision, Recall, and F1-Score.

## 📁 Project Structure

```text
Task1_Movie_Genre_Classification/
│── Movie_Genre_Classification.ipynb
│── train_data.txt
│── test_data.txt
│── test_data_solution.txt
│── README.md
```

## 🚀 How to Run

1. Clone this repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Run all the cells in sequence.
5. Test the model using new movie plot descriptions.

## 🙏 Acknowledgement

This project was completed as part of the **CodSoft Machine Learning Internship** to gain practical experience in Machine Learning and Natural Language Processing.
