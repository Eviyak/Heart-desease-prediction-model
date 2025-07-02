# 🫀 Heart Disease Prediction Model

## 📄 Description
A machine learning project that uses logistic regression to predict the presence of heart disease based on clinical data. Built and trained using a dataset of 303 patient records

## 📁 Dataset (https://disk.yandex.ru/d/kO_oa4uEA9CHqw)
This model was trained on a dataset containing 303 patient records with 14 features each. The target column `target` indicates the presence (`1`) or absence (`0`) of heart disease.

**Features:**
- `age` – Age of the patient  
- `sex` – Sex (1 = male; 0 = female)  
- `cp` – Chest pain type (0–3)  
- `trestbps` – Resting blood pressure (mm Hg)  
- `chol` – Serum cholesterol (mg/dl)  
- `fbs` – Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)  
- `restecg` – Resting electrocardiographic results (0–2)  
- `thalach` – Maximum heart rate achieved  
- `exang` – Exercise-induced angina (1 = yes; 0 = no)  
- `oldpeak` – ST depression induced by exercise  
- `slope` – Slope of the peak exercise ST segment  
- `ca` – Number of major vessels (0–3) colored by fluoroscopy  
- `thal` – Thalassemia (1 = normal; 2 = fixed defect; 3 = reversible defect)  
- `target` – 1: disease present, 0: no disease

## 🧠 Model
- Algorithm: **Logistic Regression**
- Data preprocessing:
  - Feature scaling
  - Encoding categorical values
- Evaluation:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion Matrix

## 📌 Notes
- This project is for educational purposes and not intended for real-world medical diagnosis.
