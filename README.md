# Black-Friday-Sales-Analysis

This project analyzes Black Friday sales data to explore customer purchasing behavior across various product categories. The primary goal is to identify trends and patterns in buying behavior, particularly focusing on demographic factors that influence purchasing decisions.

## Dataset
The dataset consists of customer transaction information from Black Friday, including several key features:

User_ID: A unique identifier for each customer.

Product_ID: A unique identifier for each product.

Gender: The gender of the customer (M or F).

Age: The age group of the customer (e.g., 0-17, 26-35, 55+).

Occupation: The occupation code associated with the customer.

City_Category: The category of the city where the customer resides (e.g., A, B, C).

Stay_In_Current_City_Years: The number of years the customer has stayed in their current city.

Marital_Status: The marital status of the customer (0 for single, 1 for married).

Product_Category_1, Product_Category_2, Product_Category_3: Categories to which the purchased products belong.

Purchase: The total amount spent by the customer.

## Approach
I conducted exploratory data analysis (EDA) to visualize customer demographics and purchasing trends. I compared some predictive models: linear regression, random forest, XGBoost, and deep learning, to see which model better understood purchasing behavior.

## Results
The analysis revealed that male customers aged 26-35 were the most frequent buyers during Black Friday. The XGBoost model outperformed the other models in predicting purchases, indicating that it’s the most accurate and reliable for this dataset. Based on these insights, I recommended targeted marketing strategies, such as discounts on popular products for the identified customer segment, and create loyalty programs to enhance sales and improve customer satisfaction.
