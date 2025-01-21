# Final-Project---CARDIO-SCOPE
**Project Name:**  
CardioScope: Cardiovascular Disease Detection and Risk Assessment  

**Description:**  
CardioScope leverages machine learning to predict the risk of cardiovascular disease (CVD) based on patient health metrics such as blood pressure, cholesterol levels, and lifestyle factors. This project offers a cost-effective and scalable solution for early detection, enabling healthcare providers to deliver personalized prevention and treatment strategies. By addressing the critical need for timely interventions, CardioScope aims to reduce the global burden of cardiovascular diseases.  

**Introduction:**  
Cardiovascular diseases (CVDs) are a leading cause of mortality worldwide, placing a significant strain on healthcare systems. Early detection and prevention are critical in mitigating these risks. Traditional diagnostic methods, while effective, are often resource-intensive and inaccessible in low-resource settings.  

CardioScope addresses these challenges by employing machine learning techniques to analyze key health metrics such as age, cholesterol levels, blood pressure, and activity levels. The predictive model developed in this project empowers healthcare providers with actionable insights, enabling efficient risk stratification and targeted interventions.  

**Objective:**  
To develop a predictive model that identifies individuals at risk of cardiovascular disease using clinical and demographic data. The model will assist healthcare providers in early detection, leading to timely interventions and improved patient outcomes.  

**Problem Statement:**  
Despite advancements in medical technology, early identification of cardiovascular disease remains challenging due to the complex interplay of risk factors and limited accessibility to diagnostic tools. This project aims to bridge the gap by creating an automated and affordable solution for risk assessment using machine learning.  

**Key Challenges Addressed:**  
- Early Detection: Identifying individuals at risk of CVD at an early stage.  
- Cost-Effectiveness: Providing an affordable solution using accessible health data.  
- Automation: Simplifying risk assessment with machine learning, reducing dependency on clinical resources.  
- Personalization: Tailoring preventive recommendations based on individual health profiles.  

**Dataset Overview:**  
- **Numerical Features:** Age, systolic (ap_hi) and diastolic (ap_lo) blood pressure.  
- **Categorical Features:** Cholesterol, glucose levels, and gender.  
- **Binary Features:** Smoking, alcohol consumption, physical activity, and the target variable `cardio`.  
- **Target Variable Distribution:**  
  - Class 0: No cardiovascular disease (50.5%).  
  - Class 1: Cardiovascular disease present (49.5%).  

**Methodology:**  
The data was preprocessed through normalization, encoding of categorical features, and handling class imbalance using `scale_pos_weight`. Key steps included:  
1. Exploratory Data Analysis (EDA) to identify trends and correlations.  
2. Feature selection to focus on relevant health metrics.  
3. Model training using XGBoost, followed by hyperparameter tuning via GridSearchCV.  
4. Performance evaluation using metrics such as accuracy, precision, recall, and F1-score.  

**Results:**  
- **Best Model:** XGBoost Classifier with hyperparameter tuning.  
- **Performance Metrics:**  
  - Accuracy: 73.3%  
  - Precision: 75.4%  
  - Recall: 68.5%  
  - F1 Score: 71.8%  
- **ROC AUC Score:** 0.78  

**Conclusion:**  
The CardioScope project successfully developed a robust predictive model for early detection of cardiovascular disease risk. The XGBoost model demonstrated strong performance, making it suitable for real-world deployment in healthcare settings.  
