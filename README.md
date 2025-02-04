# Bike_Buyers

# Introduction
As part of assessment in the Data Analytics class organized by PSP_Analytics, one of the analytics projects I’ll be working on is the Bike Sales Dataset. The Bike Sales Dataset contains the ID, Marital Status, Gender, Income, Children, Education, Occupation, Home Owner, Cars, Commute Distance, Region, Age and Purchased Bike. The goal of this work is to:
  ✓ Create a new Excel file, and include four sheets labelled: Aggregate Functions, Text Functions and Logical Functions
  ✓ Each sheet will contain specific types of Excel functions to analyze the dataset.
  ✓ Include the functions in new columns beside the original dataset and label each operation.
  
# Data Sourcing
This dataset used in this work is gotten from the Data Analytics Class announcement channel, which was posted by Mr. Kingsley Adisa.

# Data Preparation
We will load the data into MS Excel.

![IMG_20250204_114415](https://github.com/user-attachments/assets/3faa8866-0551-485a-9daf-e85012ea2df0)


# Data Cleaning/Transformation
Here, we check if the format of each column is correct and correct it were necessary. We also address inconsistencies in the columns to ensure a more accurate dataset for analysis

# Data Analysis/Visualization
We are to use the Bike_buyers dataset to answer the following questions:

1. Aggregate Functions: You are required to use aggregate functions to perform calculations on the
`Income` column of the dataset. For each task, insert a new column as needed and perform the
following:
  a. Use the `SUM` function to calculate the total income from all customers.

   ![sum](https://github.com/user-attachments/assets/4f16d924-74d8-46a2-a472-69fa0f5b0f59)


  b. Use the `AVERAGE` function to find the average income of customers.

   ![average](https://github.com/user-attachments/assets/074f667b-7677-41c3-bfff-983d5d182674)

  c. Use the `MAX` function to identify the maximum income.

   ![max](https://github.com/user-attachments/assets/4a78779a-caaf-44d4-be36-d8ad5925a5e4)

  d. Use the `MIN` function to find the minimum income.

   ![min](https://github.com/user-attachments/assets/90a3239e-8af9-47bd-9d50-23d77e22477c)

  e. Use the `COUNT` function to count how many income values are available (non-blank).

   ![count](https://github.com/user-attachments/assets/61e7194a-2bef-4bf4-b9bd-e1b2e559f557)

3. Text Functions: Use text functions to manipulate data in the Customer Name and Customer ID
columns.
  a. Use the `LEFT` function to extract the first 2 characters from the Customer ID column.
  b. Use the `RIGHT` function to extract the last 3 characters of the Customer Name column.
  c. Use the `LEN` function to find the length of each name in the Customer Name column.

  ![text](https://github.com/user-attachments/assets/f7f21e61-308f-43e1-84a8-22eb50172ef7)

        
  d. Use the `CONCAT` function (or `TEXTJOIN` if preferred) to combine the Customer Name and
  Customer ID into a single column with the format "Customer Name – Customer ID".

   ![concat](https://github.com/user-attachments/assets/311faf16-00b9-42d1-97f1-20fb88da1201)

  e. Use the `TRIM` function to remove any leading or trailing spaces in the Customer Name
column.

   ![trim](https://github.com/user-attachments/assets/97d5783a-83e7-4ab6-970b-85f58c74beab)

4. Logical Functions: Use logical functions to analyze and perform conditional operations based on
the data.
  a. Use the `IF` function to create a new column labeled "High Income", where customers with an income above $50,000 are marked as “Yes” and those below are marked as “No.”

     ![high income](https://github.com/user-attachments/assets/68a62f21-defb-4ce3-8f64-98febbfddd86)

  b. Use the `SUMIF` function to calculate the total Income for customers who are married (i.e M).

   ![and](https://github.com/user-attachments/assets/977398f5-e96a-4547-8658-b5ea6d6cf975)

  c. Use the `COUNTIF` function to count how many customers have an income greater than $50,000.

   ![countif](https://github.com/user-attachments/assets/890a24e5-c300-40bb-ac98-4c2ad07a46d2)


  d. In a new column named “Age Bracket”, Use the `IFS` function to classify customers age into categories:
  - Adolescents (0-30),
  - Middle age (31-54), and
  - Old (55+)
  - 
     ![age](https://github.com/user-attachments/assets/bd08925f-61eb-4f30-98eb-d15a620aa67c)

  e. Use the `AND` function to create a new column that checks if a customer’s income is greater than $50,000 and their age is greater than 30.

   ![sumif](https://github.com/user-attachments/assets/797ce99e-7444-49bf-ad61-450ca2f4d430)

# Conclusion

![image](https://github.com/user-attachments/assets/114e7331-e48f-4c4b-80f8-a82af7c92827)
