# Medical Insurance Cost Prediction  

## Project Overview  
This project aims to build a predictive model for estimating medical insurance charges based on various patient characteristics using regression analysis.  

## Objectives  
- Develop a model to predict medical insurance costs.  
- Analyze the impact of patient characteristics such as age, sex, BMI, number of children, smoking status, and region on insurance charges.  

## Dataset  
The dataset contains information on **1,338 individuals** and includes the following features:  
- `age`: Age of the individual  
- `sex`: Gender of the individual  
- `BMI`: Body Mass Index  
- `children`: Number of children/dependents covered by insurance  
- `smoking`: Smoking status (yes/no)  
- `region`: Geographic region  
- `charges`: Medical insurance charges (target variable)  

### Key Statistics  
- Average Age: 39 years  
- Average BMI: 30.45  
- Average Number of Children: 1  
- Mean Insurance Charges: $13,261  

## Methodology  
1. **Data Preprocessing**: Checked for missing values.  
2. **Exploratory Data Analysis**: Analyzed variable distributions and relationships.  
3. **Feature Engineering**: No new features were created; existing features were deemed sufficient.  
4. **Model Selection**: The following models were employed:  
   - Linear Regression  
   - Decision Tree Regressor  
   - Random Forest Regressor  

## Key Findings  
- Pearson’s correlation matrix was analyzed to understand relationships between variables.  
- Model performance metrics and evaluations need to be conducted.  

## Conclusions and Recommendations  
- Next steps include training and evaluating the regression models, selecting the best-performing model, and conducting further feature engineering and hyperparameter tuning.  
- Consider evaluating additional models for improved predictions.  

## Future Work  
- Explore correction for potential biases in the dataset.  
- Implement visualization techniques to better illustrate results.  
- Extend the analysis to include various machine learning algorithms for comparison.  

## Installation and Usage  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/Kamuyu-cyber/medical-insurance-prediction.git  
   cd medical-insurance-prediction
