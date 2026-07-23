# 📚Student Dropout Data Engineering Pipeline

*Student:* Muneera Almojel

*Major:* Information Systems

*Program:* SDAIA Academy – Data Engineering for AI Systems (DAICO)

*Trainer:* Mohammed Albeladi

# 📖 Project Overview

This project demonstrates an end-to-end data engineering pipeline using a real-world student dropout dataset.

The pipeline starts with raw data ingestion, followed by data validation, data cleaning, Bronze, Silver, and Gold layers. Finally, a Random Forest machine learning model is used to predict student academic status.


#  🎯Project Objectives

- Load the raw dataset.
- Validate data quality.
- Build Bronze, Silver, and Gold layers.
- Prepare clean data for analytics.
- Train a Random Forest classification model.
- Evaluate the model performance.


# 📂Dataset

The project uses a real student dropout dataset containing demographic, academic, and socioeconomic attributes.

Target Classes:

- Graduate
- Dropout
- Enrolled


# ⚙️ Pipeline Architecture

1. Data Ingestion
2. Dataset Overview
3. Data Validation
4. Bronze Layer
5. Silver Layer
6. Gold Layer
7. Machine Learning
8. Model Evaluation

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- GitHub


# 📁 Repository Structure

Student-Dropout-Data-Pipeline/
```text

│── Student_Dropout_Data_Pipeline.ipynb
│── Data dropout.csv
│── bronze_student_dropout.csv
│── silver_student_dropout.csv
│── gold_student_dropout_summary.csv
│── README.md
```

# How to Run

1. Open Student_Dropout_Data_Pipeline.ipynb using Google Colab or Jupyter Notebook.
2. Upload Data dropout.csv to the notebook environment.
3. Run all notebook cells in order.
4. The pipeline generates the following output files:
   - bronze_student_dropout.csv: raw ingested data.
   - silver_student_dropout.csv: cleaned and validated data.
   - gold_student_dropout_summary.csv: aggregated summary by student status.

# Data Validation

The notebook performs basic validation checks, including:

- Checking the dataset dimensions and column names.
- Checking missing values.
- Checking duplicate records.
- Verifying the target classes.
- Cleaning and preparing the data before model training.

# Layer Description

- *Bronze Layer:* Stores the raw dataset without analytical transformations.
- *Silver Layer:* Stores the cleaned dataset after removing duplicates and handling data-quality issues.
- *Gold Layer:* Stores an aggregated summary of student outcomes for reporting and analysis.

# Project Scope and Limitations

This implementation is a local educational prototype developed with Python and Pandas.  
Kafka, Delta Lake, Airflow, RAG, Great Expectations, and OpenLineage are not implemented in the current version. These technologies are considered possible future extensions.

# 📊 Results

The pipeline successfully processed the dataset through Bronze, Silver, and Gold layers.

A Random Forest classifier was trained to predict student academic status and evaluated using:

- Accuracy
- Classification Report
- Confusion Matrix



# ✅ Conclusion

This project demonstrates a local educational data pipeline integrated with machine learning. It transforms raw student data into cleaned and aggregated datasets and trains a Random Forest model to predict student academic outcomes.
