# Stroke Prediction EDA and Accuracy
 Data Analysis and Accuracy Score for Stroke Prediction
 
 Data Brief:

    1)id: Identification number of the individual.
    2)gender: Gender of the individual.
    3)hypertension: Health related parameter, does person have hypertension.
    4)heart_disease: Health related parameter, does person have heart disease.
    5)ever_married: Personal information, is person married on not?
    6)work_type: Nature of work place.
    7)Residence_type: Residence type of the individual.
    8)avg_glucose_level: average glucose level in blood for the individual.
    9)bmi: body mass index of the individual.
    10)smoking_status: Habitual information. Current smoking status of individual.
    11)stroke: Our taget, is person suffered heart attack?


The project is stroke classification with these features.
I used Catboost for training.
gender, ever_married, work_type, residence_type and smoking_status is our categorical datas.
I used Catboost because it is easily handle with categorical data.
Catboost is very assertive in giving a good result without being tuned. So I did not tune it.

**Accurancy Score is 93.9%**
