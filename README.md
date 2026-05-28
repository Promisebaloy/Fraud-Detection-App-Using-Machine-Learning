# Fraud Detection Analysis App

## Project Overview

The Fraud Detection Analysis App is a Machine Learning-powered web application designed to detect fraudulent financial transactions in real time. The project combines data analysis, predictive modeling, and deployment using Streamlit to provide an interactive platform for fraud prediction.

The system was trained on over 6.3 million transaction records and achieved a precision score of 94.78%, demonstrating strong performance in identifying fraudulent activities while minimizing false fraud alerts.

---

# Objectives

* Analyze transaction data to identify fraud patterns and trends.
* Build and evaluate Machine Learning models for fraud detection.
* Deploy the trained model using a Streamlit web application.
* Enable real-time fraud prediction through user-input transaction details.

---

# Dataset Summary

The dataset contains approximately **6,362,620 records** and **11 variables** related to financial transactions.

### Features Included

* Transaction Type
* Transaction Amount
* Sender Balance Before Transaction
* Sender Balance After Transaction
* Receiver Balance Before Transaction
* Receiver Balance After Transaction
* Fraud Indicator (Target Variable)

---

# Data Quality Assessment

A data quality assessment was conducted to ensure reliability and completeness of the dataset.

### Findings

* No missing values were identified.
* Data structure and formatting were consistent.
* Dataset was suitable for Machine Learning analysis and model training.

---

# Exploratory Data Analysis (EDA)

EDA was performed using Python libraries such as Pandas and Matplotlib to better understand the dataset.

### Key Analysis Performed

* Reviewed dataset structure using:

  * `df.head()`
  * `df.info()`
* Examined data types and feature distributions.
* Analyzed transaction patterns and fraud behavior.
* Identified categorical and numerical variables.
* Visualized transaction type distributions.
* Investigated fraud occurrence across transaction categories.
* Created transaction amount histograms.
* Analyzed fraud trends over time.
* Generated a correlation matrix heatmap.
* Identified high-risk accounts associated with large transactions.

---

# Machine Learning Model Development

## Data Preprocessing

* Removed unnecessary columns and irrelevant variables.
* Defined feature variables and target variable.
* Prepared the dataset for model training and evaluation.

## Model Training

The project used Machine Learning techniques to classify transactions as fraudulent or legitimate.

### Steps Included

* Data splitting into training and testing datasets.
* Pipeline setup for preprocessing and model training.
* Evaluation of multiple Machine Learning algorithms.
* Comparison of model performance metrics.

### Final Model Performance

* Precision Score: **94.78%**

The final model demonstrated strong predictive capability in detecting fraudulent transactions.

---

# Streamlit Web Application

A Streamlit-based web application was developed to deploy the trained Machine Learning model.

## Features

* Interactive user interface
* Real-time fraud prediction
* User input transaction details
* Instant prediction output
* Reusable saved Machine Learning pipeline

---

# Technologies Used

## Programming Language

* Python

## Libraries & Tools

* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Streamlit
* Joblib

---

# Project Structure

```bash
Fraud-Detection-App/
│
├── data/
├── notebooks/
├── models/
├── app.py
├── requirements.txt
├── fraud_model.pkl
├── README.md
└── assets/
```

---

# Installation

## Clone the Repository

```bash
git clone https://github.com/yourusername/fraud-detection-app.git
```

## Navigate to the Project Directory

```bash
cd fraud-detection-app
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

# Running the Application

Run the Streamlit application using:

```bash
streamlit run app.py
```

---

# Results

The project successfully demonstrated how Machine Learning can be applied to fraud detection in financial transactions.

### Key Achievements

* Processed over 6.3 million transaction records.
* Built a high-performing fraud detection model.
* Achieved 94.78% precision.
* Developed a real-time prediction web application.
* Improved fraud identification and transaction security capabilities.

---

# Conclusion

The Fraud Detection Analysis App highlights the effectiveness of Machine Learning in identifying fraudulent financial transactions. By integrating data preprocessing, predictive analytics, and a user-friendly Streamlit interface, the project provides a practical solution for real-time fraud detection.

The application can support financial institutions in:

* Improving transaction security
* Reducing financial losses
* Enhancing fraud prevention strategies
* Detecting suspicious transaction behavior efficiently

---

# Future Improvements

* Add additional fraud detection algorithms
* Deploy the application to cloud platforms
* Integrate real-time transaction APIs
* Improve model recall and overall performance
* Add dashboard analytics and reporting features

---

# Author

Promise Baloyi
