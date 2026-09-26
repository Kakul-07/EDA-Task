* Heart Disease EDA and Feature Engineering *

About the Project
This project performs Exploratory Data Analysis (EDA) and Feature Engineering on a Heart Disease dataset.
The main purpose is to understand the dataset, identify data quality issues, find patterns in the data, visualize important relationships, detect outliers, and prepare the dataset for further machine learning work.

Dataset: The dataset contains 918 records and 12 columns.
The main columns are:
* Age – Age of the patient
* Sex – Gender of the patient
* ChestPainType – Type of chest pain
* RestingBP – Resting blood pressure
* Cholesterol – Cholesterol level
* FastingBS – Fasting blood sugar indicator
* RestingECG – Resting ECG result
* MaxHR – Maximum heart rate achieved
* ExerciseAngina – Exercise-induced angina
* Oldpeak – ST depression
* ST_Slope – Slope of the ST segment
* HeartDisease – Target variable

Technologies Used
* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Jupyter Notebook

Project Steps
1. Data Understanding:
* Loaded the dataset
* Checked the number of rows and columns
* Checked column names and data types
* Generated statistical summaries
* Checked categorical values

2. Data Cleaning:
* Missing values
* Duplicate records
* Invalid categorical values
* Invalid binary values
* Suspicious numerical values
RestingBP = 0 and Cholesterol = 0 were treated as invalid placeholder values. They were converted to missing values and replaced using the median.

3. Outlier Analysis:
The IQR method was used to identify statistical outliers.
Outliers were not automatically removed because extreme medical measurements can represent actual patient observations.
The detected values were inspected separately from invalid values.

4. Exploratory Data Analysis:
* Heart disease distribution
* Gender distribution
* Gender vs Heart Disease
* Chest Pain Type distribution
* Chest Pain Type vs Heart Disease
* Resting ECG vs Heart Disease
* Exercise Angina vs Heart Disease
* ST Slope vs Heart Disease
* Numerical feature distributions
* Boxplots
* Age vs Maximum Heart Rate
* Correlation matrix
* Correlation heatmap

5. Feature Engineering:
* AgeGroup
* MaxHR_Percent
* BPCategory
* CholesterolCategory
Categorical features were also converted into numerical values using one-hot encoding.

Key Observations:
* The dataset contains both heart disease and non-heart disease cases.
* Male patients are more represented than female patients.
* ASY is the most common chest pain type.
* Chest pain type shows differences in heart disease distribution.
* Age and maximum heart rate show a visible relationship.
* Several numerical features contain statistical outliers.
* Zero values in RestingBP and Cholesterol required special treatment.
* The target variable does not have a severe class imbalance.