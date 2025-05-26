
Titanic Dataset – Data Cleaning & Preprocessing

Internship Task | AI & Machine Learning
This project is part of my AI & ML internship, where I performed data cleaning and preprocessing on the Titanic dataset using Python. The goal was to prepare raw data for machine learning by addressing missing values, encoding categorical variables, scaling numerical features, and removing outliers.

--Objective
To transform raw Titanic dataset into a clean, structured format suitable for machine learning by performing:
Handling of missing values
Encoding of categorical variables
Normalization of numerical features
Visualization and removal of outliers


-- Dataset Information

Source: Titanic dataset (available in the Seaborn library)

Description: Contains demographic and survival information of passengers aboard the Titanic

--Tools & Libraries Used

Tool / Library	Purpose

Python	Programming language
Pandas	Data manipulation
NumPy	Numerical operations
Seaborn	Data visualization
Matplotlib	Plotting charts
scikit-learn	Feature scaling (StandardScaler)

 --Step-by-Step Process

1. Dataset Loading & Exploration

Loaded the dataset using Seaborn

Explored null values, data types, and basic statistics


2. Missing Value Treatment

Filled missing age values with mean

Imputed missing embarked entries with mode

Dropped the deck column due to excessive missing data


3. Encoding Categorical Variables

Applied Label Encoding for sex (male → 0, female → 1)

Used One-Hot Encoding for embarked column


4. Feature Scaling

Normalized age and fare using StandardScaler to improve model performance


5. Outlier Detection & Removal

Visualized numerical columns using boxplots

Removed outliers in the fare column using the IQR method

 --Final Output

A clean, preprocessed DataFrame

Ready for further steps in the machine learning pipeline (e.g., modeling, training)
