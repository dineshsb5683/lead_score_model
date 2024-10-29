# Lead Conversion Prediction for X Education

### Introduction
This project focuses on predicting lead conversion rates for X Education, aiming to enhance customer acquisition and improve marketing strategies. The analysis identifies key factors influencing lead conversion from a dataset that includes various features related to leads.

### Objectives
- Build a predictive model to estimate the likelihood of lead conversion.  
- Optimize marketing strategies based on insights derived from the model.  

### Data Overview
The dataset consists of features such as:
- Lead Source  
- Last Activity  
- Lead Origin  
- Demographic Information  

### Data Cleaning and Preprocessing
- Removed columns with over 30% missing values.  
- Dropped irrelevant and redundant features.  
- Created dummy variables for categorical features to facilitate model training.  

### Methodology
#### Feature Selection
- Employed Recursive Feature Elimination (RFE) to identify 15 significant features influencing conversion rates.  

#### Model Building
- Utilized logistic regression for predictive modeling.  
- Calculated Variance Inflation Factor (VIF) to check for multicollinearity and refined the model by removing problematic features.  

### Model Evaluation
- Achieved an accuracy of 79% on the training set.  
- AUC score of 0.79 indicates good model performance in distinguishing between converted and non-converted leads.  

### Key Insights and Recommendations
1. **Lead Origin**: Prioritize leads from the Lead Add Form to enhance conversion rates.  
2. **Last Notable Activity**: Implement proactive follow-ups through phone calls and SMS.  
3. **Lead Source Optimization**: Improve user experience on the Welingak website to capture more converting leads.  
4. **Email Engagement**: Revamp email marketing strategies for leads marked as "Do Not Email."  
5. **Targeted Marketing**: Develop offerings for demographics such as students and unemployed individuals to improve engagement.  
6. **Standardize High-Performing Activities**: Integrate successful follow-up methods into the lead nurturing process.  

### Conclusion
The findings highlight the importance of refining lead generation strategies. By focusing on high-performing channels and personalizing communication, X Education can enhance lead conversion rates and foster a more engaged customer base.  

