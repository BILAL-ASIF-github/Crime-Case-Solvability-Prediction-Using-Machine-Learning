# 🕵️‍♂️ Crime Case Solvability Prediction Using Machine Learning 📊

A complete **Machine Learning pipeline** applied to a massive real-world dataset to predict whether a crime case will be solved based on historical data!

---

## 🧠 Overview

Crime solving is a complex process, and not all cases are solved successfully. **Crime Case Solvability Prediction** is a comprehensive machine learning project designed to uncover the hidden patterns that influence the outcome of criminal investigations. 

Addressing the core problem—*"Can we predict whether a crime case will be solved or not based on historical crime data?"*—this project treats case solvability as a **binary classification problem**. Handling a massive dataset of around **600,000 records**, this initiative goes beyond a simple lab task, covering the full industry-standard ML workflow from data cleaning to model evaluation.

---

## 🚀 Project Objectives

* ✅ **Analyze real-world data** — Explore and understand a massive historical crime dataset.
* ✅ **Data Preprocessing** — Clean data, handle missing values, encode categorical features, and select relevant variables.
* ✅ **Predictive Modeling** — Apply and compare suitable machine learning algorithms.
* ✅ **Discover Insights** — Understand the key factors and patterns that affect crime case solvability.

---

## 📂 Dataset & Features

The dataset consists of historical crime records collected over multiple years, where each row represents a single crime case. 

**Key Features Analyzed:**
* Victim Sex & Race
* Perpetrator Sex
* Weapon Type
* Relationship between victim and perpetrator
* City and State
* Year and Month of crime

**🎯 Target Variable:**
* `1` 👉 **Case Solved**
* `0` 👉 **Case Not Solved**

---

## 🤖 Machine Learning Models

Due to the nature of the data, two primary classification algorithms were selected and compared:

### 1️⃣ Logistic Regression
* **Why it was chosen:** It is simple, fast to train on large datasets, and produces probability-based outputs. It provides stable, interpretable results that make it easy to explain how different features influence solvability.

### 2️⃣ Random Forest Classifier (🏆 Best Performer)
* **Why it was chosen:** As an ensemble learning algorithm, it handles non-linear relationships and complex categorical data exceptionally well. By using multiple decision trees, it reduces overfitting and achieved a **better accuracy and ROC-AUC score** overall.

> **Why other algorithms were excluded:**
> * **Linear Regression:** Designed for continuous output, not classification.
> * **KNN & SVM:** Computationally expensive, slow, and highly inefficient for a dataset of 600,000 records.
> * **Neural Networks:** Added unnecessary complexity and lacked the easy interpretability needed for this specific problem.

---

## 📈 Evaluation & Results

The models were rigorously evaluated using standard classification metrics:
* **Accuracy**
* **Precision & Recall**
* **F1 Score**
* **ROC-AUC Curve**

**Conclusion:** Logistic Regression proved highly useful for data interpretation and baseline understanding, while the **Random Forest Classifier** provided the strongest predictive performance due to its ability to capture complex, non-linear patterns.

---

## 🌍 Real-Life Applications

This data-driven approach has powerful implications for the real world:
* 🚓 **Law Enforcement:** Helps identify traditionally difficult cases early on.
* 🕵️ **Investigation Planning:** Supports resource allocation and crime analysis.
* 🏛️ **Policy Making:** Assists leaders in improving crime control and prevention strategies.
* 📚 **Research:** Valuable for academic studies in criminal justice and data science.

---

## 🧩 Technologies Used

* 🐍 **Python** – Core programming language
* 📓 **Jupyter Notebook** – Interactive development environment
* 🔢 **NumPy & Pandas** – Data manipulation, cleaning, and preprocessing
* 🤖 **Scikit-learn** – Machine learning model development and evaluation
* 📊 **Matplotlib & Seaborn** – Data visualization and exploratory data analysis

---

## ⚙️ Installation & Running the Project

1. **Clone this repository**
   ```bash
   git clone [https://github.com/BILAL-ASIF-github/crime-solvability-prediction.git](https://github.com/BILAL-ASIF-github/crime-solvability-prediction.git)
   cd crime-solvability-prediction
   ```

2. **Install required dependencies**
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn jupyter
   ```

3. **Launch the Jupyter Notebook**
   ```bash
   jupyter notebook
   ```
   Open the main notebook file to explore the data, run the preprocessing steps, and train the models! 🎉

---

## 🧾 License

This project is licensed under the **MIT License** — free to use, modify, and distribute with credit. See the `LICENSE` file for details.

---

## 👨‍💻 Author

**Bilal Asif**

* 📧 badigitalmarketingservices@gmail.com
* 💼 [www.linkedin.com/in/billallasif](https://www.linkedin.com/in/billallasif)
* Portfolio : [https://billallasif.vercel.app/](https://billallasif.vercel.app/)

⭐ If you like this project, consider giving it a star on GitHub!
