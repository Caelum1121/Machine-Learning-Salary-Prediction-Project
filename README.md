# Machine Learning Salary Prediction Project

## 📌 Problem Statement
This project focuses on building a machine learning model to **analyze and predict employee salaries** based on professional and organizational attributes.

The primary objectives are:
- To identify the key factors that influence salary levels
- To evaluate how accurately salaries can be predicted using supervised learning models
- To translate machine learning outcomes into actionable business insights for management decision-making

---

## 📊 Dataset
- **Dataset Name:** In the Know Company Salary Data (2020–2025)
- **Source:** Course-provided dataset for *Foundations of Artificial Intelligence*
- **File:** `FoAI_A2_data.csv`
- **Format:** CSV

### Features
- Experience Level (Entry, Mid, Senior, Executive)
- Employment Type
- Job Role
- Company Size
- Company Location
- Salary (Target Variable)

### Data Preparation
- Removed invalid and missing values
- Encoded categorical variables
- Conducted Exploratory Data Analysis (EDA) to examine distributions, correlations, and trends

---

## 🤖 Methodology
1. Exploratory Data Analysis (EDA)
2. Data preprocessing and feature engineering
3. Training supervised learning models for salary prediction
4. Model evaluation and comparison using performance metrics
5. Interpretation of results from a business perspective

### Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Google Colab

---

## 📈 Results
- **Experience level** was the most significant factor affecting salary outcomes
  - Salary increased by approximately **200–300%** from entry-level to executive-level positions
- Machine learning models achieved **strong predictive performance**, meeting academic benchmarks (R² ≥ 0.70)
- Company size and job role also showed notable influence on salary variation
- The final model demonstrated a balance between prediction accuracy and interpretability

---

## 💡 Business Insights
- Enables data-driven compensation planning
- Helps management understand structural salary differences across roles and experience levels
- Demonstrates the practical application of machine learning in organizational decision-making

---

## 🚀 Project Highlights
- End-to-end machine learning workflow: EDA → preprocessing → modeling → evaluation
- Real-world dataset with clear business relevance
- Implemented using Python in Google Colab for reproducibility and collaboration

---

## 📂 Repository Structure
├── FoAI_A2_data.csv <br> 
├── salary_prediction.ipynb <br>
└── README.md


---

## 📎 How to Run
1. Open `salary_prediction.ipynb` in Google Colab
2. Upload the dataset file when prompted
3. Run all cells sequentially to reproduce results
