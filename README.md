# Medical Insurance Cost Prediction System – Documentation (Dataset Included)

## 1. Project Overview

This project focuses on predicting annual medical insurance costs using machine learning techniques. The system analyzes personal health conditions, lifestyle habits, and insurance-related attributes to estimate medical expenses accurately.

The dataset used in this project is **medical_cost_prediction_dataset.csv**, which contains structured patient-level healthcare information such as age, BMI, smoking status, stress level, sleep duration, physical activity, insurance coverage, and previous medical expenses.

The goal of this project is to assist insurance companies, hospitals, and individuals in estimating expected healthcare costs using predictive analytics.

---

## 2. Dataset Description

The dataset consists of multiple features related to personal health conditions and lifestyle habits that influence insurance expenses.

Key features include:

- Age
- Gender
- Body Mass Index (BMI)
- Smoking status
- Diabetes condition
- Hypertension status
- Heart disease condition
- Asthma condition
- Physical activity level
- Daily steps count
- Sleep duration
- Stress level
- Doctor visit frequency
- Hospital admission history
- Medication usage
- Insurance type
- Insurance coverage percentage
- City type
- Previous medical expenses

Target variable:

- Annual medical insurance cost

These features help the model understand relationships between health indicators and insurance expenses.

---

## 3. Project Objective

The main objectives of this project include:

- Predicting annual medical insurance cost using machine learning
- Identifying relationships between lifestyle habits and healthcare expenses
- Comparing regression algorithms for prediction performance
- Improving accuracy of insurance cost estimation
- Supporting healthcare decision-making using predictive analytics

---

## 4. Problem Statement

Estimating medical insurance costs manually is complex because expenses depend on multiple influencing factors such as age, medical history, lifestyle habits, and environmental conditions.

Traditional estimation methods cannot efficiently analyze large datasets or identify hidden relationships between variables. Therefore, a machine learning-based prediction system is required to improve accuracy and automation.

---

## 5. Methodology

The project follows a structured machine learning workflow.

### Data Collection

A healthcare-related dataset containing medical and lifestyle attributes is used for training the prediction model.

### Data Preprocessing

This stage includes:

- Handling missing values
- Removing inconsistencies
- Encoding categorical variables into numerical format

### Exploratory Data Analysis (EDA)

Visualization techniques are used to analyze relationships between:

- Age and medical cost
- BMI and medical cost
- Smoking habits and medical cost
- Stress level and medical cost

This helps identify important factors affecting insurance expenses.

### Feature Selection

Relevant independent variables affecting medical insurance cost are selected for model training.

### Model Training

Two regression models are implemented:

- Linear Regression
- Random Forest Regression

### Model Testing

The trained models are evaluated using testing datasets to measure prediction accuracy and reliability.

---

## 6. Machine Learning Approach

This project uses a supervised machine learning regression approach.

Steps involved include:

- Understanding dataset structure
- Cleaning and preprocessing data
- Encoding categorical variables
- Splitting dataset into training and testing sets
- Training regression models
- Evaluating prediction accuracy
- Comparing model performance
- Selecting the best-performing model

---

## 7. Technologies Used

The project is implemented using Python and the following libraries:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

These libraries support data processing, visualization, and machine learning model development.

---

## 8. Model Evaluation

The performance of regression models is evaluated using prediction accuracy metrics.

Two models were compared:

### Linear Regression

A basic regression algorithm suitable for linear relationships between variables.

### Random Forest Regression

An ensemble learning method that captures complex feature relationships and improves prediction accuracy.

Random Forest Regression produced better results compared to Linear Regression.

---

## 9. Applications of the Project

This system can be used by:

- Insurance companies for policy pricing estimation
- Hospitals for treatment cost prediction analysis
- Individuals for estimating expected healthcare expenses
- Researchers studying healthcare expenditure trends

---

## 10. Advantages of the Project

Key benefits include:

- Accurate insurance cost prediction
- Reduced manual estimation effort
- Support for healthcare analytics
- Improved insurance planning decisions
- Efficient handling of structured healthcare datasets

---

## 11. Limitations of the Project

Some limitations include:

- Prediction accuracy depends on dataset quality
- Model performance may vary across populations
- Real-world healthcare data may be more complex
- Lifestyle conditions may change over time
- Requires larger datasets for higher prediction accuracy

---

## 12. Future Enhancements

Possible improvements include:

- Using larger real-time healthcare datasets
- Deploying the model as a web application
- Integrating deep learning techniques
- Connecting hospital database systems
- Developing a user-friendly prediction interface

---

## 13. Conclusion

This project successfully demonstrates how machine learning techniques can be applied to predict medical insurance costs based on personal health and lifestyle factors.

Two regression models were implemented and evaluated, and Random Forest Regression showed better prediction performance.

The system provides an efficient and scalable solution for healthcare cost estimation and supports data-driven decision-making in the insurance sector.
