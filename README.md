# Holiday Package Purchase Prediction 🚀

## Problem Statement
"Trips & Travel.Com" company wants to enable and establish a viable business model to expand the customer base. One of the ways to expand the customer base is to introduce a new offering of packages. Currently, there are 5 types of packages the company is offering * Basic, Standard, Deluxe, Super Deluxe, King. Looking at the data of the last year, we observed that 18% of the customers purchased the packages. However, the marketing cost was quite high because customers were contacted at random without looking at the available information. The company is now planning to launch a new product i.e. Wellness Tourism Package. Wellness Tourism is defined as Travel that allows the traveler to maintain, enhance or kick-start a healthy lifestyle, and support or increase one's sense of well-being. However, this time company wants to harness the available data of existing and potential customers to make the marketing expenditure more efficient.

## 📌 Project Overview

This project predicts whether a customer will purchase a holiday package based on their demographic and interaction details. It helps travel companies target potential customers more effectively and improve conversion rates.

## ✅ What This Project Does

* Takes customer details (age, occupation, number of trips, passport ownership, etc.).
* Predicts the probability of purchasing a holiday package.
* Trained and evaluated using a supervised machine learning model.

## ⚙️ How I Built It

1. **Data Collection:** Imported the dataset containing customer demographic details and past purchase behaviors.
2. **EDA & Preprocessing:** Handled missing values, encoded categorical features, and performed necessary feature engineering.
3. **Model Training:**

   * Tried multiple models: Logistic Regression, Decision Tree, Random Forest.
   * Evaluated using accuracy, precision, recall.
   * Selected **Random Forest Classifier** as the final model because it performed the best on validation data.
4. **Model Saving:** Used `pickle` to serialize the trained model for deployment.

## 🎯 Why Random Forest?

* Outperformed Logistic Regression and Decision Tree on validation accuracy.
* Handles both numerical and categorical features well.
* Robust to overfitting and can capture complex patterns in the data.
* Final model achieved an **accuracy of \~85%** on the test set.

## 📈 Project Results

* **Accuracy:** \~85% (varies slightly with random state)
* Provides consistent and interpretable predictions.

## 🚀 How To Use

* Load `model.pkl`.
* Provide customer features in the correct order.
* Get a prediction (1 = Will purchase, 0 = Will not purchase).

## 📁 Repository Structure

```
📦 Holiday-Package-Purchase-Prediction
 ├── Notebook_and_Model
 │   ├── main_notebook.ipynb
 │   ├── model.pkl
 ├── README.md
```

## ✨ Future Improvements

* Deploy as a REST API with Flask or FastAPI.
* Build an interactive Streamlit app for business users.
* Improve model by adding more features or trying advanced algorithms.

## 🤝 Contributions

Feel free to fork this project, improve the model, or adapt it for your use case!

---

