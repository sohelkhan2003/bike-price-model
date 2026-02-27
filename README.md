# 🏍 Used Bike Price Predictor  

A production-ready Machine Learning web application that predicts the resale value of used bikes based on user inputs.  
This project implements a complete ML pipeline — from data preprocessing and feature engineering to model deployment using Flask.

---

## 📌 Project Overview

This project builds a regression model to estimate the selling price of used bikes using historical marketplace data.

The system processes raw input features such as:
- Brand  
- Age of Bike  
- Kilometers Driven  
- Owner Type  
- Fuel Type  

It returns an estimated resale price in real time through a web interface.

---

## 🚀 Key Features

- ✅ End-to-End ML Pipeline (Data Cleaning → Training → Deployment)  
- ✅ Feature Engineering for improved model performance  
- ✅ Outlier Removal using IQR (Interquartile Range) method  
- ✅ Categorical Encoding (Brand, Owner Type, etc.)  
- ✅ Model Saving & Loading using Joblib  
- ✅ Real-Time Price Prediction via Flask Web App  
- ✅ Clean & User-Friendly UI  

---

## 🧠 Machine Learning Details

- **Problem Type:** Regression  
- **Algorithm Used:** Linear Regression  
- **Evaluation Metrics:**
  - R² Score: 0.94  
  - RMSE: ₹32,500  
  - MAE: ₹22,000  

The model explains 94% of the variance in resale prices, indicating strong predictive capability.

---

## 🛠 Tech Stack

### Programming Language
- Python  

### Data Science & ML
- Pandas  
- NumPy  
- Scikit-learn  

### Deployment
- Flask  
- Joblib  

### Frontend
- HTML5  
- CSS3  

---

## 📂 Project Structure

```text
used-bike-price-predictor/
│
├── app.py                  # Flask application logic
├── requirements.txt        # Project dependencies
├── models/
│   └── bike_price_model.pkl
├── templates/
│   └── index.html
├── static/                 # CSS files (if any)
└── README.md
```

---

## ⚙️ How It Works

1. User enters bike details in the web form  
2. Flask backend receives the inputs  
3. Preprocessing steps applied (encoding, transformation, etc.)  
4. Saved ML model is loaded using Joblib  
5. Model predicts the resale price  
6. Prediction displayed instantly on the web interface  

---

## ▶ Run Locally

### 1️⃣ Clone the Repository

```bash
git clone <your-repository-link>
cd used-bike-price-predictor
```

### 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Application

```bash
python app.py
```

### 4️⃣ Open in Browser

```
http://127.0.0.1:5000
```

---

## 🌐 Deployment

This application can be deployed on:

- Render  
- Railway  
- Heroku  
- Any VPS server  

---

## 📊 Model Performance

| Metric | Value |
|--------|--------|
| R² Score | 0.94 |
| RMSE | ₹32,500 |
| MAE | ₹22,000 |

---

## 🎯 Business Impact

- Helps sellers estimate fair market value  
- Assists buyers in avoiding overpayment  
- Can be integrated into online vehicle marketplaces  
- Scalable to other vehicle categories  

---

## 👨‍💻 Author

**Sohel Khan**  
B.Tech – Computer Science (AI/ML)  
Aspiring Data Scientist | ML Developer  

---

⭐ If you found this project useful, consider starring the repository.
