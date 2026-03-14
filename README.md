# ❤️ Heart Disease Prediction (Kaggle Competition)

Machine learning project developed for the Kaggle competition:

**Predicting Heart Disease – Playground Series S6E2**

The goal of this competition was to predict whether a patient has heart disease based on medical attributes such as age, cholesterol level, blood pressure, ECG results, and maximum heart rate.

---

# 📊 Dataset

The dataset contains approximately **630,000 records** and **13 medical features** including:

- Age
- Sex
- Chest Pain Type
- Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- ECG Results
- Maximum Heart Rate
- Exercise Angina
- ST Depression
- Slope of ST
- Number of Vessels
- Thallium Test

Target Variable:
- **Heart Disease (0 = Absence, 1 = Presence)**

Evaluation Metric:
- **ROC-AUC**

---

# 🧠 Approach

The pipeline includes:

### Data Processing
- Feature cleaning
- Target encoding
- Dataset merging and experimentation

### Cross Validation
- **Stratified K-Fold (5 folds)** to avoid class imbalance issues

### Models Used
- LightGBM
- XGBoost

### Ensemble
Final prediction generated using **LightGBM + XGBoost blended ensemble**.

---

# 📈 Results

| Model | CV ROC-AUC |
|------|-------------|
| LightGBM | 0.9547 |
| XGBoost | 0.9548 |
| Ensemble | **0.95495**|

Kaggle Public Leaderboard Score:

**0.95299**

Competition Rank:

**Top ~40% among 4000+ participants**

---

# 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Scikit-Learn
- LightGBM
- XGBoost
- Kaggle Notebooks

---

# 📂 Project Structure

- notebooks/
   heart_disease_kaggle.ipynb

## Dataset

The dataset used in this project comes from the Kaggle competition:

Predicting Heart Disease – Playground Series S6E2

Due to GitHub file size limitations, the dataset is not included in this repository.

You can download it from the Kaggle competition page:

https://www.kaggle.com/competitions/playground-series-s6e2/data


---

# 🚀 How to Run

### Install dependencies
-  pip install -r requirements.txt

---

# 🧑‍💻 Author

Rahul Singh  
Computer Science Student | Data Science Enthusiast

Kaggle Profile: https://kaggle.com/rahulsinghdspy
LinkedIn: https://linkedin.com/in/pyrahul
