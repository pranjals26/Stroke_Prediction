# Stroke_Prediction

A stroke is a serious medical condition that occurs when blood flow to the brain is disrupted, which can cause damage to brain cells. This can be caused by a blood clot (known as an ischemic stroke) or bleeding in the brain (known as a hemorrhagic stroke).

### Problem Statement
Stroke is a major health concern globally and has a significant impact on both individuals and healthcare systems. There are many risk factors for stroke, such as hypertension, heart disease, diabetes, and lifestyle factors. Our project aims to use machine learning to analyze large datasets and accurately predict stroke risk based on these modifiable risk factors. The ultimate goal is to create a personalized stroke risk warning system that provides tailored messages to individuals, suggesting lifestyle modifications to reduce their risk of stroke. This approach has the potential to transform stroke prevention and management, decreasing the impact of this life-threatening condition on individuals and healthcare systems worldwide.

### Attribute Information 
1) id: unique identifier
2) gender: "Male", "Female" or "Other"
3) age: age of the patient
4) hypertension: 0 if the patient doesn't have hypertension, 1 if the patient has hypertension
5) heart_disease: 0 if the patient doesn't have any heart diseases, 1 if the patient has a heart disease
6) ever_married: "No" or "Yes"
7) work_type: "children", "Govt_jov", "Never_worked", "Private" or "Self-employed"
  
8) Residence_type: "Rural" or "Urban"
9) avg_glucose_level: average glucose level in blood
10) bmi: body mass index
11) smoking_status: "formerly smoked", "never smoked", "smokes" or "Unknown"* 12) stroke: 1 if the patient had a stroke or 0 if not

### Target Variable 
Target 1. Stroke: Stroke history (0 = no stroke risk, 1 = stroke risk; target variable)



<img width="511" alt="image" src="https://github.com/pranjals26/Stroke_Prediction/assets/41803622/19d02abe-08dc-47c0-b718-aca527f8ab95">


### Interpretation
1. Precision: Precision is a measure of how many of the predicted positive instances are actually true positives. A higher precision indicates a lower rate of false positives. Among the models listed, Logistic Regression and XGBoost have the highest precision scores, with values of 0.11 and 0.16, respectively.
2. F1 Score: The F1 Score is the harmonic mean of precision and recall. It provides a balanced measure between precision and recall. In this table, XGBoost has the highest F1 Score of 0.23, indicating a good balance between precision and recall.
3. ROC: The Receiver Operating Characteristic (ROC) curve is a plot of the true positive rate against the false positive rate at various classification thresholds. It measures the model's ability to discriminate between classes. XGBoost has the highest ROC score of 0.78, suggesting good discrimination between positive and negative instances.
4. Accuracy: Accuracy is the proportion of correctly classified instances out of the total instances. It is a general measure of overall model performance. XGBoost has the highest accuracy score of 0.88, indicating the highest proportion of correctly classified instances among the listed models.
5. Recall: Recall, also known as the true positive rate or sensitivity, measures the proportion of actual positive instances correctly classified by the model. It is especially important in scenarios where identifying true positives is crucial. MLP Classifier has the highest recall score of 0.81, indicating its ability to correctly identify a higher proportion of positive instances.


Considering the importance of recall as the primary evaluation metric, the MLP model achieved the highest recall score of 0.81, making it the best choice for identifying patients at risk of stroke. The development of an ML model for stroke prediction has the potential to facilitate early detection and intervention, minimizing the severity of strokes. Future opportunities include expanding the dataset and exploring additional machine learning algorithms to improve the model's performance and reliability. The ultimate goal is to provide the public with a user-friendly tool that assesses individual stroke risk and promotes early treatment and rehabilitation.
