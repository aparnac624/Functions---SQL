# Functions--SQL
This README explains the series of SQL operations performed on the Country and Persons tables. The operations include adding a new column, creating a user-defined function, querying for age, and performing string manipulations on the Country table.

Operations Performed :
1. Add a new column called DOB in Persons table with data type as Date
   - The first step is to add a new column DOB (Date of Birth) to the Persons table with the DATE data type.
    
2. Write a user-defined function to calculate age using DOB.
   - Next, we create a user-defined function calculateage that takes the DOB as input and calculates the person's age based on the current date.
     
3. Write a select query to fetch the Age of all persons using the function that has been created.
   - Now that the calculateage function has been created, we can fetch the age of all persons from the Persons table by applying this function to the DOB column.
     
4. Find the length of each country name in the Country table.
   - To find the length of each country name in the Country table, we use the LENGTH() function. This function returns the number of characters in the country name.
     
5. Extract the first three characters of each country's name in the Country table.
   - To extract the first three characters of each country name, we use the LEFT() function.
     
6. Convert all country names to uppercase and lowercase in the Country table.
   - To convert the country names to uppercase and lowercase, we use the UPPER() and LOWER() functions, respectively.


The screenshots of the outputs have been attached for reference. 
