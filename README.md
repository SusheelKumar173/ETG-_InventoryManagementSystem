# ETG-_InventoryManagementSystem
- Creator : G.Susheel Kumar

An inventory management system project that allows user to manage and maintain his/her inventory with ease. The inventory management system has been developed to allow users to add an inventory,enter inventory quantity and other details, update inventory status and more.

# Problem :

One of the major issue for small scale shopkeepers is to keep track of their inventory and sales. Most oftenly they spend a lot of time and efforts to manage their inventory as well as keep record of their sales.

# Introduction:

I have created an Inventory Management System to manage the goods for a small scale shops using the power of python and json. This will save a lot of time and efforts of the shopkeepers and facillitate them in the tedious task of managing inventory and sales.

The project is a JSON Based Inventory Management System. I have divided it in four parts.

  The First part contains a nested dictionary of 39 products with product id as the key and other details like product name, price, expiry date, quantity ,manufacturer date,category as value of each key.Then the dictionary is converted to json file.

  The Second part contain code to display only the product categories.

  The Third Part contains generating bills for the customer purchase,creating a file for Sales and also updating product file after product is sold.

  The Fourth Part contains updating existing products,also updating in product file and adding new Products into the inventory.

# Functionalities and working:

This project is actually divided into 2 files:

<b>1.Adding_Elements_into_Inventory:</b> In this part, We create a records.json file which contains all the Inventories with details like product id(barcode),name,quantity,price,isAvailable,Expiry date. Here we can add new goods in the inventory and the records will be stored in records.json file.

<b>2.Product Purchase:</b> In this part, a)We enter the transaction or purchase details like product id,no. of items purchased,name of customer, mobile number of customer. b)If the purchased items are available in inventory, then Bill is generated c)The detailes of the transactions are then stored in sales.json file with attributes like total transactions,transactio id,date,time, product name,total amount of purchase, customer name and customer mobile number.

# Tools used:

<b>Google Colab</b>
          - Colab notebooks are Jupyter notebooks that run in the cloud and are highly integrated with Google Drive, making them easy to set up, access, and share





