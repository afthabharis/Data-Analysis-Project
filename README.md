** INSURANCE DATA ANALYSIS PROJECT **

>> PROBLEM STATEMENT:
An insurance agency, ABC Insurance, has a large dataset containing information about their policyholders and claims.
They want to perform exploratory data analysis (EDA) on this dataset to gain insights that can help them make better
business decisions and improve their operations.

The agency wants to analyze the different body types and the environment that affect the premium. The disease's effect 
or the cost of treatment differs depending on the circumstances. For example, a smoker's medical insurance premium may
be higher than that of a healthy person, because smokers are more likely to develop chronic diseases.The agency wants 
to analyze the data to research healthcare premium costs.

>> OBJECTIVE:
To analyze the dataset that will help to create a model that will predict the cost of medical insurance based on various input features.

>> STEPS PERFROMED:
    1. Importing libraries such as Pandas, matplotlib, NumPy, and seaborn and loaded the insurance dataset.
    2. Checking the shape of the data along with the data types of the column.
    3. Checking for missing values in the dataset.
    4. Exploring the relationship between the feature and target column using a count plot of categorical columns
       and a scatter plot of numerical columns.
    5. Performed data visualization using plots of feature vs feature relationships.
    6. Checking if the number of premium charges for smokers or non-smokers is increasing as they are aging.

>> OBSERVATIONS:
    1. According to Count Plots: The count of policyholders is relatively balanced between genders, with a higher number
       of non-smokers compared to smokers.
    2. According to Scatter Plots: The scatter plot of age vs. charges shows a positive correlation, suggesting that as
       age increases, the insurance charges tend to increase. The BMI vs. charges plot also indicates a similar trend.
    3. According to the Pairplot: The pairplot colored by smoker status shows that smokers tend to have higher insurance
       charges compared to non-smokers across various ages and BMI values.
    4. The boxplot illustrates that smokers generally have higher insurance charges than non-smokers, especially as they age.
       This reinforces the notion that smoking is a significant factor in determining health insurance premiums.

>> CONCLUSION:

  The exploratory data analysis reveals critical insights into the factors affecting healthcare premiums, particularly the impact
  of smoking and age on insurance charges. These insights can inform the development of predictive models to estimate insurance 
  costs based on individual characteristics.
