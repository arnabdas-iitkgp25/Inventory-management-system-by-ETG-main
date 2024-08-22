# Inventory-management-system-by-ETG
This repository has all the code that I have used in building the JSON-based inventory management system using Python for my AI/ML Skill.

This project contains one .ipynb python file and two JSON files.
 1. records.json has the details of the available products.
 2. sales.json has the details of all the sold transactions.
    
The records.json contains the following:->
  1. product_id
  2. name
  3. price
  4. quantity_in_stock
  5. rating
  6. type_of_product
     
 whereas the sales.json contain 
  1. product_id
  2. name
  3. quantity
  4. and amount
 
 When we start working in this system the first it will ask you to choose the tasks you want to perform for the following:-
   1. Add Item- to add a new product to the existing file.
   2. Remove Item- delete the item present in the existing file.
   3. purchasing - to buy the item present in the existing file. If the item is not present or the quantity you want is not present, it will inform you, and once you purchase the item, this will also send you the bill for the shopping and update the data after selling the item.
   4. searching an item- this will help you to search for the item present in the system.
   5. print sales report-it will help you to maintain the sales history.
   6. Quit- exit for the program.
 This is all the function that can be performed by this inventory management system.
