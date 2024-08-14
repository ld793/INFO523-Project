---
editor_options: 
  markdown: 
    wrap: 72
---

# INFO523-Project

This project will explore outlier detection methods in the context of
data mining. Outlier values can impact data analysis and results, and it
is important to detect them as data is mined. Outliers can be
categorized as global, collective, or contextual. The methods discussed
in this project will focus mostly on global outliers which are defined
as data points that are very different from the rest of the data values.
However, we will discuss a case of contextual outliers which are defined
as data points that stand out from the data in specific conditions.

Outliers can arise from inherent human error such as measurement
mistakes and incorrect data entry. For this reason, it is important to
understand the possible values in for any given variable before applying
statistical detection methods.

This project will focus on a dataset called Diabetes Patients Data
obtained from Kaggle.com.

Details of the data from kaggle.com:

"This dataset is originally from the National Institute of Diabetes and
Digestive and Kidney Diseases. The objective of the dataset is to
diagnostically predict whether a patient has diabetes, based on certain
diagnostic measurements included in the dataset. Several constraints
were placed on the selection of these instances from a larger database.
In particular, all patients here are females at least 21 years old of
Pima Indian heritage.2 From the data set in the (.csv) File We can find
several variables, some of them are independent (several medical
predictor variables) and only one target dependent variable (Outcome)."

"Information on the parameters can be found at
<https://openventio.org/wp-content/uploads/Determinants-of-Gestational-Diabetes-Pedigree-Function-for-Pima-Indian-Females-IMOJ-6-121.pdf>
research report.

"It counts on 9 important study characteristics such as:

-   diastolic blood pressure (DBP) (mm Hg),

-   age (in years), number of pregnancies (NOPs),

-    2-hours serum insulin (µU/ml) (Insulin),

-   triceps skin fold thickness (TSFT) (mm),

-   plasma glucose concentration over 2-hours in an oral glucose
    tolerance test (Glucose),

-   diabetes pedigree function (DPF),

-   study unit type (SUT) (1=non- diabetic, 2=diabetic),

-   and body mass index (BMI)."
