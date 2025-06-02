# 💓 Heart Disease Prediction using Random Forest

A machine learning classification project that predicts the presence of heart disease based on real-world medical data.  
This project uses a **Random Forest Classifier** to build a robust and accurate prediction model.

---

## 📌 Objective

The goal of this project is to analyze medical data and predict whether a patient is likely to have heart disease.  
Early prediction can lead to better diagnosis and timely treatment.

---

## 🧰 Tools & Technologies Used

- **Python**
- **Pandas** for data manipulation
- **Scikit-learn** for building and evaluating ML models
- **Matplotlib** & **Seaborn** for data visualization
- **Jupyter Notebook** as the development environment

---

## 📊 Dataset

The dataset used is the **UCI Heart Disease Dataset**, which contains 14 key medical attributes such as:

- Age  
- Resting Blood Pressure  
- Serum Cholesterol  
- Chest Pain Type  
- Maximum Heart Rate Achieved  
- Fasting Blood Sugar  
- And others...

> Dataset source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/45/heart+disease)

---

## 🧪 Project Workflow

1. **Data Loading & Exploration**  
   Understand the structure, types, and distribution of the dataset.

2. **Data Preprocessing**  
   - Handling missing values  
   - Converting categorical features  
   - Normalization (if needed)

3. **Feature Selection**  
   Analyze feature importance using the model.

4. **Model Building**  
   Trained a **Random Forest Classifier** using scikit-learn.

5. **Model Evaluation**  
   - Accuracy Score  
   - Confusion Matrix  
   - Precision, Recall, F1-score  
   - Feature Importance Plot

---

## ✅ Results

The Random Forest model achieved high performance on the test set, proving effective in identifying patients with heart disease.  
Key features contributing to prediction include **age**, **cholesterol**, and **maximum heart rate achieved**.

---

## 📈 Visualizations

- Heatmap of feature correlations  
- Confusion matrix visualization  
- Feature importance bar plot

---

## 📦 How to Run the Project

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Eng-yousef-khalaf/heart-disease-prediction-project.git
2. **Navigate to the project directory and open the Jupyter Noteboo:**
   ```bash
   cd heart-disease-prediction
   jupyter notebook
3. **Run the notebook:**
  ```bash
Open heart_disease_prediction.ipynb and run all cells.

