Dataset Summary 

The dataset contains customer records characterized by eleven columns: customer_id, first_name, last_name, email, phone, signup_date, country, age, income, and loyalty_points. The data exhibits significant issues across almost all columns, including missing values, inconsistent formatting, non-standard text entries, and inconsistent casing.

The below images show a detailed analysis of the inconsistencies and messiness of the data. 

<img width="1345" height="597" alt="image" src="https://github.com/user-attachments/assets/60374875-ca65-4a49-8cab-426a35de8799" />
<img width="1346" height="702" alt="image" src="https://github.com/user-attachments/assets/0bfbea46-a7fb-4aee-a0cf-3a0b3b386ba1" />
<img width="960" height="541" alt="image" src="https://github.com/user-attachments/assets/1f6f7e5b-efd8-47aa-8e28-ce3e19548327" />

Data Cleaning Approach

As can be seen from the analysis, the data is incredibly messy. To clean this dataset, I will employ a sytematic ETL approach, cleaning column after column while leaving the original dataset unaltered. This approach will rely heavily on SELECT statements, CASE logic, and built-in SQL functions (TRIM, REPLACE, CAST, date functions) to derive clean values.




