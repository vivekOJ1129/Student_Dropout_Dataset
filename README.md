# 🎓 Student Dropout Risk Analysis

A data analytics and machine learning project to predict student dropout risk based on academic performance, demographics, and behavior.

This project was created as part of the **Gigaversity Data Analyst Internship Challenge**.

---

## 📌 Objective

To analyze and predict school dropout risk among students using statistical techniques and machine learning models. The goal is to help educational institutions identify at-risk students and provide early interventions.

---

## 🧩 Problem Statement

> Predict the dropout risk (`Low`, `High`) of a student based on features like age, gender, GPA, failures, absences, lunch type, test prep status, and parental education level.

---

## 🗃️ Dataset

- File: `Student_Dropout_Dataset.csv`
- Cleaned and preprocessed
- Categorical labels preserved for Tableau
- Binary dropout risk mapped as:
  - `0 → Low`
  - `1 → High`  
  (Remapped to text labels for visualization)

---

## 🧠 Features Used

| Feature               | Description                              |
|-----------------------|------------------------------------------|
| Gender                | Male / Female                            |
| Age                   | Age of student                           |
| Failures              | Number of past class failures            |
| Absences              | Total number of absences                 |
| Test Preparation      | Completed or not                         |
| Lunch Type            | Standard or Free/Reduced                 |
| Parental Education    | Highest level of parental education      |
| School Type           | Urban / Rural                            |
| Avg Score             | Mean of Math, Reading, Writing scores    |
| Dropout Risk          | Target variable (Low / High)             |

---

## ⚙️ Machine Learning Models

Two models were trained and evaluated:

### 🔸 Logistic Regression
- Baseline model
- Simple and interpretable
- Accuracy reported on validation set

### 🔸 Random Forest Classifier
- Ensemble model for better performance
- Identifies feature importances
- Used for final prediction insights

Notebooks:
- `logistic_regression.ipynb`
- `random_forest.ipynb`

---

## 📊 Tableau Dashboard

A comprehensive dashboard was built using Tableau to:

- Visualize dropout risk distribution
- Analyze GPA, absences, failures
- Detect patterns by gender, parental education
- Enable filtering by demographics

Data source: `Tableau_Ready_Dropout_Dataset_LabeledBinary.csv`

---

## 📂 Folder Structure

```
student_dropout_dataset/
├── logistic_regression.ipynb
├── random_forest.ipynb
├── Tableau_Ready_Dropout_Dataset_LabeledBinary.csv
├── README.md
```

---

## 🧪 Requirements

To run the Python notebooks locally:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 📫 Author

**Vivekanand Ojha**  
📧 Email: vivekanandojha09@gmail.com  
🔗 GitHub: [@vivekOJ1129](https://github.com/vivekOJ1129)
🔗 Linkedin: [Vivekanand Ojha](https://www.linkedin.com/in/vivekanand-ojha-485462289/)

---

## 📄 License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).
