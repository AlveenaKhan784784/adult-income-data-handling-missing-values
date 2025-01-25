# adult-income-data-handling-missing-values
# Adult Income Dataset: Handling Missing Values

## Overview
This project focuses on the Adult Income dataset, which is used to predict whether an individual's income exceeds $50,000 per year based on various demographic and personal attributes. The primary objective of this analysis is to handle missing values in the dataset to prepare it for further analysis and modeling.

## Dataset Description
The Adult Income dataset contains various features, including:

- Age
- Work Class
- Education
- Marital Status
- Occupation
- Relationship
- Race
- Sex
- Capital Gain
- Capital Loss
- Hours Worked Per Week
- Native Country

## Missing Values Handling

### Step 1: Identifying Missing Values
The first step involves loading the dataset and checking for missing values. This was done using the `isnull().sum()` function, which provides a count of missing values for each column.

### Step 2: Analyzing Missing Values
After identifying the columns with missing values, the percentage of missing values was analyzed to determine the best approach for handling them.

### Step 3: Handling Missing Values
- **Work Class**: The missing values in the `workclass` column (5%) were filled with the mode (most common value) of the column.
- **Occupation**: Missing values in the `occupation` column were also replaced with the 'Unknown'.
- **Native Country**: Missing values in the `native-country` column were filled with the mode value.

### Link to Dataset
You can access the dataset [here](https://www.kaggle.com/datasets/wenruliu/adult-income-dataset).

