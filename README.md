# 💳 Credit Card Fraud Detection

A machine learning and web-integrated solution to detect fraudulent credit card transactions, developed by **PoojithaReddy Chavali**. This project includes end-to-end processing: from dataset analysis and model building to a deployable Django backend.

---

## 📁 Project Structure

Credit-Card-Fraud-Detection/
│
├── Backend/ # ML model development
│ ├── Credit_Card (1).ipynb # Jupyter Notebook with model training
│ ├── data.csv # Input dataset
│ ├── Hybrid.pkl # Trained ML model
│
├── Credit/ # Django app for prediction
│
├── manage.py # Django project management
├── db.sqlite3 # Database
├── requirements.txt # Python dependencies
├── README.md # Project documentation
└── 2.wav # Optional asset

yaml
Copy
Edit

---

## 🔍 Key Features

- 📊 Exploratory Data Analysis (EDA)
- ⚖️ Class imbalance handled using **SMOTE**
- 🤖 Trained models: Logistic Regression, Random Forest, XGBoost
- 🧠 Saved best model (`Hybrid.pkl`) for deployment
- 🌐 Django-based web backend
- 📈 Evaluation metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC

---

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/PoojithaReddyChavali/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
3. Run Django App
bash
Copy
Edit
python manage.py runserver
Visit http://127.0.0.1:8000/ in your browser to use the web interface.

📊 Dataset
📂 Source: Kaggle – Credit Card Fraud Detection

📈 Contains 284,807 transactions with 492 frauds (~0.17%)

🔐 Features are anonymized using PCA (V1 to V28), plus Time, Amount, and Class

🛠 Tech Stack
Languages: Python, HTML (via Django)

ML Libraries: pandas, NumPy, scikit-learn, XGBoost, imbalanced-learn

Visualization: Matplotlib, Seaborn

Backend: Django, SQLite

Model: Hybrid.pkl (best performing)

✅ Results
✅ ROC-AUC: > 0.95

✅ Balanced fraud detection with improved recall

✅ Optimized and ready for real-time integration

