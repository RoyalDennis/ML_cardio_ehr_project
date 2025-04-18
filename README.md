# 🫀 Cardiovascular Disease Prediction Using Machine Learning & Real-Time EHR Integration

## 📌 Project Overview

Cardiovascular disease (CVD) is the leading cause of death globally, accounting for approximately 17.9 million deaths annually, which represents nearly 32% of all global deaths. This project focuses on enhancing early detection, diagnosis, and prognosis of CVD by integrating machine learning (ML) models with real-time Electronic Health Record (EHR) systems. By leveraging patient data such as vital signs, lab results, and demographics, the system aims to assist healthcare professionals with accurate, timely, and data-driven clinical decisions.

## 🎯 Research Goal

The primary goal of this research is to build predictive machine learning models and integrate them with real-time EHR systems to improve the accuracy and timeliness of CVD diagnosis and prognosis. This will support clinicians in identifying high-risk patients early and enabling more effective interventions.

---

## 🧠 Research Problem

Although medical technology continues to advance, early detection of cardiovascular disease remains a significant challenge due to the complexity and volume of patient data. Traditional diagnostic methods often fail to identify at-risk individuals early, leading to delayed interventions and increased mortality.

---

## 🧪 Machine Learning Models Used

- **Logistic Regression**
- **Random Forest Classifier**
- **Support Vector Machine (Linear SVM)**
- **Neural Network (Multi-Layer Perceptron with GridSearchCV)**

---

## 📂 Datasets Used

| Dataset | Description | Source |
|--------|-------------|--------|
| **Framingham Heart Study** | Longitudinal study on CVD risk factors | [Framingham Dataset](https://www.framinghamheartstudy.org/) |
| **MIMIC-III** | ICU patient data (vitals, labs, notes) | [MIMIC-III Dataset](https://mimic.mit.edu/) |
| **Cleveland Heart Disease Dataset** | Features for heart disease diagnosis | [UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease) |

> **Note**: Only publicly available datasets were used in compliance with privacy and research ethics standards.

---

## 🧠 Project Architecture

The workflow includes:
1. Data cleaning and preprocessing
2. Feature engineering (e.g., combining age, cholesterol, BP)
3. Model training and evaluation
4. Hyperparameter tuning (for Neural Network)
5. Real-time prediction simulation using sample EHR data

---

## 📊 Performance Metrics

Each model was evaluated using the following metrics:

- **Accuracy**: Measures the overall correctness of predictions.
- **Precision**: Indicates the proportion of true positive predictions among all positive predictions.
- **Recall**: Reflects the model's ability to correctly identify all actual positive cases.
- **AUC-ROC**: Measures the model’s ability to distinguish between classes at different thresholds.

### 🔍 Results Summary

| Model               | Accuracy | Precision | Recall | AUC-ROC |
|--------------------|----------|-----------|--------|---------|
| Logistic Regression | 99.21%   | 99.52%    | 99.68% | 0.8800  |
| Random Forest       | 99.00%   | 99.51%    | 99.46% | 0.8789  |
| Linear SVM          | 98.20%   | 99.08%    | 99.08% | 0.7717  |
| Neural Network      | 98.47%   | 98.56%    | 99.89% | 0.6442  |


---

✅ Conclusion

This project demonstrates the potential of integrating machine learning with real-time Electronic Health Record (EHR) systems for the early diagnosis and prognosis of cardiovascular diseases (CVD). Through the use of diverse datasets and a combination of classification models, including logistic regression, random forest, support vector machines, and neural networks, we achieved high accuracy and precision, helping to identify at-risk patients more effectively. The results suggest that machine learning models, when properly tuned and validated, can significantly enhance clinical decision-making in cardiovascular care.

---

🔮 Future Work

Future development of this research will focus on increasing the interpretability of machine learning models using Explainable AI (XAI) techniques such as SHAP (SHapley Additive Explanations) and LIME (Local Interpretable Model-Agnostic Explanations). These tools can help clinicians understand why a model makes certain predictions, thereby building trust in AI-supported diagnostics. Additionally, expanded feature engineering from clinical notes using NLP, and model retraining with larger, multicenter datasets will be explored to enhance model generalization and real-world applicability. Further clinical validation and deployment in real-time healthcare environments will also be part of the next phase.

---

🛡️ Ethical Considerations & HIPAA Compliance

This research adheres to ethical principles in the use of medical data by relying solely on publicly available and de-identified datasets (Framingham, MIMIC-III, Cleveland Heart Disease). No personally identifiable information (PII) was accessed or processed during this study. The MIMIC-III dataset, in particular, is HIPAA-compliant and provided under strict data use agreements. All modeling and data handling followed best practices to ensure privacy, security, and fairness. In real-world deployment, future systems must ensure full HIPAA compliance, including secure data storage, access control, anonymization, and regular audits, to protect patient privacy and maintain ethical standards in AI-assisted healthcare solutions.

---

## 📺 Project Presentation (YouTube)

🎥 [Watch Presentation on YouTube](https://youtu.be/JvQ2K3Twhzc)

---

## 📊 Presentation Slides
 https://docs.google.com/presentation/d/1O8vWTKW9kpetyQjNV9n73huqw7oToC1GgWNoxRUdAqI/edit?usp=sharing

---

## 💻 How to Run This Project

### 🔧 Requirements

Install the required Python libraries:

```bash
pip install -r requirements.txt
