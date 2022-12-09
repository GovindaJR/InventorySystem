# Inventory System with Scanner
An inventory managment system with a graphical user interface that is capable of taking input from scanning a barcode. Written in Python using the PyQt5 library and using an SQLite database
The system holds information about products that can be read or deleted. Items are added by scanning a barcode using a wireless phone camera or a webcam as a scanner. 
This project is created for CNT 4104 - Software Proj Comp Networks.

# Proposal
## Problem 
Inventory management refers to the process of storing, ordering, and selling goods and services. It is important, because having too little stock on hand can reduce revenue and having too big of an inventory can reduce sales. All businesses have inventories or items that pertain to ordinary business operations, and it is crucible to be monitoring that inventory. As businesses get larger and larger, their inventories increase and so does the difficulty of tracking their items. Having inaccurate information about the current stock of items can make it difficult to tell when to refill stock or which stock moves well. Knowledge of those metrics are very important when it comes to making business decisions. Improper inventory management can allow for theft and other security issues to affect your business as well. 

Inventory management is a difficult business process to do by hand. It takes time, and if you make a mistake, it could have ripple effects that negatively impact your business for months or years.
## Solution
Having a tool that can assist with inventory management can help with the tracking and management of a business's inventory. Businesses doing inventory by hand or using other archiac methods can be a waste of time and money. Using a software tool can improve efficency and lessen the amount of labor needed for proper inventory management. Accurate knowledge of your inventory can help you make cost-effective decisions when it comes to ordering new products, knowing which products that are consistently low (selling well), and knowing when to order them. Products that don’t sell are essentially losses to your business, so those items could be easily tracked using a software system. 

This software is a simple, easy to use system that allows businesses to manage their inventory. Working with the system can be as easy as just scanning a barcode! The system can record items, and has easy to use searching to allow to maintain up-to-date knowledge on the stock of all of your products. 

You can: 
- Minimize storage costs
- Minimze Losses
- Sell more product

The system can also be modified to interface with other business processes: such as other bookkeeping systems, accounting systems or point-of-sale systems among many others!

The system is an amazing tool that can help solve the issues appear in the inventory management process. 
# Use Case Diagram
![image](https://user-images.githubusercontent.com/62119685/206790516-2ba0d8f0-74e7-4be9-ac89-197458420271.png)


# VCS
This project uses GIT as it's version control system. 

# Programming Practice
This project will follow the Python PEP8 style guidelines. 
<br/>
For more information: https://peps.python.org/pep-0008/

# Backend 
We have desiged the backend of the system, depicted in this ER diagram.
The database was created using SQLite3
<br/>
<br/>
![image](https://user-images.githubusercontent.com/62119685/205520965-f4b3a593-821b-4013-8f88-d11bb4aff244.png)

The UI is capable of reading from and writing to the database. 

# Frontend
The frontend was developed using PyQT5
<br/>
<br/>
The main menu screen takes user input and returns a record of the matching item. The input could be gathered from typing, or by scanning a barcode with an appropriate device. 
Click "Scan" to connect to either a phone or a webcam to use as a barcode scanner

Alternatively, enter a batch number, an ID number, or a product category to search the system. 
<br/>

![Scannerdemo](https://user-images.githubusercontent.com/62119685/205520323-b95f4127-85cc-4e3d-976e-d12fb37445c0.gif)
<br/>
<br/>
Items could be added to the system by searching for an item that does not exist, or clicking "Add Item" on the search results page. You would be directed to this page. Filling out the inputs will allow you to add a new product to the system!

![success](https://user-images.githubusercontent.com/62119685/205520489-d258f84a-1130-4c3f-93b6-04062cb5777a.JPG)
<br/>
<br/>
Below you can see the newly added product being searched for and the results screen showing the product details. 


![addingdemo](https://user-images.githubusercontent.com/62119685/205520525-1a270eae-936d-490c-b7e4-da1df22f526a.gif)

<br/>
<br/>

# Installation: 
1. Have [Python](https://www.python.org/downloads/) installed on your system.
2. Git clone this repo, or download it as a .zip (and extract it).
3. Install all the libraries mentioned in requirements.txt using  `pip install -r requirements.txt`
4. Run "inventoryMain.py"

# How can this software be improved? 
 - Adding a dashboard showing sale statistics relevent to the products. 
 - Creating feature for tracking inventory across different sites
 - Add inventory notifications for when a product is running out of stock, so you can reorder it. 
        

# Authors
Govinda Ramrattan and Jaysson Balbuena
