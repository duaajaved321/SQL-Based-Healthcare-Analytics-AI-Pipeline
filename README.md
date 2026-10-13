# SQL-Based Healthcare Analytics & ML Pipeline

**AI Internship | Milestone 02**

A healthcare data analytics pipeline that uses **SQL, Python, and machine learning preprocessing** to extract, analyze, visualize, and prepare structured healthcare data for predictive modeling.

## Features

- **Database Integration:** Connects to a local SQLite database.
- **SQL Queries:** Uses joins to combine patients, appointments, doctors, and hospital information.
- **Exploratory Data Analysis (EDA):** Analyzes patient demographics, appointment patterns, medical specialties, and prescription activity.
- **Data Visualization:** Uses Matplotlib and Seaborn to explore healthcare trends.
- **Feature Engineering:** Extracts age-related and appointment-based features.
- **ML Preprocessing:** Applies categorical encoding, numerical scaling, and train-test splitting.

## Tech Stack

- Python
- SQLite / SQL
- Pandas and NumPy
- Matplotlib and Seaborn
- Scikit-learn
- Google Colab / Jupyter Notebook

## Workflow

```text
Healthcare SQL Dataset
         ↓
SQLite Database
         ↓
SQL Joins & Data Extraction
         ↓
Data Cleaning & Feature Engineering
         ↓
Exploratory Data Analysis
         ↓
Visualizations
         ↓
ML Preprocessing
         ↓
Train / Test Datasets
```

## Key Results

The notebook demonstrates:

- Analysis of 100 appointment records.
- Exploration of patient ages, appointment reasons, and healthcare activity.
- Generation of demographic and appointment-related features.
- Preparation of 80 training and 20 testing samples.
- Transformation of the input data into 29 features for machine learning.

These results reflect the example dataset and notebook outputs, rather than an independently validated predictive model.

## How to Run

1. Clone or download the repository.
2. Install the required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Place the original SQLite-compatible `HospitalDB.sql` file in the project directory.
4. Open `healthcare_analytics.ipynb` in Jupyter Notebook or Google Colab.
5. Run all cells sequentially.

The notebook creates a local SQLite database from the supplied SQL script and executes the analytics pipeline.

## What I Learned

- Writing SQL queries and joining relational tables.
- Extracting SQL data into Pandas DataFrames.
- Performing exploratory data analysis and visualizations.
- Identifying patterns in structured healthcare datasets.
- Creating features from demographic and date information.
- Applying encoding and feature scaling.
- Preparing training and testing datasets for machine learning.

## Limitations

- The project depends on the original `HospitalDB.sql` dataset.
- Dataset-level findings may not generalize to real healthcare populations.
- No predictive model was trained or evaluated.
- The pipeline focuses on analytics and ML data preparation rather than deployment.
- The project is intended for educational purposes and is not a clinical decision-support system.

## Conclusion

This milestone demonstrates an end-to-end workflow connecting **relational databases, SQL analytics, exploratory data analysis, feature engineering, and machine learning preprocessing**.

It establishes a foundation for future predictive analytics and AI applications.

---

**Project Type:** AI Internship Milestone 02  
**Focus:** SQL, Healthcare Analytics, EDA, Feature Engineering, ML Preprocessing
