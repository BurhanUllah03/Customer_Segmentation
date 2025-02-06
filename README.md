
# 🛒 Mall Customer Segmentation

Customer segmentation is a powerful approach to understanding diverse consumer groups and optimizing business strategies. The Turkey Shopping Malls dataset provides a glimpse into consumer behavior across different retail categories and shopping malls in Turkey. With details such as invoice numbers, customer demographics, product categories, payment methods, and purchase dates, this dataset is ideal for exploring shopping trends and customer preferences. 

It offers insights into purchasing patterns, such as how age, gender, and payment methods impact spending habits across various malls like Emaar Square Mall and the Mall of Istanbul. By analyzing this data, businesses can better understand their customers, optimize product offerings, and enhance marketing strategies. 

Effective segmentation helps businesses design personalized marketing campaigns, optimize inventory, and improve customer experiences.


## 🎯Objective of the Project

The primary aim of this project is to analyze the shopping behavior of customers in Turkey’s shopping malls to uncover meaningful insights that drive business decisions. 

Key objectives include:

- Examining shopping distribution patterns based on gender and age to identify demographic preferences.
- Identifying which gender and age groups contribute most to product sales and revenue generation.
- Analyzing the distribution of purchase categories in relation to demographics, payment methods, and shopping malls to understand customer preferences.
- Exploring the relationship between payment methods and other variables to identify trends in consumer behavior.
- Providing actionable insights to help businesses optimize marketing strategies, improve inventory management, and enhance customer satisfaction.

This analysis aims to assist businesses in tailoring their offerings and strategies for targeted customer segments, ultimately driving profitability and customer engagement.

## 🔎 Attribute_ information

About Dataset: 

This dataset contains shopping information from 10 different shopping malls between 2021 and 2023. We have gathered data from various age groups and genders to provide a comprehensive view of shopping habits in Istanbul. The dataset includes essential information such as invoice numbers, customer IDs, age, gender, payment methods, product categories, quantity, price, order dates, and shopping mall locations.


- invoice_no: A combination of the letter 'I' and a 6-digit integer uniquely assigned to each operation. 
- customer_id: A combination of the letter 'C' and a 6-digit integer uniquely assigned to each operation. 
- gender: String variable of the customer's gender. 
- age: Positive Integer variable of the customers age. 
- category: String variable of the category of the purchased product. 
- quantity: The quantities of each product (item) per transaction. 
- price: Product price per unit in Turkish Liras (TL). 
- payment_method: String variable of the payment method (cash, credit card or debit card) used for the transaction.
- invoice_date: The day when a transaction was generated. 
- shopping_mall: String variable of the name of the shopping mall where the transaction was made.

## 📝 Tasks to Perform

Q1  : How is the shopping distribution according to gender?

 Q2  : Which gender did we sell more products to?

 Q3  : Which gender generated more revenue?

 Q4  : Distribution of purchase categories relative to other columns

  Q5  : How is the shopping distribution according to age?


  Q6  : Which age cat did we sell more products to?


  Q7  : Which age cat generated more revenue?

Q8  : Does the payment method have a relation with other columns?


  Q9  : How is the distribution of the payment method?







## 📝 Steps followed 

**(a)Loading the data in Power BI** : Load data into Power BI Desktop, dataset is a csv file. Click on "Transform Data"

**(b)Data profiling in Power Query** : Open Power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.

**(c)Results Observed** : Analyzed the columns and their distribution, found that

*   A total of 99,458 transactions were processed with no duplicate records found.
*   **Transaction Volume and Uniqueness:** A total of 99,458 unique transactions were processed, with no duplicate records identified.
*   **Unique Identifiers:** All `invoice_no` and `customer_id` records are unique.
*   **Gender Distribution:** The `gender` column contains only "Male" and "Female" values.
*   **Customer Age Range:** Customer ages range from 18 to 69 years old.
*   **Product Categories:** There are 8 product categories: Books, Clothing, Cosmetics, Food & Beverages, Shoes, Souvenir, Toys, and Technology.  (Note: You listed "books" twice; I've assumed this was unintentional.)
*   **Invoice Date Formatting:** The `invoice_date` column had inconsistent formatting.  These dates were standardized to the D/MM/YYYY format.
*   **Transaction Date Range:** Transactions span from January 2020 to March 2023.
*   **Shopping Malls:**  The `shopping_mall` column includes data from 10 distinct shopping malls.

**(c)Solving questions provided through visuals**
![Image](https://github.com/user-attachments/assets/37414b59-b437-45e8-aa0c-bf6910cafb93)

![Image](https://github.com/user-attachments/assets/b1b42051-ccd9-4b5a-be30-9203c45d4b3f)

