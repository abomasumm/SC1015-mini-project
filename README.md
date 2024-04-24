# Heart Attack Analysis & Prediction

## Introduction
This project aims to analyze and predict heart attacks based on various physiological and medical factors. Heart attacks, also known as myocardial infarctions, occur when a part of the heart muscle doesn't receive enough blood, often due to blockages in the coronary arteries.

## Problem Definition
The goal of this project is to apply data science techniques to predict the likelihood of a heart attack based on patient data, thereby potentially saving lives by enabling preventive measures.

## Flow of Pipeline
1. Data Cleaning and Preprocessing
2.Exploratory Data Analysis (EDA)
3. Exploratory Data Analysis (EDA)
4. Model Building
5. Model Evaluation
6. Conclusion

## Key Findings from EDA

- **Age Distribution**: The majority of patients experiencing heart attacks were found to be in the age range of 50-60 years. This suggests a higher risk in this age group.

- **Gender Differences**: Males are statistically more likely to experience heart attacks than females, with about 68% of the dataset comprising males who have suffered a heart attack.

- **Cholesterol Levels**: Patients with heart attacks had higher average cholesterol levels compared to the healthy group, indicating a strong correlation between high cholesterol levels and heart attack incidence.

- **Blood Pressure Insights**: High systolic blood pressure was another common factor among heart attack patients, with most patients showing systolic blood pressures above 140 mmHg.

- **Smoking and Heart Attacks**: Smoking status showed a significant correlation with heart attack occurrences. Smokers comprised approximately 30% of heart attack cases, underscoring smoking as a major risk factor.

- **Impact of Exercise**: Patients engaging in regular physical activity were less likely to have a heart attack, highlighting the protective effect of exercise against heart disease.


## What Did We Process in the EDA

- **Missing Values**: Identified and imputed missing values using statistical methods such as median imputation for skewed distributions and mean imputation for normally distributed features.
  
- **Feature Analysis**: Conducted detailed univariate and bivariate analyses, using box plots to visualize distributions and outliers, and bar charts to compare categorical variables.
  
- **Data Normalization**: Standardized numerical features to have zero mean and unit variance, essential for effective model performance.
  
- **Correlation Analysis**: Utilized Pearson correlation coefficients to identify strongly correlated variables, helping to understand the relationships between different risk factors and heart attack incidence.

## Statistical Descriptions
Detailed statistical analysis, including mean, median, mode, and distribution of data sets to understand the trends and underlying patterns in heart health data.

## Machine Learning Models

The models used in this project include:

Logistic Regression
Decision Tree
Random Forest

## Evaluations of Models

Each model was evaluated based on its performance metrics:

Logistic Regression showed promising precision but lower recall.
Decision Trees provided good interpretability but were prone to overfitting.
Random Forest achieved the best overall accuracy and ROC-AUC score, indicating its effectiveness in handling unbalanced datasets.

## Conclusion

The Random Forest model outperformed other models in terms of accuracy and ability to predict heart attacks. This suggests that ensemble methods, which consider multiple decision paths, are better suited for complex health datasets.

## What We Have Learned

This project reinforced the importance of careful feature selection and model tuning in improving prediction accuracies. It also highlighted the critical role of EDA in understanding underlying data characteristics before applying machine learning algorithms.

## Contributors

- Ghate Harshal Shrikant
- Solis Aaron Mari Santos
- Ethan Wong Kee Jann

## Acknowledgements
Aaron: Machine Learning Models, Problem Formulation, Debugging
Ethan: Sourcing of Data, Data Cleaning and Prepping, Problem Formulation, Slides
Harshal: Exploratory Data Analysis, Problem Formulation, Slides
## References
https://www.kaggle.com/code/kanncaa1/heart-attack-analysis-prediction (link to download the dataset)
https://archive.ics.uci.edu/dataset/45/heart+disease (info about dataset)



