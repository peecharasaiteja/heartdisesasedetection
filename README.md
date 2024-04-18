colab link:https://colab.research.google.com/drive/1c5pYtka_OsvArF8bQTnuWzWOd7_b2Ui9


1.Introduction
Heart disease remains one of the leading causes of mortality worldwide, necessitating effective detection methods to mitigate its impact on public health. Early identification of individuals at risk of heart disease enables timely intervention, thereby reducing morbidity and mortality rates. This project aims to develop a predictive model for heart disease detection by leveraging machine learning algorithms and clinical data.


2   Feature Description

1.	Age:
•	Represents the age of the patient in years.
2.	Sex:
•	Indicates the gender of the patient.
•	Categories: Male (1), Female (0)
3.	Chest Pain Type:
•	Specifies the type of chest pain experienced by the patient.
•	Categories:
•	Typical Angina (1)
•	Atypical Angina (2)
•	Non-Anginal Pain (3)
•	Asymptomatic (4)
4.	Resting Blood Pressure (RestingBP):
•	Represents the resting blood pressure of the patient in mm Hg.
5.	Serum Cholesterol:
•	Indicates the serum cholesterol level of the patient in mg/dl.
6.	Fasting Blood Sugar (FastingBS):
•	Indicates whether the patient's fasting blood sugar is greater than 120 mg/dl.
•	Categories: Yes (1), No (0)
7.	Resting Electrocardiographic Results (RestingECG):
•	Represents the resting electrocardiographic results of the patient.
•	Categories:
•	Normal (0)
•	ST (1)
•	LVH (2)
8.	Maximum Heart Rate Achieved (MaxHR):
•	Represents the maximum heart rate achieved by the patient.
9.	Exercise Induced Angina (ExerciseAngina):
•	Indicates whether the patient experienced exercise-induced angina.
•	Categories: Yes (1), No (0)
10.	Oldpeak:
•	Represents the ST depression induced by exercise relative to rest.
11.	ST Slope:
•	Specifies the slope of the peak exercise ST segment.
•	Categories:
•	Up (0)
•	Down (1)
•	Flat (2)
12.	Heart Disease:
•	Target variable indicating the presence (1) or absence (0) of heart disease
