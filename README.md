# 🧠 Telco Customer Churn Prediction

![Churn Project Banner](Telco4.jpg)

## 📘 Table of Contents
1. [Project Overview](#project-overview)
2. [Business Problem](#business-problem)
3. [Solution Architecture](#solution-architecture)
4. [Churn Segments & Loyalty Drivers](#churn-segments--loyalty-drivers)
5. [Technology Stack](#technology-stack)
6. [Folder Structure](#folder-structure)
7. [How to Run](#how-to-run)
8. [Model Performance](#model-performance)
9. [Future Scope](#future-scope)
10. [Author & Contact](#author--contact)

---

## 📌 Project Overview

This project presents a full-fledged churn prediction system designed for telecom operators. It leverages machine learning and a Flask-based web application to identify customers likely to churn and helps define proactive retention strategies.

---

## ❓ Business Problem

Churn is one of the most expensive issues faced by telecom providers. The cost of acquiring new customers is often higher than retaining existing ones. This project aims to predict which customers are likely to churn and understand the reasons why, enabling smarter decision-making.

---

## 🧩 Solution Architecture


### 🔧 Key Functionalities:
- Customer 360° Profile View
- Behavioral Segmentation
- Churn Prediction using Random Forest
- Web-based scoring application using Flask

---

## 🔍 Churn Segments & Loyalty Drivers

### 🎯 Identified Customer Segments:
- **Conditionally Loyal Subscriber**: Value-driven, but not locked in
- **Conditional Churner**: Evaluates better offers, price sensitive
- **Lifestyle Migrator**: Churns due to circumstantial or lifestyle shifts
- **Unsatisfied Churner**: Likely to leave due to poor experience

### 💡 Key Loyalty/Churn Triggers:
- Handset loss or upgrade
- Network quality issues
- Offers, pricing, and service plans
- Customer support satisfaction

![Churn Segmentation](Telco5.jpg)

---

## 🛠️ Technology Stack

| Category         | Tools/Tech                      |
|------------------|---------------------------------|
| Programming      | Python, Flask                   |
| ML Models        | Random Forest (Scikit-learn)    |
| Data Handling    | Pandas, NumPy                   |
| Visualization    | Matplotlib, Seaborn             |
| Model Persistence| Pickle                          |
| Frontend         | HTML/CSS via Flask Templates    |

---

---

## ▶️ How to Run

```bash
# 1. Clone the repository
git clone https://github.com/your-username/telco-churn-prediction.git
cd telco-churn-prediction

# 2. Install dependencies
pip install -r requirements.txt

# 3. Run the Flask app
python app.py

# 4. Visit the app in your browser
http://127.0.0.1:5000/
