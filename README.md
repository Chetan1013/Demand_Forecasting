
# 📈 Demand Forecasting Using Machine Learning

A Machine Learning-powered Demand Forecasting application built using Streamlit and XGBoost to predict product demand based on pricing, discounts, inventory levels, promotions, competitor pricing, and product category.

The project helps businesses make data-driven inventory and pricing decisions by forecasting future product demand accurately.

---

# 🚀 Project Goal

The primary goal of this project is to build an intelligent demand forecasting system that helps businesses:

- Predict product demand in advance
- Optimize inventory management
- Reduce overstocking and stock shortages
- Improve pricing and promotional strategies
- Support data-driven business decisions

The application uses Machine Learning techniques to analyze multiple business-related factors and generate accurate demand predictions in real time.

---

# ✨ Features

- Real-time demand prediction
- Interactive Streamlit web application
- XGBoost Regression model integration
- Encoded categorical feature handling
- User-friendly interface for business inputs
- Fast and efficient forecasting system

---

# 🧠 Machine Learning Workflow

The project follows a complete Machine Learning pipeline:

1. Data Collection
2. Data Cleaning & Preprocessing
3. Feature Encoding using Label Encoders
4. Model Training using XGBoost Regressor
5. Model Serialization using Pickle
6. Deployment with Streamlit

---

# 📂 Project Structure

```bash
Demand_Forecasting/
│
├── app.py
├── xgboost_demand_model.pkl
├── label_encoders.pkl
├── Demand_Forecasting-checkpoint.ipynb
├── ML_model-checkpoint.ipynb
├── requirements.txt
└── README.md
````

---

# 📊 Input Features

The model predicts demand based on the following business features:

* Price
* Discount
* Inventory Level
* Promotion Status
* Competitor Pricing
* Product Category

---

# ⚙️ Technologies Used

* Python
* Streamlit
* Pandas
* NumPy
* Scikit-learn
* XGBoost
* Pickle

---

# 🖥️ Web Application

The application provides an interactive dashboard where users can:

* Enter product details
* Select category and promotion status
* Predict product demand instantly

The prediction result is displayed in real time using the trained Machine Learning model.

---

# ▶️ How to Run the Project

## 1️⃣ Clone Repository

```bash
git clone https://github.com/your-username/Demand_Forecasting.git
```

---

## 2️⃣ Navigate to Project Folder

```bash
cd Demand_Forecasting
```

---

## 3️⃣ Create Virtual Environment

### Windows

```bash
python -m venv .venv
```

### Activate Environment

```bash
.venv\\Scripts\\activate
```

---

## 4️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 5️⃣ Run Streamlit Application

```bash
streamlit run app.py
```

The application will open in your browser automatically.

---

# 📌 Example Requirements

```txt
streamlit
pandas
numpy
scikit-learn
xgboost
```

---

# 📈 Future Improvements

* Add advanced forecasting algorithms
* Integrate time-series forecasting
* Add graphical analytics dashboard
* Deploy using Streamlit Cloud or Render
* Add database integration
* Improve prediction accuracy using hyperparameter tuning

---

# 📷 Project Output

The model generates predicted demand values based on user-provided business parameters, enabling smarter inventory and sales planning.

