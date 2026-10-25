# 🚕 Automatidata – NYC TLC Fare Prediction & Machine Learning Pipeline

## 📌 Executive Summary
This project is an end-to-end data science and machine learning pipeline developed across the [Google Advanced Data Analytics Professional Certificate](https://www.coursera.org/professional-certificates/google-advanced-data-analytics). 

Acting as a Data Analyst / Data Scientist at **Automatidata**, a data consulting firm, this project involves consulting for the **New York City Taxi and Limousine Commission (TLC)**. The NYC TLC regulates over 200,000 taxi cab and for-hire vehicle licensees processing roughly one million daily trips. 

The primary business goal is to analyze trip data, perform exploratory analysis and statistical testing, and build predictive models (Multiple Linear Regression and Tree-Based ML models) to estimate taxi fares prior to each ride based on distance, time of day, and key trip characteristics.

---

## 🛠️ Tech Stack & Tools
* **Programming Language:** Python 3.x
* **Data Analysis & Viz:** Pandas, NumPy, Matplotlib, Seaborn
* **Statistical Analysis:** SciPy, Statsmodels
* **Machine Learning:** Scikit-Learn, XGBoost
* **Workflow Framework:** PACE (Plan, Analyze, Construct, Execute)
* **Environment:** Jupyter Notebooks / Google Colab / Coursera Jupyter Lab

---

## 📁 Repository Structure
```text
├── data/
│   ├── raw/                           # Raw NYC TLC trip datasets
│   └── processed/                     # Feature engineered and cleaned datasets
├── docs/
│   ├── PACE_Strategy_Document.docx     # PACE planning roadmap across project phases
│   ├── Executive_Summaries/           # Stakeholder summaries for each phase
│   └── Project_Proposals/             # Initial scoping & milestone deliverables
├── notebooks/
│   ├── 01_data_inspection_prep.ipynb  # Course 1: Data inspection & project planning
│   ├── 02_exploratory_data_analysis.ipynb # Course 2: EDA & data visualization
│   ├── 03_hypothesis_testing.ipynb    # Course 3: Statistical A/B testing
│   ├── 04_regression_modeling.ipynb   # Course 4: Multiple linear regression
│   ├── 05_machine_learning_tree.ipynb # Course 5: Random Forest & XGBoost modeling
│   ├── 06_model_evaluation.ipynb      # Course 6: Advanced evaluation & hyperparameter tuning
│   └── 07_final_capstone_presentation.ipynb # Course 7: Final stakeholder presentation
├── README.md                          # Project documentation
└── requirements.txt                   # Project dependencies

How to Run the Project
Clone the repository:

Bash
git clone [https://github.com/your-username/automatidata-nyc-tlc-fare-prediction.git](https://github.com/your-username/automatidata-nyc-tlc-fare-prediction.git)
cd automatidata-nyc-tlc-fare-precision
Install dependencies:

Bash
pip install -r requirements.txt
Run Notebooks: Launch Jupyter and follow the sequential notebooks located in the notebooks/ directory.
