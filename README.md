# 🏠 Bangalore House Price Prediction

A **Machine Learning project** that predicts house prices in Bangalore using property features such as **location, BHK, total square feet, and number of bathrooms**.

## 📌 Project Overview

House prices in Bangalore vary significantly depending on the property's location, size, and facilities. This project analyzes housing data and applies Machine Learning techniques to predict property prices.

The project mainly focuses on:

* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Outlier Handling
* Categorical Encoding
* Regression-based Price Prediction

## 📂 Dataset

The project uses the **Bengaluru House Price Dataset**, containing **13,320 property records**.

🔗 **Dataset:** [Bengaluru House Price Data — Kaggle](https://www.kaggle.com/datasets/amitabhajoy/bengaluru-house-price-data)

### Important Features

| Feature      | Description                |
| ------------ | -------------------------- |
| `location`   | Location of the property   |
| `size`       | Number of bedrooms/BHK     |
| `total_sqft` | Total area of the property |
| `bath`       | Number of bathrooms        |
| `price`      | Target house price         |

## ⚙️ Project Workflow

```text
Dataset
   ↓
Data Cleaning
   ↓
Missing Value Handling
   ↓
Feature Engineering
   ↓
Outlier Removal
   ↓
Categorical Encoding
   ↓
Train-Test Split
   ↓
Model Training
   ↓
Model Evaluation
   ↓
Price Prediction
```

## 🧹 Data Preprocessing

The dataset is cleaned and prepared before training the Machine Learning model.

Key steps include:

* Removing unnecessary columns.
* Handling missing values.
* Converting `size` into a numerical **BHK** feature.
* Processing `total_sqft` values and ranges.
* Removing abnormal/outlier observations.
* Encoding the `location` feature into numerical values.

## 🔍 Exploratory Data Analysis

EDA is performed to understand the relationship between property characteristics and price.

The analysis focuses on:

* House prices across different locations.
* Relationship between BHK and price.
* Effect of total square feet on price.
* Relationship between bathrooms and house price.
* Distribution of property prices.

## 🤖 Machine Learning

The target variable is:

```text
price
```

The main features used for prediction are:

```text
location
bhk
total_sqft
bath
```

The processed data is divided into training and testing sets, after which a regression model is trained to predict house prices.

## 📊 Result

The trained Machine Learning model predicts Bangalore house prices based on important property characteristics such as **location, area, BHK, and bathrooms**.

Model performance is evaluated using the test dataset to determine how well the model performs on unseen properties.

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Matplotlib**
* **Seaborn**
* **Scikit-learn**
* **Jupyter Notebook**

## 📁 Project Structure

```text
Bangalore-House-Price-Prediction/
│
├── data/
│   └── Bengaluru_House_Data.csv
│
├── notebooks/
│   └── house_price_prediction.ipynb
│
├── README.md
└── requirements.txt
```

## ⭐ Skills Demonstrated

`Python` • `Pandas` • `NumPy` • `EDA` • `Data Cleaning` • `Feature Engineering` • `Outlier Handling` • `Categorical Encoding` • `Regression` • `Scikit-learn` • `Machine Learning`
