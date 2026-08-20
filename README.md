# titanaic_survival
# Titanic Survival Prediction

A machine learning project based on the Titanic dataset to analyze passenger information and prepare data for predicting passenger survival.

## 📌 Project Overview

This project explores the famous Titanic dataset using Python and machine learning techniques. The dataset contains information about passengers such as passenger class, gender, age, number of siblings/spouses, parents/children, fare, and port of embarkation.

The project focuses on data exploration, preprocessing, handling missing values, and converting categorical data into numerical form for machine learning.

## 🛠️ Technologies Used

* Python
* NumPy
* Pandas
* Seaborn
* Matplotlib
* Scikit-learn
* Google Colab

## 📊 Dataset

The Titanic dataset is loaded using Seaborn's built-in dataset:


The original dataset contains **891 rows and 15 columns**.

Important features include:

* `survived` – Survival status (target variable)
* `pclass` – Passenger class
* `sex` – Gender
* `age` – Passenger age
* `sibsp` – Number of siblings/spouses aboard
* `parch` – Number of parents/children aboard
* `fare` – Passenger fare
* `embarked` – Port of embarkation
* `alone` – Whether the passenger was traveling alone

## 🔍 Data Preprocessing

The following preprocessing steps were performed:

1. Loaded the Titanic dataset.
2. Explored the dataset using `head()`, `columns`, `isnull().sum()`, and `info()`.
3. Removed columns that were not required for the analysis.
4. Handled missing values in the `age` column using the mean.
5. Removed rows with missing `embarked` values.
6. Converted categorical features such as `sex` and `embarked` into numerical values using `LabelEncoder`.
7. Converted the processed dataframe into integer format.

After preprocessing, the dataset contains **889 records and 9 features**.

## ▶️ How to Run

### Option 1: Google Colab

Open the notebook directly in Google Colab and run the cells sequentially.


## 📈 Learning Outcomes

Through this project, I practiced:

* Exploratory Data Analysis (EDA)
* Data cleaning
* Handling missing values
* Feature selection
* Categorical data encoding
* Pandas and NumPy operations
* Data visualization using Seaborn and Matplotlib
* Preparing datasets for machine learning

## 🔗 Google Colab

The notebook can be opened directly in Google Colab using the Colab link included in the notebook.

## 👨‍💻 Author

**Aaditya Bisht**

B.Tech Computer Science & Engineering

GitHub: [aaditya-codes-eng](https://github.com/aaditya-codes-eng)
