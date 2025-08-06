# 📊 Salary Insights Dashboard – ISSP25 Project

> A visual analytics dashboard for salary prediction and interpretability using explainable AI.

---

## 📁 Project Description

This project was developed for the course **Artificial Intelligence and Human-Machine Interaction (ISSP25)**. It combines **interactive visualizations**, **machine learning predictions**, and **model explainability** to support users in understanding cybersecurity salary data.

The dashboard helps:
- **HR analysts** explore salary trends by role and remote level
- **Job seekers** compare job titles and interpret salary predictions

---

## 🚀 Features

- 📌 Interactive dashboard built with **Dash by Plotly**
- 📉 Salary distribution histograms by job title
- 🧠 SHAP-based feature importance explanation
- 📈 Remote work vs salary scatter plot
- ✅ Cleaned and encoded dataset ready for machine learning

---

## 📦 Tech Stack

- Python 3.11
- Dash (`dash`, `plotly`)
- Machine Learning (`scikit-learn`)
- Explainability (`shap`)
- Data handling (`pandas`, `numpy`)

---

## 📂 Folder Structure

project/
├── app.py # Dash app code
├── cleaned_model.ipynb # Notebook with modeling and SHAP
├── salaries.csv # Raw dataset
├── requirements.txt # Python dependencies
├── README.md # This file
└── assets/
├── shap_summary_plot.png # SHAP summary image
└── dashboard_example.png # Optional UI screenshot

---

## 📸 Screenshots

<img width="952" height="450" alt="newplot" src="https://github.com/user-attachments/assets/7062c532-ff0b-4ab9-8843-34c859349732" />


### 🔹 Salary Dashboard

<img width="952" height="450" alt="newplot (1)" src="https://github.com/user-attachments/assets/41902344-f525-449a-ba3d-08f21c15a3f1" />


### 🔹 SHAP Feature Importance

![SHAP](assets/shap_summary_plot.png)

---

## 📈 Model Evaluation

| Metric | Value         |
|--------|---------------|
| MAE    | ~$36,000      |
| RMSE   | ~$46,000      |
| R²     | ~0.32         |

Model used: `RandomForestRegressor` with one-hot encoding and IQR-based outlier filtering.

---

## 💡 SHAP Explainability

We used **SHAP (TreeExplainer)** to:
- Generate a global **summary plot** of feature importance
- Visualize **force plots** for individual prediction logic
- Help users interpret *why* the model predicts certain salaries

---

## 🧠 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/salary-dashboard.git
   cd salary-dashboard
2. Install dependencies:
pip install -r requirements.txt

3. Launch the Dash app:
python app.py

4. Open your browser to: http://127.0.0.1:8050

##   🎓 Course Notes
**📚  Built as part of Artificial Intelligence and Human-Machine Interaction (ISSP25)**
**📊  Emphasizes explainable AI, visual analytics, and user-centered interaction**
**🧠  Uses SHAP to interpret predictions and support transparency**

## 👤 Author
**Muhammad Ikram Hafeez & Rehan Khaliq**
University of Prizren, Kosovo
International Summer School 2025
Instructor: Ilir Jusufi

## 📜 License
This project is for educational purposes only.
