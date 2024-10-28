# lab-flask

Web App:
https://prediabetes.onrender.com/

Diabetes Prediction Machine Learning Model
This project involves the development of a machine learning model for predicting diabetes using a dataset from Kaggle. The model requires the following input features:

Pregnancies: Number of times pregnant
Glucose: Plasma glucose concentration during a 2-hour oral glucose tolerance test
Blood Pressure: Diastolic blood pressure (mm Hg)
Skin Thickness: Triceps skin fold thickness (mm)
Insulin: 2-hour serum insulin (mu U/ml)
BMI: Body mass index (calculated as weight in kg/(height in m)^2)
Diabetes Pedigree Function: A function indicating diabetes ancestry
Age: Age in years
After processing the input data, the model predicts whether the individual has diabetes.

Data Preparation and Model Development
The Kaggle diabetes dataset was first cleaned and analyzed for outliers using data visualization libraries such as Seaborn, Matplotlib, and Bokeh. Outliers were removed based on statistical analysis conducted with Pandas and NumPy.

To address the class imbalance in the dataset, techniques such as SMOTE (Synthetic Minority Over-sampling Technique) were employed. The model leverages Logistic Regression—a crucial supervised machine learning algorithm. The development process included:

Standardization of features
Splitting the data into training and test sets
Model validation using cross-validation techniques
The trained model and the standard scaler were serialized using the Pickle module for future predictions.

Deployment
The model was built and deployed on Microsoft Azure, ensuring accessibility and scalability.

Technical Skills
Programming Languages: Python
Statistical Analysis: Proficient in statistics for data evaluation
Data Manipulation and Visualization: Expertise in data cleaning, exploratory data analysis (EDA), and feature engineering
Machine Learning: Experience with supervised machine learning algorithms, particularly Logistic Regression
Web Development: Intermediate knowledge of HTML and CSS
Frameworks: Familiar with Flask for deploying machine learning models
