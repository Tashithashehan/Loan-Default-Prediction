.
# Loan Default Prediction 🏦

This project is a Machine Learning application that predicts whether a customer will default on their loan payments. It uses financial data to help banks identify high-risk borrowers.

### 📍 Project Overview

In the banking industry, deciding who to give a loan to is a major challenge. This project follows a full data science pipeline:

1. **Data Cleaning:** Removing unnecessary columns.
2. **Preprocessing:** Scaling numbers and encoding categories.
3. **Modeling:** Training multiple algorithms to find the best one.
4. **Interface:** Creating a simple UI for real-world testing.

---

### 📂 Dataset Details

The dataset used is the **Loan Default Prediction** dataset from Kaggle.

* **Bank Balance:** The amount currently in the account.
* **Annual Salary:** How much the user earns per year.
* **Employed:** Whether the user has a job () or is a student/unemployed ().
* **Defaulted? (Target):**  if they failed to pay,  if they paid on time.

---

### 🚀 Results

We tested three different models. Here is how they performed:

| Model | Accuracy |
| --- | --- |
| Linear Regression | 96.6% |
| Decision Tree | 95.3% |
| **Random Forest** | **97.0%** 🏆 |

**Conclusion:** The Random Forest model is the most reliable for this specific problem.

---

### 💻 How to Run the App

I have included a **Gradio** interface. To run it:

1. Open the `.ipynb` file in Google Colab.
2. Ensure `Default_Fin.csv` is uploaded.
3. Run the "Gradio" cell to see the interactive sliders and buttons!

---

### 🛠️ Built With

* **Python** 🐍
* **Pandas** (Data manipulation)
* **Scikit-Learn** (Machine Learning)
* **Gradio/Streamlit** (User Interface)
* **Joblib** (Saving the model)

.
