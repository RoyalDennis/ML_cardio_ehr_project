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

## 📺 Project Presentation (YouTube)

🎥 [Watch Presentation on YouTube](https://www.youtube.com/watch?v=your-link-here)

---

## 📊 Presentation Slides
 https://docs.google.com/presentation/d/1O8vWTKW9kpetyQjNV9n73huqw7oToC1GgWNoxRUdAqI/edit?usp=sharing

---

## 💻 How to Run This Project

### 🔧 Requirements

Install the required Python libraries:

```bash
pip install -r requirements.txt
