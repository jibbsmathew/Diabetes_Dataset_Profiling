# Diabetes Dataset - Exploratory Data Analysis using Pandas Profiling

This repository provides a dataset related to diabetes, containing several attributes that can be used to predict the onset of diabetes in patients. The dataset consists of the following variables:

- `Pregnancies`: Number of times pregnant.
- `Glucose`: Plasma glucose concentration after 2 hours in an oral glucose tolerance test.
- `BloodPressure`: Diastolic blood pressure (mm Hg).
- `SkinThickness`: Triceps skinfold thickness (mm).
- `Insulin`: 2-Hour serum insulin (mu U/ml).
- `BMI`: Body mass index (weight in kg/(height in m)^2).
- `DiabetesPedigreeFunction`: Diabetes pedigree function (a function that represents the likelihood of diabetes based on family history).
- `Age`: Age (years).
- `Outcome`: Binary variable indicating the presence of diabetes (1 = Yes, 0 = No).

To analyze and explore the diabetes dataset, we will use the pandas profiling library to generate a detailed report on the dataset.

## Dataset Description

The dataset contains information on pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, age, and the presence of diabetes for a group of patients.

## Dataset Source

The dataset is not mentioned in the provided information. Please provide the source of the dataset.

## Pandas Profiling

To generate a report using pandas profiling, follow these steps:

1. Load the dataset into your Python environment using a library such as pandas.
2. Install the pandas profiling library using the command `pip install pandas-profiling`.
3. Import the necessary libraries: `import pandas as pd` and `import pandas_profiling`.
4. Read the dataset into a pandas DataFrame.
5. Generate the profile report using the `pandas_profiling.ProfileReport()` function.
6. Review the generated report to gain insights into the dataset. The report will include information on the dataset's statistics, missing values, correlations, distributions, and more.
