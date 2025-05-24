# 🏡 Predicting Future Trends in Land Prices

A machine learning-based web application that predicts future land prices based on historical data and socio-economic indicators. This platform helps buyers, investors, developers, and policymakers make informed real estate decisions.

## 📌 Problem Statement

The project aims to develop a robust platform for predicting future land prices using historical datasets and ML algorithms. The application provides users with land price trends, insights, and personalized notifications.

---

## 🧩 Features

### 🔐 Functional Requirements
- **User Authentication:** Role-based access for users and admins.
- **Dashboard:** Interactive charts displaying current and future trends.
- **Data Upload:** Admins can manage datasets via CSV/Excel.
- **Prediction Tool:** Predict land prices using ML models.
- **Historical Visualization:** Track and analyze previous trends.
- **Advanced Search & Filter:** Query by area, land type, and price range.
- **Download Reports:** Generate summaries.
- **Email Notifications:** Admin alerts for specific regions.

### ⚙️ Non-Functional Requirements
- Scalability, Stability, and Performance
- Simple, Responsive UI
- Secure data handling with encryption
- Easy maintainability and portability

---

## 🧪 ML Models Used
- **Linear Regression**
- **Random Forest Regressor**
- **K-Nearest Neighbors (KNN)**

Each model is trained on cleaned, normalized, and feature-engineered data for accurate predictions.

---

## 🔍 Key Components

### 1. **Land Price Predictor**
- Predict future prices using user inputs.
- Calculate inflation-adjusted trends.
- Visualize predicted vs current prices.

### 2. **Search with Filters**
- Query by region, land use type, and price.
- Get predictions for selected entries.
- Visual feedback for average price comparison.

### 3. **Notification System**
- Admins send real-time alerts based on region.
- Emails triggered for interested users.

---

## 🧱 Tech Stack

- **Frontend:** HTML5, CSS3
- **Backend:** Python Flask
- **Database:** Oracle SQLPlus
- **ML Libraries:** Scikit-learn, TensorFlow, Pandas, NumPy
- **Visualization:** Matplotlib, Seaborn

---

## 🛠️ Project Workflow

1. **Data Collection & Preprocessing**
2. **Model Training**
3. **Flask Backend Development**
4. **Frontend UI Development**
5. **Testing & Optimization**
6. **Deployment & Monitoring**

---

## 🔐 Security Considerations

- Role-based login
- Hashed passwords
- Data encryption (in transit & at rest)
- Session management
- IP filtering & firewall for admin panel

---

## 📊 Sample Output

- Interactive trend plots (`price_prediction.png`)
- CSV-based predictions
- Region-wise clustering & similar area suggestion

---

## 📚 Learning Outcomes

- Applied ML for real-world data prediction.
- Developed full-stack web apps using Flask.
- Learned software engineering practices (version control, modularization).
- Integrated security principles and REST APIs.
- Gained experience in collaborative team development.

---

## 📂 Directory Structure (suggested)
project-root/
│
├── data/
│   └── land_prediction_Dataset.csv
│
├── models/
│   └── *.joblib (trained model files)
│
├── static/
│   └── price_prediction.png
│
├── templates/
│   ├── search/
│   │   ├── search_index.html
│   │   └── search_result.html
│   │
│   ├── admin_dashboard.html
│   ├── faqs.html
│   ├── first_pg.html
│   ├── home.html
│   ├── index.html
│   ├── login.html
│   ├── notifications.html
│   ├── predict.html
│   ├── predict_search.html
│   ├── register.html
│   └── result.html
│
├── app.py
├── predictor.py
├── search.py
├── notify.py
└── requirements.txt
