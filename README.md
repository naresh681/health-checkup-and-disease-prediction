# 🩺 HealthCheck: Lifestyle & Disease Correlation

## 📘 Overview
**HealthCheck** is a machine learning project that explores how lifestyle factors — such as BMI, exercise, smoking, alcohol, and stress — influence disease occurrence.  
The project uses a **Random Forest Classifier** to predict diseases based on lifestyle data and provides visual insights through statistical plots.

---

## 🎯 Objectives
- Analyze lifestyle habits and their correlation with diseases.  
- Identify key factors that contribute to health risks.  
- Build and evaluate a predictive model using **Random Forest**.  
- Visualize patterns using **Seaborn** and **Matplotlib**.

---

## 🧩 Dataset Description
The dataset used is **`healthcheck_dataset.csv`** and contains the following features:

| Feature | Description |
|----------|--------------|
| Gender | Male / Female |
| Age | Age of the individual |
| BMI | Body Mass Index |
| Exercise_Hours | Average daily exercise (hours) |
| Smoking | Smoking habit (Yes/No) |
| Alcohol | Alcohol consumption (Yes/No) |
| Stress_Level | Low / Medium / High |
| Disease | Target variable (type of disease) |

---

## ⚙️ Tech Stack
- **Language:** Python  
- **Libraries:**  
  - `pandas`, `numpy` – Data manipulation  
  - `seaborn`, `matplotlib` – Data visualization  
  - `scikit-learn` – Model training and evaluation  

---

## 🔬 Methodology
1. **Data Loading** – Load and preview dataset.  
2. **Exploratory Data Analysis (EDA)** – Visualize disease distribution, BMI, and exercise correlations.  
3. **Encoding** – Convert categorical variables into numeric form using `LabelEncoder`.  
4. **Model Training** – Train a **Random Forest Classifier** on the processed data.  
5. **Evaluation Metrics** –  
   - Classification Report  
   - Confusion Matrix  
   - ROC Curve (Multi-class)  
   - Log Loss  
6. **Feature Importance** – Identify key contributing factors to disease prediction.

---

## 📊 Visualizations
- 📈 Disease distribution plot  
- 🧍‍♂️ BMI vs Disease (Box Plot)  
- 💪 Exercise Hours vs Disease (Bar Plot)  
- 🧩 Confusion Matrix Heatmap  
- ❤️ ROC Curve (for each class)  
- 📉 Log Loss Curve  
- 🌿 Feature Importance Bar Chart  

---

## 🧠 Model Evaluation
- **Algorithm Used:** Random Forest Classifier  
- **Metrics:**  
  - Accuracy  
  - Precision  
  - Recall  
  - F1-Score  
  - ROC-AUC per class  
  - Log Loss value  

---

## 🔍 Key Insights
- Diseases show clear patterns linked to **BMI**, **stress**, and **exercise**.  
- High stress levels and low exercise hours are often correlated with negative health outcomes.  
- **Feature Importance** analysis reveals BMI and Stress_Level as major influencing features.

---

## 🚀 How to Run

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/HealthCheck-Lifestyle-Disease.git
cd HealthCheck-Lifestyle-Disease
