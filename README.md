# 💳 Credit Card Fraud Detection using Random Forest

![](https://github.com/Jamestown34/Credit-Card-Fraud-Detection-Supervised-Machine-Learning-/blob/main/card/download.jpeg) <!-- Optional image showing fraud prediction insights -->

## 🧠 Project Overview

In this project, I addresswed the pressing issue of **credit card fraud** by building a machine learning model using the **Random Forest Classifier**. The model is trained to distinguish between legitimate and fraudulent transactions based on various features such as transaction amount, location data, and population of the user's city.

my goal is to create a tool that can accurately flag suspicious transactions, aiding financial institutions in reducing fraud and protecting customers.

---

## 🎯 Problem Statement

Credit card fraud can have devastating financial impacts if not detected early. Traditional rule-based systems often generate too many false positives or miss evolving fraud patterns.

### Objective:
- Detect fraudulent transactions using **Random Forest**
- Clean and preprocess transactional data
- Evaluate predictions and simulate new cases
- Identify the most influential features in fraud detection


![](https://github.com/Jamestown34/Credit-Card-Fraud-Detection-Supervised-Machine-Learning-/blob/main/card/Screenshot%20(55).png)

---

## 📚 Dataset

- **Source**: Synthetic dataset (Kaggle-based)
- **Records**: Thousands of transaction entries
- **Features**: Transaction time, merchant info, amount, location coordinates, city population, and more
- **Target**: `is_fraud` (1 = fraud, 0 = legitimate)

### 🔧 Feature Selection

After preprocessing, key features used:
- `amt`: Transaction amount  
- `lat`: Customer location  
- `merch_lat`: Merchant location  
- `city_pop`: Population of the customer’s city

Features removed for clarity and relevance:

## 🛠 Tools & Technologies

- **Python**
- **Pandas & NumPy**
- **Scikit-learn** (`RandomForestClassifier`, model evaluation)
- **Matplotlib & Seaborn** (visualizations)
- **Jupyter Notebook**
- 


![](https://github.com/Jamestown34/Credit-Card-Fraud-Detection-Supervised-Machine-Learning-/blob/main/card/Screenshot%20(56).png)

---

## 🔬 Methodology

### ✅ Step-by-step:

#### 1. **Data Cleaning**
- Dropped irrelevant columns
- Handled missing values
- Checked class balance

#### 2. **Feature Engineering**
- Focused on location and transaction-based metrics

#### 3. **Model Training**
- Trained a `RandomForestClassifier` on the cleaned dataset
- Split data into training and testing sets

#### 4. **Prediction Simulation**
- Simulated prediction using sample transaction inputs

---

## 📊 Results & Evaluation

- The model achieved strong performance across key metrics:
  - **Accuracy**: High
  - **Recall (Fraud Detection)**: Prioritized
  - **Precision**: Tuned to reduce false alarms

### 🔑 Key Indicators:
- Large transaction amounts  
- Remote merchant-customer distances  
- Low population areas  

These features contributed the most to identifying fraudulent transactions.

> ⚠️ **Common Warning**: `X does not have valid feature names` — safe to ignore for input simulations.

---

## 💡 Insights & Implications

This project demonstrates how **machine learning can automate fraud detection** by learning from historical patterns. Even without detailed personal or banking information, the model could successfully flag risky transactions using a few insightful features.

### ✅ Benefits:
- **Real-time fraud alerts**
- **Enhanced customer protection**
- **Reduced financial loss** for financial institutions



![](https://github.com/Jamestown34/Credit-Card-Fraud-Detection-Supervised-Machine-Learning-/blob/main/card/Screenshot%20(57).png)

---

## 🚀 Next Steps

- Explore advanced models like **XGBoost** or **LightGBM**
- Add **time-based features** (hour, day, frequency)
- Build a **fraud monitoring dashboard**
- Integrate with APIs for **live prediction streaming**
- Apply **clustering techniques** to detect fraud rings

---

## 🤝 Let's Connect

If you're interested in fraud analytics, fintech AI, or want to collaborate on a project, feel free to **fork the repo** or **reach out**!

> _"Stopping fraud before it starts — with the power of data."_ 💡


