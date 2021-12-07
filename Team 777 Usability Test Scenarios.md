# Zipped project: #

Our zipped versions of our GUI and CLI are located at:

https://github.com/Stackeduary/SE2021

They work and have been tested on multiple computers.


# Task 1 #

Our usability requirements from Lab 1 were weak, so we have rewritten two of them for the purposes of this lab.

UR-1:

Using our application's GUI, at least two out of three users will be able to enter a product's barcode, quantity, name and price into the form fields for these four values and add the product to their cart without needing a help menu or user guide. That is, our form is designed in an intuitive, easy-to-use way such that at most one out of three users will be unable to add a product to their cart without assistance from a help menu, user guide or another user guiding them.

User story 1:

As a new cashier using the POS system, I want to add a product to a customer's shopping cart without needing to consult a help menu or user guide so I can serve customers quickly and do my job well.

Usability test 1:

- Tasks:

 -- Open the application

 -- Navigate to the "Point-of-sale" tab

 -- Locate and click on the "New Purchase" button

 -- Navigate to and enter the product's barcode and quantity; the product's name and price should populate in the form automatically

 -- Locate and click on the "Add to cart" button

 -- Ensure that the product has been added to the cart by checking the shopping cart pane at the bottom half of the window and verify that the correct product name, barcode, quantity and price have been added to the cart

- The problem is whether the POS user can easily read and navigate the point-of-sale interface and identify which buttons to click in the user interface to perform the desired action of adding a product to the shopping cart

- Start condition: the point-of-sale user has the POS system application open and running and has a product barcode with a positive quantity in the warehouse to enter (i.e., there are products in the store's inventory that the cashier can actually sell); the point-of-sale user has a working keyboard, mouse and computer screen

- End condition: the desired product has been added to the shopping cart and the quantity of the item sold has been deducted from the store's inventory

- This task shall be completed within three seconds after the product's barcode has been identified

- This test applies to the GUI


UR-2:

Using our application GUI, at least two out of three users will find the text size of the application readable and the colors of the interface readable and easy to use. There shall not be more than one out of every three cases where a user cannot see the buttons or form fields due to the color scheme of the menu or cannot read the text due to its small size.

User story 2:

As a warehouse manager using the POS system, I want to be able to read the text of the menu easily and easily see what buttons I have to click in order to add a product to the warehouse quickly so I can do my job efficiently without straining my eyes or entering information in the wrong fields or clicking on the wrong button.

Usability test 2:

- Tasks:

 -- Open the application

 -- Locate, read the text of and navigate to the "Warehouse" tab

 -- Verify that the user can locate and read the text labels on the following buttons in the menu: 

    -- "Add product"

    -- "Delete product"

    -- "Change"

    -- "Out of stock"

    -- "Confirm"

    -- "Cancel"

    -- "Update"

 -- Verify that the user can locate and read the labels of the following form fields in the menu: 

    -- "Bar Code:"

    -- "Amount:"

    -- "Name:"

    -- "Price:"

 -- Verify that the user can locate and read the labels of the following column headers in the warehouse menu: 

    -- "Id"

    -- "Name"

    -- "Price"

    -- "Quantity"

 -- Click on the "Add product" button

 -- Enter the product's barcode, quantity name and price

 -- Click on the "Confirm" button

 -- Ensure that the product has been added to the warehouse

- The problem is whether the warehouse manager can readily read the text of the menu and clearly identify the buttons he/she must click to perform the desired action of adding a product to the warehouse

- Start condition: the warehouse manager has the POS system application open and running and has a product barcode and a predetermined positive quantity to add to the warehouse (i.e., there are products physically in the store's possession that have not yet been added to the warehouse); the warehouse manager has a working keyboard, mouse and computer screen

- End condition: the desired product has been added to the warehouse and the quantity is positive and correct; the name, barcode and price are correctly entered

- This task shall be completed within three seconds after the product's barcode has been identified

- This test applies to the GUI
