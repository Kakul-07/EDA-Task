This project is about Exploratory Data Analysis of Life Expectancy.
The dataset contains information about different countries from 2000 to 2015. It includes health, economic, social and population-related information.
The main aim is to understand which factors are related to life expectancy.

Dataset: The dataset contains 2,938 rows and 22 columns.

The main target column is:
* Life expectancy

Some important columns are:
* Country
* Year
* Status
* Adult Mortality
* Infant Deaths
* Alcohol
* BMI
* HIV/AIDS
* GDP
* Population
* Schooling
* Immunization values

What I Did:

1. Data Understanding
* Checked shape of the dataset
* Checked columns and data types
* Used head() and describe()
* Checked basic statistics

2. Data Cleaning:
* Checked missing values
* Checked duplicate rows
* Checked invalid and suspicious values
* Fixed column names
* Handled missing values
* Checked zero values where necessary

3. Outlier Handling:
* Used the IQR method to detect outliers
* Used boxplots to understand extreme values
* Did not remove genuine extreme country values blindly
* Applied capping to selected highly skewed columns

4. EDA:
* Life expectancy distribution
* Developed vs Developing countries
* Life expectancy over the years
* Country-wise average life expectancy
* Schooling vs Life expectancy
* Adult Mortality vs Life expectancy
* Correlation between numerical variables

5. Feature Engineering
* average_immunization
* total_child_deaths
* average_thinness
* status_encoded
* years_since_2000

Main Findings

* Life expectancy is different across countries.
* Developed and developing countries show differences in life expectancy.
* Life expectancy changes over the years.
* Schooling and adult mortality show noticeable relationships with life expectancy.
* Some variables such as GDP and population contain highly extreme values.
* Several health and economic variables are useful for understanding life expectancy.