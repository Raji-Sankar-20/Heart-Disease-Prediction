Business case
The objective of the project is to create a reliable model predicting potential Heart Diseases in people
Problem:
Heart disease is the leading cause of death globally,costing healthcare systems billions each year.

Coronary heart disease (CHD) is the most common type of heart disease, killing over 370,000 people annually.

Every year about 735,000 Americans have a heart attack. Of these, 525,000 are a first heart attack and 210,000 happen in people who have already had a heart attack.

Heart disease is the leading cause of death for people of most ethnicities in the United States, including African Americans, Hispanics, and whites. For American Indians or Alaska Natives and Asians or Pacific Islanders, heart disease is second only to cancer.

Early detection and intervention are crucial for preventing serious complications and reducing mortality (death).

However, traditional risk assessment methods often lack accuracy and personalization, leading to missed diagnoses and unnecessary interventions.

Solution:
This project proposes developing a heart disease prediction model using machine learning (ML) algorithms.
It will involve:
Task 1: Data Analysis Report: Comprehensive analysis of patient data to identify risk factors and relationships between variables.

Task 2: Machine Learning Model: Building and training an ML model to predict potential heart disease in individuals based on various factors.

Task 3: Hospital Actionable Suggestions: Recommending strategies to integrate model predictions into hospital workflows for targeted screening, personalized prevention, and improved patient outcomes.

Benefits:
Improved Accuracy: ML models can learn complex patterns in data, potentially surpassing traditional methods in predicting heart disease with greater accuracy.

Early Detection: Identifying individuals at high risk early allows for timely intervention and preventive measures, reducing complications and mortality (death).

Personalized Care: The model can tailor recommendations based on individual risk factors, leading to more effective and efficient interventions.

Cost Reduction: Early detection and prevention can significantly reduce healthcare costs associated with treating advanced heart disease stages.

Enhanced Patient Engagement: Empowering patients to understand their risk profile and actively participate in preventive measures.

Domain Analysis
There are two datasets to be utilized in this project; values and labels. The values dataset consists of 14 columns while that of label contains 2 columns. Both dataset have the patient_id column with the same values as a unique and random identifier. Both data sets will be merged as one. The presence of heart disease column is the label .it contains 2 values(datatype: binary).

The remaining 13 features are described in the section below.

slope_of_peak_exercise_st_segment (type: int): the slope of the peak exercise ST segment, an electrocardiography read out indicating quality of blood flow to the heart
thal (type: categorical): results of thallium stress test measuring blood flow to the heart, with possible values normal, fixed_defect, reversible_defect
resting_blood_pressure (type: int): resting blood pressure
chest_pain_type (type: int): chest pain type (4 values)
num_major_vessels (type: int): number of major vessels (0-3) colored by flourosopy
fasting_blood_sugar_gt_120_mg_per_dl (type: binary): fasting blood sugar > 120 mg/dl
resting_ekg_results (type: int): resting electrocardiographic results (values 0,1,2)
serum_cholesterol_mg_per_dl (type: int): serum cholestoral in mg/dl
oldpeak_eq_st_depression (type: float): oldpeak = ST depression induced by exercise relative to rest, a measure of abnormality in electrocardiograms
sex (type: binary): 0: female, 1: male
age (type: int): age in years
max_heart_rate_achieved (type: int): maximum heart rate achieved (beats per minute)
exercise_induced_angina (type: binary): exercise-induced chest pain (0: False, 1: True)
 

Heart Disease Prediction:
In heart disease prediction, exercise-induced angina holds significant weight as:

Symptom of underlying heart disease: Its presence strongly suggests potential coronary artery disease (CAD), the leading cause of heart attacks. Non-invasive indicator: Unlike invasive tests like angiography, exercise stress tests can safely screen and identify individuals at risk for heart disease by revealing angina. Severity marker: The severity and duration of angina during exercise provide clues to the extent of potential heart damage and disease progression. However, it's important to remember:

Not everyone with angina has heart disease: Other factors like musculoskeletal issues or anxiety can also trigger chest pain during exercise. Some people with heart disease may not experience angina: The degree of disease severity and individual variations in symptoms are at play. Therefore, exercise-induced angina is a crucial symptom to consider in heart disease prediction, but it should be interpreted along with other clinical factors, risk assessments, and diagnostic tests for a comprehensive evaluation.