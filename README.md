# FUFU_REPUBLIC_DATA_MODELLING_PROJECT
Overview
Fufu Republic is a restaurant chain with nationwide outlets in Nigeria. The chain faces challenges in inventory management, customer experience, and sales tracking. This project aims to create a data model to support data-driven decisions.

Project Objective
Understand sales trends by location, payment methods, and dining options.
Optimize stock levels, minimizing waste and ensuring availability.
Enhance the customer experience by analyzing purchasing behavior and tailoring promotions.

Business Process
The project focuses on Sales Management to answer:

Which branches and menu items perform best?
How do sales vary by dining option (dine-in, take-out, online) and payment method?
How can inventory be better managed across different locations?

Fact Table: FactSales
Captures transaction data such as sales amount, quantity sold, and relevant IDs for branches, payment methods, and menu items.

Dimension Tables
BranchLocation: Tracks branch details.
PaymentMethod: Stores payment method types.
DiningOption: Categorizes transactions by dining mode.
Menu: Contains menu item details like name, price, and category.
Customer: Stores customer details for loyalty and behavior tracking.
Date: Tracks transaction date and time information.

Key Metrics
Total sales and items sold by branch, menu item, and payment method.
Inventory turnover and waste.
Customer purchasing patterns.
