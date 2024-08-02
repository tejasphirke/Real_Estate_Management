# Real Estate Management

## Introduction
This dashboard was designed and analyzed using Microsoft PowerBI to provide users with a comprehensive view of real estate data, including information on properties, location, and costs. The dashboard includes interactive visualizations and charts that allow users to explore the data in a user-friendly format.

## Dataset
The dataset was taken from Kaggle and it contains various attributes such as Id, Property Location, price, bedrooms, sqft_living,floors, waterfront, yr_built, yr_renovated, lat, long.

Created few columns:
1. Waterfront column: It shows whether house has waterfront view or not
2. Modified Condition column: To know the condition of house based on 0 - very good, 1 - good, 2 - bad.
3. Renovated column: Whether the it is new or renovated based on columns yr_built and yr_renovated.

Overview:

- Connecticut, California, Arizona, Florida have good quality properties. Connecticut have bad properties as well but Florida has least.
- There is only 1% houses with waterfront views which is around 163.
- The majority of demand is particularly for 3 bedrooms which is around 9824 followed by 4 bedrooms with 6882. 
- Around 11k have been renovated which corresponds to 52% of total properties. While 48% are not renovated.
- In the plot properties by year built, Earlier there were more properties built as compared to now. Between 2010 and 2022 there is just one spike where more properties were built. However, before 2010 there are more properties built. 

## Visualization
![image](https://github.com/user-attachments/assets/3ba2104a-5d4d-40a6-9482-b7e28adaf0d2)
![image](https://github.com/user-attachments/assets/2ce2cfa5-619d-4f7a-a5ef-d25d62fa799d)

