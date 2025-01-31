# **Coffee Sales Analysis:**

# **1. Introduction:**
# **2. Tools I Used:**
To thoroughly explore the coffee sales dataset, I utilized the capabilities of a range of essential tools:

**1. Excel:**

**2. Git & GitHub:** for sharing my analysis and dashboard.



In the context of coffee sales analysis, the Roast Type column with values L, M, and D typically refers to the roast level of the coffee beans:
L (Light Roast)
M (Medium Roast)
D (Dark Roast)

Coffee type column:
Ara (Arabica)
Rob (Robusta)
Lib (Liberica)
EXC (Excelsa)

A loyalty card is a type of card or card-like program that is offered by a business to its customers. With this card, customers can easily accumulate rewards and unlock exclusive discounts for their purchases.

The row dataset is composed of three sheets (orders, customers, products), so we can depend on one sheet in analysis like a fact table, I will choose the "orders" sheet to fill in all important columns from other sheets (customers, products) to perform a strong analysis.

So, to achieve this we will do a group of steps to make the orders sheet the main (fact) sheet to work with for analysis:

**(1) Create a "Customer Name" column referenced to the customers sheet using XLOOKUP function:**

**(2) Create an "Email" column referenced to the customers sheet using XLOOKUP function:**

**(3) Create a "Coffee Type" column referenced to the products sheet using XLOOKUP function:**

**(4) Create a "Roast Type" column referenced to the products sheet using XLOOKUP function:**

**(5) Create a "Size" column referenced to the products sheet using XLOOKUP function:**

**(6) Create a "Unit Price" column referenced to the products sheet using XLOOKUP function:**

**(7) Create a "Total Sales" column using columns ("Quantity", "Unit Price"):**
Total Sales = Unit Price * Quantity

**(8) Create a "Coffee Type" column to replace short coffee names with full coffee names ("Ara ", "Arabica") - ("Rob", "Robusta") - ("Lib", "Liberica") and ("Exc", "Excelsa"):**

**(9) Create a "Roast Type" column to replace short roast names with full roast names ("L ", "Light") - ("M", "Medium")  and ("D", "Dark"):**


**(10) Change the date format to column "Order Date" into a more clear and month clearer format using the custom format in number format cells:**
yyyyy-mm-dd -> dd-mmm-yyyy

**(11) Change the format of the "Size" column to clear the unit of the size "Kg" to make it more clear using the custom format in number format cells:**
0.5 -> 0.5 Kg

**(12) Change the format of the currency columns ("Unit Price", "Total Sales") into dollar sign ($) using accounting number format in numbers:**
9.95 -> $9.95 	 
19.90 -> $19.90 

**(13) Select all columns and rows and remove duplicated values if exist, using remove duplicates in data tools in data.**

**(14) Format the whole sheet to make it more clear and suitable table using (Ctrl + t) and name it "Orders".**






