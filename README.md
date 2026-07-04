# Data-Driven-Cardiovascular-Risk-Prediction-Using-Classification-Models

# 🫀 Data-Driven Cardiovascular Risk Prediction Using Classification Models

## 📌 Overview
This project focuses on predicting the risk of cardiovascular (heart) disease using Machine Learning classification models. The system analyzes patient health data and determines whether a person is at **high risk or low risk** of developing heart disease.

The goal is to assist in **early diagnosis and preventive healthcare** using data-driven insights.

---

## 🎯 Problem Statement
Cardiovascular diseases are one of the leading causes of death worldwide. Early detection is crucial, but traditional diagnosis methods can be time-consuming and may not always leverage historical data effectively.

There is a need for:
- Fast and accurate risk prediction  
- Data-driven healthcare decisions  
- Automated screening systems  

---

## 💡 Solution
This project builds a Machine Learning-based system that:
- Analyzes patient medical data  
- Trains classification models  
- Predicts cardiovascular risk  
- Provides results through a simple web interface  

---

## ⚙️ Tech Stack

| Category | Tools |
|--------|------|
| Programming | Python 🐍 |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn |
| Backend | Flask |
| Visualization | Matplotlib |
| Frontend | HTML, CSS |

---

## 📊 Dataset
- **Dataset Used:** UCI Heart Disease Dataset  
- Contains patient health information such as:
  - Age  
  - Sex  
  - Blood Pressure  
  - Cholesterol  
  - Maximum Heart Rate  
  - Chest Pain Type  

- **Target Variable:**
  - `0` → No Heart Disease  
  - `1` → Heart Disease  

---

## 🧠 Machine Learning Models Used
- Logistic Regression  
- Decision Tree Classifier  
- Random Forest Classifier ⭐  
- Support Vector Machine (SVM)  

👉 **Best Performing Model:** Random Forest (highest accuracy)

User Input → Data Processing → ML Model → Risk Prediction → Output Display


---

## ✨ Features
- 🫀 Predicts heart disease risk (High / Low)  
- 🤖 Multiple ML model comparison  
- 📊 Accuracy evaluation  
- 🌐 Simple web interface using Flask  
- ⚡ Fast and efficient predictions  

---

## 📁 Project Structure


cardio-risk-prediction/
│
├── app.py
├── model_training.py
├── model.pkl
├── requirements.txt
├── README.md
│
├── data/
│ └── heart.csv
│
├── templates/
│ └── index.html
│
├── static/
│
├── screenshots/
│ └── output.png


---

## ▶️ How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-username/cardio-risk-prediction.git
cd cardio-risk-prediction
2️⃣ Install Dependencies
pip install -r requirements.txt
3️⃣ Train the Model
python model_training.py
4️⃣ Run the Application
python app.py
5️⃣ Open in Browser
http://127.0.0.1:5000/
📈 Model Performance
Random Forest achieved the highest accuracy among all models
Model performance may vary based on dataset preprocessing

🚀 Future Improvements
🔥 Deploy on cloud (AWS / Render / Heroku)
📱 Build mobile application
🧠 Use Deep Learning models
📊 Improve dataset size for better accuracy
🧪 Challenges Faced
Data preprocessing and cleaning
Model selection and tuning
Integrating ML with web application
🏆 Learning Outcomes
End-to-end Machine Learning project development
Model training and evaluation
Flask-based web deployment
Real-world healthcare application
👩‍💻 Author

Ega Meghana

---

## 🔄 System Workflow
