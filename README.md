# 🎓 UCI Student Performance Predictor

<p align="center">

**An end-to-end Machine Learning project for predicting student academic performance using the UCI Student Performance Dataset.**

<br>

<a href="https://github.com/Mahnoor-Kalsoom/UCI_Student_Performance_Predictor">
<img src="https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github" alt="GitHub Repository">
</a>
<img src="https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python" alt="Python">
<img src="https://img.shields.io/badge/Machine%20Learning-Scikit--learn-orange?style=for-the-badge" alt="Machine Learning">
<img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter" alt="Jupyter">

</p>

---

## 📌 Overview

**UCI Student Performance Predictor** is a Machine Learning project that analyzes student-related academic, demographic, and behavioral information to predict student performance.

The project demonstrates a complete Machine Learning workflow, including:

* 📊 Exploratory Data Analysis (EDA)
* 🧹 Data preprocessing
* 🔍 Feature analysis
* ⚙️ Feature engineering
* 🤖 Machine Learning model development
* 📈 Model evaluation
* 🔬 Model comparison
* 🎯 Performance prediction
* 📓 Jupyter Notebook-based experimentation

The project uses the **UCI Student Performance Dataset**, a well-known dataset containing information about students' academic performance, demographics, family background, study habits, and social behavior.

---

## 🎯 Project Objectives

The main objectives of this project are to:

1. Understand the factors associated with student academic performance.
2. Explore relationships between student characteristics and final grades.
3. Prepare real-world educational data for Machine Learning.
4. Train Machine Learning models for student performance prediction.
5. Evaluate and compare model performance.
6. Identify important features that contribute to prediction results.

---

## 📊 Dataset

This project uses the **UCI Student Performance Dataset**.

The dataset contains information related to:

* Student demographics
* Family background
* Parental education
* School-related information
* Study time
* Previous failures
* Absences
* Social activities
* Alcohol consumption
* Family and educational support
* Previous academic grades
* Final academic performance

### Target Variable

The primary academic outcome is the student's final grade:

**`G3` — Final Grade**

The final grade is measured on a scale from **0 to 20**.

---

## 🧠 Machine Learning Workflow

```text
                 UCI Student Dataset
                         │
                         ▼
                Data Collection
                         │
                         ▼
                 Data Exploration
                         │
                         ▼
              Data Preprocessing
                         │
                         ▼
              Feature Engineering
                         │
                         ▼
                Train/Test Split
                         │
                         ▼
               Model Development
                         │
                         ▼
                Model Evaluation
                         │
                         ▼
               Model Comparison
                         │
                         ▼
             Student Performance
                  Prediction
```

---

## 🔎 Exploratory Data Analysis

The exploratory analysis investigates relationships between student performance and different academic, demographic, and behavioral variables.

Examples of investigated factors include:

* Study time
* Previous failures
* Absences
* Parental education
* Family support
* School support
* Social activities
* Alcohol consumption
* Previous grades
* Student demographics

Visualizations are used to better understand distributions, correlations, and relationships within the dataset.

---

## 🧹 Data Preprocessing

The preprocessing stage prepares the dataset for Machine Learning.

Typical preprocessing operations include:

* Handling categorical variables
* Encoding categorical features
* Selecting relevant features
* Preparing numerical variables
* Splitting the data into training and testing sets
* Preparing the target variable

---

## 🤖 Machine Learning

The project experiments with Machine Learning approaches for predicting student performance.

Depending on the experiment, models can include algorithms such as:

* Linear Regression
* Decision Tree
* Random Forest
* Other Scikit-learn models

The models are evaluated using appropriate regression metrics.

### Evaluation Metrics

Common evaluation metrics include:

| Metric   | Description                  |
| -------- | ---------------------------- |
| **MAE**  | Mean Absolute Error          |
| **MSE**  | Mean Squared Error           |
| **RMSE** | Root Mean Squared Error      |
| **R²**   | Coefficient of Determination |

---

## 📈 Results

The notebook contains the detailed model training, evaluation, and comparison results.

The final model selection is based on predictive performance and the evaluation metrics obtained during experimentation.

> **Note:** The exact results shown in this section should be updated after the final experiments are completed so that the README reflects the actual model performance.

---

## 📁 Project Structure

```text
UCI_Student_Performance_Predictor/
│
├── 📓 *.ipynb
│   └── Machine Learning analysis and experiments
│
├── 📊 *.csv
│   └── Dataset files
│
├── 📄 *.py
│   └── Python source files
│
├── 📄 requirements.txt
│   └── Project dependencies
│
├── 📄 README.md
│   └── Project documentation
│
└── 📄 .gitignore
    └── Files excluded from Git
```

> The exact structure may vary depending on the files included in the project.

---

## 🛠️ Technologies Used

| Technology              | Purpose                           |
| ----------------------- | --------------------------------- |
| 🐍 **Python**           | Programming language              |
| 🐼 **Pandas**           | Data manipulation                 |
| 🔢 **NumPy**            | Numerical computing               |
| 📊 **Matplotlib**       | Data visualization                |
| 🎨 **Seaborn**          | Statistical visualization         |
| 🤖 **Scikit-learn**     | Machine Learning                  |
| 📓 **Jupyter Notebook** | Data analysis and experimentation |

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Mahnoor-Kalsoom/UCI_Student_Performance_Predictor.git
```

### 2. Navigate to the Project

```bash
cd UCI_Student_Performance_Predictor
```

### 3. Create a Virtual Environment

Windows:

```bash
python -m venv venv
```

Activate it:

```bash
venv\Scripts\activate
```

### 4. Install Dependencies

If the project contains `requirements.txt`:

```bash
pip install -r requirements.txt
```

### 5. Launch the Notebook

```bash
jupyter notebook
```

Then open the project's `.ipynb` file.

---

## 📚 Dataset Source

The project is based on the **UCI Student Performance Dataset**.

The dataset was originally introduced by:

**P. Cortez and A. Silva, "Using Data Mining to Predict Secondary School Student Performance," 2008.**

Please refer to the official UCI Machine Learning Repository for the dataset and its licensing/citation requirements.

---

## 💡 Key Insights

This project demonstrates how Machine Learning can be applied to educational data to:

* Identify patterns in student performance
* Understand factors associated with academic outcomes
* Compare different predictive models
* Explore the relationship between student behavior and academic results
* Develop data-driven approaches to educational analytics

---

## 🔮 Future Improvements

Potential improvements include:

* [ ] Build an interactive Streamlit application
* [ ] Add a student performance prediction form
* [ ] Perform hyperparameter optimization
* [ ] Add cross-validation
* [ ] Add feature importance visualization
* [ ] Add SHAP-based model explainability
* [ ] Deploy the model as a web application
* [ ] Add automated testing
* [ ] Add CI/CD using GitHub Actions

---

## 👩‍💻 Author

### Mahnoor Kalsoom

Machine Learning & Data Science Project

**GitHub:**
https://github.com/Mahnoor-Kalsoom

---

## ⭐ Support

If you find this project useful or interesting, consider giving the repository a ⭐ on GitHub.

---

## 📄 License

This project is intended for educational and research purposes.

Please refer to the original UCI dataset documentation for dataset licensing and citation information.
