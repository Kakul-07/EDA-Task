# Heart Disease EDA
## About the Project
This project is based on the Heart Disease dataset.

## Libraries Used
- NumPy
- Pandas
- Matplotlib
- Seaborn

## Work Done
1. Loaded and checked the dataset.
2. Checked rows, columns, data types and basic statistics.
3. Checked missing values and duplicate rows.
4. Checked unique values and categories.
5. Checked invalid values such as zero RestingBP and Cholesterol.
6. Studied HeartDisease distribution.
7. Analysed gender, chest pain, RestingECG, ExerciseAngina, ST_Slope and FastingBS.
8. Used histograms and boxplots for numerical features.
9. Checked correlation between numerical features.
10. Detected outliers using the IQR method.
11. Cleaned invalid zero values using median replacement.
12. Created AgeGroup, MaxHR_Percent, BPCategory and CholesterolCategory.
13. Encoded categorical features using one-hot encoding.
14. Checked the final dataset.

## Dataset:  The dataset contains 918 rows and 12 columns.

The target column is `HeartDisease`.
- `0` = No heart disease
- `1` = Heart disease

## Important Data Cleaning
`RestingBP = 0` and `Cholesterol = 0` were treated as invalid measurements for this analysis. They were replaced with missing values and then filled using the median.
IQR outliers were only identified.

## Files
- `Heart.csv` - dataset
- `Heart_Disease_EDA_Clean.ipynb` - EDA notebook
- `README_Heart_Disease_EDA.md` - project information
