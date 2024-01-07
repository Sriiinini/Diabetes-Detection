# Diabetes Detection among patients with various risk factors

##Project Aim
The aim of this project is to investigate the likelihood of diabetes through a comprehensive analysis of various risk factors. Unlike traditional methods relying heavily on logistic regression, more robust machine learning techniques, particularly ensemble methods known for capturing complex relationships have been used for this project. The project aims to achieve practical significance by identifying high-risk individuals early and contributing to targeted strategies for reducing diabetes prevalence.

## Dataset and Exploratory Data Analysis
The dataset, sourced from the Behavioral Risk Factor Surveillance Survey (BRFSS) 2015, comprises 441k responses and 330 features. Feature selection focused on the top 25 features influencing diabetes based on research, aiming to enhance computational efficiency and model performance. Data cleaning involved the removal of duplicates, invalid responses, and missing data, preserving data quality. Exploratory Data Analysis revealed insights into the data science pipeline, addressing challenges in healthcare data marked by irregularities in self-reported or cross-sectional datasets.

## Machine Learning Models
Initial observations led to an investigation of prevalent simple models used in healthcare, with logistic regression as our baseline, showcasing an impressive F1 score of 0.794. Ensemble methods, particularly XGBoost, outperformed other models, yielding an F1 score of 0.801. Feature importance analysis highlighted high blood pressure as the most influential factor in determining a patient's diabetic stage.

## Conclusion
In conclusion, our project delves into providing valuable insights into predictive modeling in the domain of diabetes prediction. The dual focus on risk factors and practical impact sets the project apart, offering some recommendations for future exploration.
