# 🩺 Lung Cancer Prediction - End-to-End ML Pipeline

## 📌 Project Overview
This project is a **Data-Intensive Computing (DIC)** course project, designed to build an **end-to-end machine learning pipeline** for predicting **lung cancer** based on various health, environmental, and lifestyle factors.

The project covers:
✅ **Exploratory Data Analysis (EDA)**  
✅ **Feature Engineering & Selection**  
✅ **Multiple ML Model Training & Evaluation**  
✅ **Hyperparameter Tuning**  
✅ **Model Deployment (Flask/API)**  

---

## 📂 Folder Structure

DIC-ML-Pipeline/
│── data/                # Raw & Processed Data
│── notebooks/           # Jupyter Notebooks for EDA & Model Training
│── src/                 # Source Code (Preprocessing, Training, etc.)
│── models/              # Saved ML Models
│── deployment/          # API / Web App for Model Deployment
│── requirements.txt     # Dependencies
│── README.md            # Project Documentation
│── .gitignore           # Ignored Files
│── config.yaml          # Configuration File

---

## 🛠 Technologies Used
- **Python**
- **Pandas, NumPy, Matplotlib, Seaborn**
- **Scikit-Learn, XGBoost, Random Forest**
- **Flask / FastAPI (for deployment)**
- **Docker & Streamlit (optional for UI)**

---

## ⚡ Steps to Run This Project

### **1️⃣ Clone the Repository**
git clone https://github.com/your-username/DIC-ML-Pipeline.git
cd DIC-ML-Pipeline

## 2️⃣ Create & Activate Virtual Environment
python -m venv venv
### Activate on Windows
venv\Scripts\activate
### Activate on Mac/Linux
source venv/bin/activate

## 3️⃣ Install Dependencies
pip install -r requirements.txt

## 4️⃣ Run EDA Notebook
## Navigate to the notebooks/ folder and open Jupyter Notebook:
jupyter notebook

## 5️⃣ Train the Model
python src/models/train_model.py

## 6️⃣ Deploy as API (Flask)
python deployment/app.py