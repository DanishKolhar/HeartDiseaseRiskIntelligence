# ❤️ Heart Disease Risk Intelligence

An AI-powered web application that predicts the likelihood of heart disease using a Machine Learning model. Built with Streamlit and scikit-learn, the application provides real-time risk assessment based on patient health parameters.

---

## 🚀 Features

- 🩺 Predicts heart disease risk from clinical data
- ⚡ Real-time predictions using a trained K-Nearest Neighbors (KNN) model
- 📊 Interactive and user-friendly Streamlit interface
- 🔄 Automatic feature scaling using a saved StandardScaler
- 📁 Pre-trained model loading for fast inference
- 🖥️ Lightweight and easy to deploy

---

## 🛠️ Tech Stack

- Python
- Streamlit
- Scikit-learn
- Pandas
- NumPy
- Joblib

---

## 📂 Project Structure

```
HeartDiseaseRiskIntelligence/
│
├── app.py                 # Streamlit application
├── KNN_heart.pkl          # Trained KNN model
├── scaler.pkl            # Feature scaler
├── columns.pkl           # Feature column order
├── heart.csv             # Dataset
├── Heart.ipynb           # Model training notebook
├── requirements.txt      # Project dependencies
└── README.md
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/DanishKolhar/HeartDiseaseRiskIntelligence.git
cd HeartDiseaseRiskIntelligence
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the application

```bash
streamlit run app.py
```

---

## 📊 Input Parameters

The model predicts heart disease risk using parameters such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- ST Depression (Oldpeak)
- Slope of Peak Exercise ST Segment
- Number of Major Vessels
- Thalassemia

---

## 🤖 Machine Learning

- **Algorithm:** K-Nearest Neighbors (KNN)
- **Preprocessing:** StandardScaler
- **Framework:** Scikit-learn

---

## 📈 Future Enhancements

- Probability score with confidence level
- Feature importance visualization
- Model comparison (Random Forest, XGBoost, SVM)
- Explainable AI using SHAP
- User authentication and prediction history
- Cloud deployment with Docker

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Mohammed Danish Kolhar**

GitHub: https://github.com/DanishKolhar