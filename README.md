# ❤️ Heart Disease Prediction

## 📌 Overview

This project is a **Machine Learning-based prediction system** that estimates the likelihood of a person having heart disease based on various medical attributes. The goal is to assist in **early diagnosis**, helping healthcare professionals and individuals take preventive measures.

The model uses **supervised learning algorithms** and is trained on a publicly available **Heart Disease dataset** to classify patients as **at risk** or **not at risk**.

---

## 🎯 Objectives

* Perform **data preprocessing** and **feature analysis**
* Train and evaluate **classification models**
* Compare model accuracy and select the best-performing one
* Provide a ready-to-use **prediction script or API**

---

## 📂 Dataset

* **Source**: [UCI Machine Learning Repository – Heart Disease Dataset](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
* **Features**:

  * `age` → Age of the patient
  * `sex` → Gender (1 = male, 0 = female)
  * `cp` → Chest pain type (0–3)
  * `trestbps` → Resting blood pressure (mm Hg)
  * `chol` → Serum cholesterol (mg/dl)
  * `fbs` → Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
  * `restecg` → Resting electrocardiographic results (0–2)
  * `thalach` → Maximum heart rate achieved
  * `exang` → Exercise-induced angina (1 = yes; 0 = no)
  * `oldpeak` → ST depression induced by exercise
  * `slope` → Slope of the peak exercise ST segment (0–2)
  * `ca` → Number of major vessels (0–3) colored by fluoroscopy
  * `thal` → Thalassemia (0–3)
* **Target**: `target` — 1 = heart disease present, 0 = heart disease absent

---

## 🛠 Tech Stack

* **Programming Language**: Python 🐍
* **Libraries**:

  * `pandas`, `numpy` → Data manipulation
  * `matplotlib`, `seaborn` → Data visualization
  * `scikit-learn` → Model building & evaluation
  * `joblib` → Model saving/loading

---

## 🔍 Workflow

1. **Data Loading & Cleaning**

   * Load dataset from CSV
   * Handle missing values
   * Encode categorical variables
2. **Exploratory Data Analysis (EDA)**

   * Visualize feature distributions
   * Check correlations with target variable
3. **Feature Scaling**

   * Normalize/standardize numeric features
4. **Model Training**

   * Logistic Regression
   * Random Forest Classifier
   * K-Nearest Neighbors (KNN)
5. **Model Evaluation**

   * Accuracy, Precision, Recall, F1-Score, ROC-AUC
6. **Prediction**

   * Predict heart disease for new patient data

---

## 📊 Results

* Best-performing model: **Random Forest Classifier**
* Achieved accuracy: **\~85–90%** (depending on parameters)
* High recall score → effective in identifying at-risk patients

---

## 📦 Installation & Usage

```bash
# Clone the repository
git clone https://github.com/your-username/heart_disease_prediction.git

# Navigate to the project folder
cd heart_disease_prediction

# Install dependencies
pip install -r requirements.txt

# Run the script
python heart_disease_prediction.py
```

**Example Output:**

```
Prediction: Patient is likely to have heart disease.
```

---

## 📅 Future Improvements

* Implement **hyperparameter tuning** for better performance
* Deploy as a **Streamlit web app** for user-friendly predictions
* Add support for **real-time medical data input**

---

## 🤝 Contributing

Contributions are welcome!

* Fork the repository
* Create a feature branch
* Commit your changes
* Open a Pull Request

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---
