# Complete Data Analysis Project (Wine Quality)

## 📌 Project Overview

This project explores the relationship between wine quality and its chemical properties using various data analysis techniques, including data cleaning, clustering, and regression analysis.

## 🚀 Features
* **Data**
  * https://www.kaggle.com/datasets/ghassenkhaled/wine-quality-data?resource=download

* **Data Cleaning and Preparation**

  * Missing values handled using `SimpleImputer` (Median strategy).
  * Outliers removed using the Interquartile Range (IQR) method.
  * Data scaled using `StandardScaler`.

* **K-Means Clustering**

  * Optimal number of clusters determined using Elbow and Silhouette methods.
  * Clear cluster visualization with well-labeled scatter plots.

* **Logistic Regression (Classification)**

  * Binary classification of wine quality (Good vs. Bad).
  * Clear classification report and confusion matrix.

* **Linear Regression and Regularized Regression**

  * Simple Linear Regression for quality prediction.
  * Ridge and Lasso Regression for regularization.

## 📊 Key Results

* K-Means Clustering revealed distinct groups of wine types.
* Logistic Regression achieved an accuracy of **75%**, with good precision and recall for higher quality wines.
* Linear Regression showed limited predictive power (**R² ≈ 0.28**).
* Ridge and Lasso Regression improved model stability but not significantly in performance.


## 💡 How to Use

1. **Clone the repository:**

```bash
git clone https://github.com/yourusername/wine-quality-analysis.git
```

2. **Install the required libraries:**

```bash
pip install -r requirements.txt
```

3. **Run the Jupyter Notebook for complete analysis.**

## 📌 Requirements

* Python 3.x
* pandas, numpy, matplotlib, seaborn
* scikit-learn

## 📌 About
* Name: Abdul Rehman 
* Student Number: 23113350 
* GitHub Repository: https://github.com/AR-KASHMIRI47/REFERRAL-Clustering-and-Fitting