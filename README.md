# Credit Risk Prediction App

🔗 **Live Demo:** https://credit-risk-prediction-monish.streamlit.app/ 
📦 **GitHub Repository:** https://github.com/Monish-D609/Credit-Risk-Prediction

An end-to-end **machine learning powered web application** that predicts whether a credit applicant is **Low Risk (Good)** or **High Risk (Bad)** based on financial and personal attributes.

---

## 🚀 Features

- Real-time credit risk prediction
- User-friendly web interface built with Streamlit
- Handles categorical encoding and numeric inputs
- Deployed on Streamlit Cloud
- End-to-end ML workflow (training → saving → deployment)

---

## 🧠 Machine Learning Details

- **Model:** ExtraTreesClassifier
- **Problem Type:** Binary Classification
- **Target Variable:**
  - `1` → Good Credit Risk (Lower Risk)
  - `0` → Bad Credit Risk (Higher Risk)

### Input Features
- Age
- Sex
- Job
- Housing
- Saving accounts
- Checking account
- Credit amount
- Duration (months)

Categorical features are encoded using pre-trained encoders to ensure consistency between training and inference.

---

## 🛠 Tech Stack

- **Language:** Python
- **ML Library:** scikit-learn
- **Web Framework:** Streamlit
- **Data Handling:** pandas, numpy
- **Model Persistence:** joblib
- **Deployment:** Streamlit Cloud

---

## 📁 Project Structure

Credit-Risk-Prediction/
│
├── app.py # Streamlit application
├── extra_trees_credit_model.pkl
├── Sex_encoder.pkl
├── Housing_encoder.pkl
├── Saving accounts_encoder.pkl
├── Checking account_encoder.pkl
├── requirements.txt
├── README.md
└── .gitignore


## ▶️ How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/Monish-D609/Credit-Risk-Prediction.git
   cd Credit-Risk-Prediction


Install dependencies:
pip install -r requirements.txt


Run the app: 
streamlit run app.py


📌 What I Learned
Building and training tree-based ML models

Handling categorical data safely at inference

Debugging real-world ML deployment issues

Using Git and GitHub for version control

Deploying ML applications to the cloud

📈 Future Improvements
Add prediction probability (predict_proba)

Combine preprocessing and model into a single Pipeline

Improve UI with validation and tooltips

Add model performance metrics to the app

🙌 Acknowledgements
This project was built as a hands-on learning exercise to understand the full lifecycle of an ML application, from model training to real-world deployment.

📬 Contact
If you have feedback or suggestions, feel free to reach out or open an issue.
https://www.linkedin.com/in/monish-d-3414b031b/
[LinkedIn](https://www.linkedin.com/in/monish-d-3414b031b/)

