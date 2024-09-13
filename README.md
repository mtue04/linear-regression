# Project 03: Applied Mathematics & Statistics for IT

This project involves building and evaluating linear regression models to predict student performance based on various features such as hours studied, previous scores, extracurricular activities, sleep hours, and the number of sample question papers practiced.

## Overview
This project is part of the course Applied Mathematics & Statistics for IT - 22CLC10 at University of Science, VNU-HCM, under the guidance of supervisors Vũ Quốc Hoàng, Nguyễn Văn Quang Huy, Nguyễn Ngọc Toàn, and Phan Thị Phương Uyên.

## Main Features
- Data Analysis: Exploratory data analysis (EDA) to understand the distribution and relationships between features.
- Model Building: Linear regression models using Python, including:
    + A model using all features.
    + A model using only the best single feature.
    + Custom-designed models, including feature engineering and normalization.
- Model Evaluation: Mean Absolute Error (MAE) as the main evaluation metric.

## Dependencies
- Python 3.x
- NumPy: For numerical computations and array manipulation.
- Pandas: For data processing and manipulation.
- Matplotlib: For data visualization.
- Seaborn: For enhanced data visualization.

Install the required libraries using pip:
`pip install numpy pandas matplotlib seaborn`

## Running the Project
1. Data Preprocessing: The data is loaded and preprocessed using Pandas. Key steps include feature extraction, handling missing values, and normalization for specific models.
2. Exploratory Data Analysis: Various visualizations are created to explore the relationships between features and the target variable.
3. Model Training: Different linear regression models are trained using NumPy for matrix operations.
4. Model Evaluation: The models are evaluated using MAE to compare performance.

## Results
- Best Model: The model with normalized features performed the best with a MAE of approximately 1.62.
- Significant Features: Previous scores and hours studied were found to be the most significant predictors of student performance.

## Conclusion
The project demonstrates the use of linear regression for predictive modeling, highlighting the importance of feature selection and data preprocessing in achieving accurate results.
