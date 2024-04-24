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

### Logistic Regression
- Probabilistic Predictions: Provides probabilities that a patient will experience a heart attack, offering a quantitative measure of risk that can guide clinical decisions.
- Simplicity and Speed: Quick to train and easy to implement, making it practical for use in clinical settings where computational resources might be limited.
- Feature Impact Understanding: Direct interpretation of how each risk factor (like cholesterol levels, age, etc.) impacts the likelihood of a heart attack, aiding physicians in understanding underlying risk factors.

### Decision Tree
- Interpretability: One of the most interpretable models available. Medical practitioners can see exactly how conclusions are drawn, which is crucial for trust and verification in clinical use.
- Handling Non-linear Relationships: Can efficiently model complex, non-linear relationships that might exist between variables in heart attack risk, such as interactions between age, lifestyle, and genetic factors.
- Variable Importance: Identifies which variables are the most influential in predicting heart attacks, which can help in focusing diagnostic tests and interventions.

### Random Forest
- High Accuracy: Typically offers superior predictive accuracy through ensemble learning, which combines the predictions of multiple decision trees.
- Robustness to Overfitting: By averaging multiple trees, it tends to generalize better, making it reliable in varied clinical environments and across different patient groups.
- Handling Unbalanced Data: Effective in clinical datasets where some classes (like patients with heart attacks) might be underrepresented.

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



