# PRODIGY_DS_02 *Titanic Dataset Analysis*: 

*Overview*:

The primary objective was to perform data cleaning and exploratory data analysis (EDA) on the Titanic dataset from Kaggle. This analysis aims to explore the relationships between variables and identify patterns and trends that could be crucial for predictive modeling.

*Data Cleaning:*

The initial step involved loading the Titanic datasets and addressing any inconsistencies and missing values:

Missing Values: Missing values were identified and filled appropriately. For example, 'Age' and 'Fare' were filled with their respective median values, 'Embarked' was filled with the mode, and 'Cabin' was imputed with 'Unknown'.
Outliers: Outliers in the 'Fare' column were handled using the Interquartile Range (IQR) method to cap extreme values, ensuring they don't skew the analysis.

*Feature Engineering*:
To enhance the dataset and uncover deeper insights, several new features were engineered:

Family Size: Combined 'SibSp' and 'Parch' to create a 'FamilySize' feature, representing the total number of family members aboard.
Is Alone: Derived from 'FamilySize', this feature indicates whether a passenger was alone or not.
Title Extraction: Extracted titles from passenger names and grouped them into categories to identify patterns in survival rates linked to social status and profession.
Categorical Encoding: Applied one-hot encoding to categorical variables such as 'Sex', 'Embarked', and 'Title' to convert them into a format suitable for machine learning models.

*Exploratory Data Analysis (EDA)*
A variety of visualizations were generated to understand the data better:

Missing Values Heatmap: A heatmap to visualize the distribution of missing values in the dataset.
Correlation Matrix: Displayed correlations between numerical features to identify strong relationships.
Histograms: Plotted for numerical features to observe their distributions.
Count Plots: Used for categorical features to see their frequency distributions.
Bar Plots: Illustrated survival rates by different features such as 'Sex' and 'Pclass'.
Box Plots and Violin Plots: Used to examine the distribution of numerical features like 'Age' and 'Fare' against survival status.

*Key Insights*:
The analysis revealed several critical insights:

Gender and Survival: Females had a significantly higher survival rate compared to males.
Class and Survival: Passengers in higher classes (1st and 2nd) had better chances of survival.
Family Size and Survival: Passengers with smaller families had higher survival rates compared to those with larger families.

*Conclusion*:
This project has significantly enhanced my skills in data cleaning, feature engineering, and exploratory data analysis using Python. The insights obtained from the Titanic dataset are not only fascinating but also provide a strong foundation for further predictive modeling efforts.
