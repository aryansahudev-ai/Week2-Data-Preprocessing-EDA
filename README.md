# Student Performance Data Preprocessing and EDA

## Project Overview
This project explores student performance data using Python. It includes data inspection and cleaning, outlier detection, visualizations, correlation analysis, categorical encoding, feature scaling, and statistical tests to explore how selected features relate to final grades.

## Objective
- Understand the dataset structure and data quality.
- Handle missing, invalid, and inconsistent values.
- Explore student performance using charts and summary statistics.
- Analyze relationships between selected features and `FinalGrade`.
- Encode categorical features and scale selected numerical features.

## Dataset Source
The dataset was obtained from Kaggle:

**Student Performance Predictions**  
https://www.kaggle.com/datasets/haseebindata/student-performance-predictions

Please refer to the Kaggle dataset page for the original dataset description, licensing information, and usage conditions.

## Tools and Libraries
- **Python** – programming language used for the analysis.
- **Pandas** – loading, inspecting, and cleaning data.
- **NumPy** – numerical operations and missing-value handling.
- **Matplotlib** and **Seaborn** – data visualizations.
- **SciPy** – Pearson correlation and Chi-square tests.
- **Scikit-learn** – standard scaling of numerical features.
- **Jupyter Notebook** – running and documenting the workflow.

## Project Workflow
1. Load the CSV file and inspect its rows, columns, data types, summary statistics, missing values, and duplicates.
2. Clean the data by converting selected columns to numeric types, handling invalid values, and filling missing values.
3. Inspect potential outliers using boxplots and the IQR method.
4. Explore numerical distributions and categorical counts using charts.
5. Examine relationships between study hours, parental support, and final grades.
6. Calculate a correlation matrix and inspect correlations with `FinalGrade`.
7. Encode categorical features, standardize selected numerical features, and use Pearson correlation and Chi-square tests to explore feature relationships.
8. Save the selected columns to `student_performance_final.csv`.

## Conclusion
This project provides practice in the main stages of data preprocessing and exploratory data analysis. The visualizations and statistical tests help explore patterns in student performance and possible relationships between student features and final grades. These findings show associations in the dataset and do not, by themselves, prove causation.
