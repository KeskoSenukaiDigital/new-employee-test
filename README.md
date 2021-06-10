# Tasks

1.	Create SQL query which will select all possible address object type values for given address object type
2.	Create SQL query which will select all possible delivery addresses for pickup point delivery types
3.	Create PHP class or function which will create and edit user inputted address
4.	Create SQL query which will select address display values where each address object type is row. For example: 

Type | Value
--- | --- 
City | Rīga
Street | Mūkusalas

5.	Create PHP class or function which will build Full Address for inputted address.
6.	Create SQL query which will select delivery fee for delivery type, order amount, order weight and for specific address type value
7.	Change delivery fee configuration so that DPD delivery for Riga will be 5 EUR cheaper than current delivery fee for DPD
8.	Change delivery fee configuration for extra 3 EUR charge for deliveries on Saturday
9.	Create SQL query to retrieve Pickup Point count for Omniva grouped by city
10.	Create delivery fee configuration for delivery to Lithuania shipped by DPD with fee 10 EUR if order weight is less than 10kg and 20 EUR otherwise
11.	Create SQL which will normalize phone numbers by removing country code. Country code is predefined 371
12.	Eliminate normalized phone number duplicates in table contacts. Leave most recent contact (sorting by ID Desc)
13. Assume you have orders table and there is a requirement to generate unique order numbers which can’t have gaps. Create needed database structures and PHP class or function to generate unique order numbers without gaps
