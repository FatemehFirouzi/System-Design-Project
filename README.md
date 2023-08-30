# System-Design-Project 
Project Description: Design and Implement a software system, using the Python programming principles and methods for a car Interiors company to improve its current bonus payment structure by specifically taking two actions- 1. Automate the bonus calculation process 2. Incentivize the sale sources by developing a robust and competitive dynamic bonus payment plan.
## Introduction
Welcome to the System-Design-Project repository. This project represents the culmination of my efforts in creating a new sales bonus plan automation system using Python. The primary goal of this endeavor is to provide a comprehensive solution that addresses the shortcomings associated with conventional sales bonus calculation and management methods.

Modern companies face a slew of challenges within their sales departments, such as heightened competition, rapid turnover rates, deficient self-tracking and communication tools, and the cumbersome nature of manual data submission and validation. The innovative system I've developed encompasses four distinct databases, each serving a crucial role:

Buys Database: Stores essential information regarding product purchases, including product ID, price, quantity, date, and user ID.
Sales Database: Contains details about sales transactions, encompassing product ID, price, quantity, date, and user ID.
Products Database: Houses information pertaining to available products, chiefly product ID and quantity.
Users Database: Captures essential details about the salesforce employees, including user ID, password, and name.
In conjunction with this textual description, I've uploaded the relevant Python codes to this repository. Additionally, to facilitate a deeper understanding of the system's logic flow, I've provided four visual diagrams depicting the new bonus plan's operational logic.

The bonus payment structure of Smart Car Interiors LLC. hinges on two vital sources:
In-House Sales Team: This salaried team constitutes the first source of sales.
Car Dealership Referrals: The second source involves referrals from partnering car dealerships.
Central to the new system is the assignment of distinct user IDs to both in-house sales team members and dealerships. Each entity possesses its own personalized portal within the system. The project's initial phase involves granting salesforce employees access to their individual pages, enabling them to input their sales and purchase data. Similarly, designated personnel within dealerships input referral data, operating under their unique user IDs.

For every sales and purchase transaction, each salesforce member must enter four essential variables: productID, price, quantity, and date. This data is entered daily via the new system, serving as the foundation of the "Bonus Plan."

Importantly, the system empowers salesforce employees to track their performance metrics, thereby maintaining their motivation and engagement.

The heart of our new system consists of four meticulously designed databases:

Buys Database: Stores product_id, price, quantity, date, and user_id related to purchases.
Sales Database: Holds product_id, price, quantity, date, and user_id linked to sales.
Products Database: Contains product_id and quantity information.
Users Database: Houses crucial information about salesforce members, including user ID, password, and name.
These databases collectively ensure efficient tracking of product sales. Regular updates keep these databases synchronized with the evolving processes.

Another key component is the Finance Menu, providing access to finance department personnel and executives. With data readily available from the sales department, these individuals can access statistics and bonus calculator reports, streamlining decision-making.

The bonus plan itself integrates a flat rate bonus tied to individual annual sales, coupled with an incremental bonus based on projected profit margins. Additionally, the program offers comprehensive statistical insights into products, users, and annual comparisons via an intuitive dashboard.

Finance Main Menu:
'c': Bonus Calculator
's': Statistics
'b': Back

In conclusion, the user management aspect is encapsulated in a separate flowchart. Users are presented with a menu of options, including:
'a': Add User
'r': Remove User
'p': Update User Password
'n': Update Username
'b': Back
These options empower users to efficiently manage user accounts within the system, enhancing overall usability and security.

Thank you for exploring this project repository. Feel free to delve into the code and diagrams to gain a comprehensive understanding of this innovative sales bonus plan automation system.
