# 🪀 Heart Disease Risk Prediction with Explainable AI

This project predicts the risk of heart disease using machine learning — with a focus on **explainability** and **clinical trust**. Built using the UCI Heart Disease dataset, the model outputs not only a risk score, but also **why** that score was assigned.

---

## 📌 Features

- Logistic Regression & XGBoost models
- End-to-end pipeline in Google Colab
- SHAP explainability for global and individual predictions
- ROC Curve, Confusion Matrix, and Feature Importance Visuals
- Ready for extension into Streamlit or Gradio app

---

## 📊 Model Performance (XGBoost)

| Metric    | Value   |
| --------- | ------- |
| Accuracy  | ~75.5% |
| Precision | ~76.6% |
| Recall    | ~80.4% |
| F1 Score  | ~78.5% |
| AUC-ROC   | ~81.4% |

---

## 🧠 SHAP Explainability

**Why did the model predict heart disease for this patient?**

- `trestbps` and `oldpeak` lowered the prediction.
- `age` and `chol` pushed it upward.
- The model’s decision is now *clinically interpretable*.

---

## 📁 Project Structure

```
heart-disease-risk-predictor/
├── data/                    ← Raw and cleaned CSV files
├── notebooks/               ← Colab notebooks for EDA, training, SHAP
├── plots/                   ← Saved visuals: ROC, Confusion, SHAP
├── models/                  ← Optional: trained model exports
├── app/                     ← Optional: Streamlit or Gradio frontend
├── README.md
└── requirements.txt
```

---

## 🧢 Dataset

- Source: [Kaggle – UCI Heart Disease Data](https://www.kaggle.com/datasets/redwankarimsony/heart-disease-data)
- Preprocessing: null imputation, scaling, encoding

---

## 🚀 Setup Instructions

```bash
# Clone repo
git clone https://github.com/yourusername/heart-disease-risk-predictor.git
cd heart-disease-risk-predictor

# Install dependencies
pip install -r requirements.txt

# Or open notebook directly in Colab
```

---

## ✅ Future Work

- Hyperparameter tuning (Optuna, GridSearchCV)
- Time-series modeling with wearable data
- Real-world deployment with MIMIC-IV or ECG signals
- Streamlit or Gradio web demo

---

## 👨‍⚕️ Author

**Sarath Lella**ML & Data Science | Transitioning to AI in Healthcare🔗 [LinkedIn](https://www.linkedin.com/in/sarathlella) | 🧠 [GitHub](https://github.com/sarathlella)

---

## 📌 License

MIT License – feel free to use, cite, or build upon this project.
