# Mental Health Treatment Prediction Using Distributed Processing and Machine Learning

## Overview

This project presents a scalable Big Data solution for predicting whether an individual is likely to require mental health treatment using distributed data processing and machine learning. The system processes a large-scale mental health dataset through Apache Spark, applies feature engineering techniques, trains multiple classification models, and visualizes the results using an interactive Power BI dashboard.

The project demonstrates how distributed computing can efficiently handle large datasets while providing meaningful insights to support early mental health intervention.

---

## Project Objectives

* Predict whether an individual is likely to require mental health treatment.
* Process large-scale data using Apache Spark.
* Build an end-to-end Big Data analytics pipeline.
* Compare the performance of multiple machine learning models.
* Visualize analytical results through an interactive Power BI dashboard.

---

## Dataset

The project uses a large mental health survey dataset containing demographic, behavioral, workplace, and psychological attributes. The dataset consists of approximately **292,000 records**, making it suitable for distributed processing techniques.

---

## System Architecture

The project follows a complete Big Data architecture consisting of the following layers:

Data Source
↓
Data Ingestion
↓
Distributed Storage (Parquet)
↓
Apache Spark Processing
↓
Processed Storage
↓
Machine Learning Models
↓
Power BI Visualization

---

## Project Workflow

1. Load the mental health dataset.
2. Clean and preprocess the data.
3. Encode categorical variables using Spark.
4. Assemble features for machine learning.
5. Train multiple classification models.
6. Evaluate model performance.
7. Export processed results.
8. Build an interactive Power BI dashboard for visualization.

---

## Technologies Used

* Python
* Apache Spark
* Spark MLlib
* Google Colab
* Pandas
* NumPy
* Parquet
* Power BI

---

## Machine Learning Models

The following classification algorithms were implemented and evaluated:

* Logistic Regression
* Random Forest Classifier
* Gradient Boosted Trees

---

## Model Performance

| Model                  | Accuracy |
| ---------------------- | -------- |
| Logistic Regression    | 0.714    |
| Gradient Boosted Trees | 0.698    |
| Random Forest          | 0.687    |

Among all evaluated models, **Logistic Regression achieved the highest accuracy**, indicating that the relationships between the selected features and treatment prediction are largely linear.

---

## Dashboard

The Power BI dashboard provides interactive visualizations that summarize:

* Treatment distribution
* Demographic analysis
* Model comparison
* Prediction insights
* Overall dataset statistics


## Key Features

* Distributed data processing using Apache Spark.
* Scalable machine learning pipeline.
* Efficient feature engineering with Spark ML.
* Comparison of multiple classification algorithms.
* Interactive Power BI dashboard.
* End-to-end Big Data analytics workflow.

---

## Future Improvements

* Integrate real-time streaming using Apache Kafka.
* Explore deep learning approaches.
* Improve feature engineering using domain knowledge.
* Deploy the prediction model as a web application.

