# SQL-Based Healthcare Analytics & ML Pipeline

**AI Internship | Healthcare Analytics**

A healthcare data analytics workflow using SQL, SQLite, and Python to query relational hospital data, explore operational patterns, engineer features, and prepare structured data for machine-learning experiments.

## Workflow

`HospitalDB.sql` → SQLite database → SQL joins and extraction → cleaning and feature engineering → exploratory analysis → visualizations → preprocessing and train/test data.

## What It Covers

- SQL joins across patients, appointments, doctors, and hospital-related tables
- Exploratory analysis of patient demographics and healthcare activity
- Feature engineering using demographic and appointment information
- Visual analysis with Matplotlib and Seaborn
- Categorical encoding, numerical scaling, and train/test preparation

## Tools

Python, SQLite, SQL, Pandas, NumPy, Matplotlib, Seaborn, scikit-learn, Jupyter Notebook.

## Run the Notebook

1. Clone or download this repository.
2. Install the notebook dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. Keep `HospitalDB.sql` in the repository root. It is included in this repository.
4. Open `SQL_Healthcare_Analytics_Pipeline_GitHub_Ready.ipynb` in Jupyter Notebook or Google Colab.
5. Run the cells sequentially.

## Example Dataset Results

The notebook works with an example dataset containing 100 appointment records and prepares an 80/20 train/test partition. These are dataset-level preparation results, not evidence of a trained or validated predictive model.

## Limitations

- This project focuses on SQL analytics, EDA, feature engineering, and ML preprocessing.
- No predictive model is trained or evaluated in this notebook.
- Findings from the example dataset may not generalize to real healthcare populations.
- This is an educational project, not a clinical decision-support system.

**Notebook:** `SQL_Healthcare_Analytics_Pipeline_GitHub_Ready.ipynb`
