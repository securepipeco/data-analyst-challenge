Hey!

We've come up with 3 tasks to check your skills in Python, SQL and Tableau.
These tasks are aligned with some of our Namaste workflows.

You can add the solutions to the tasks in a public repository of your choice, or send us a .zip file.

## Scope and Preparation
Namaste Technologies sells cannabis online via their e-commerce Shopify platform, CannMart.
To fulfill their reporting requirements, the Namaste Finance department asks you to create a report so they can process their Q1 financial results.
This exercise is a simplified view, focused on the Shopify orders.

Because extracting the orders from Shopify may take some time to implement, we are providing you with a dump of orders made in Q1. 

**Your goal:** provide a dashboard to the Finance department about the sales results for Q1.

Don't worry, we will guide you through the steps.

The dump we are providing you is a JSON array that contains orders, following this structure:
* Order ID
* Customer
	* ID
	* Name
	* Email
* Total Order price
* Creation date
* Line items. For each one:
  * ID
  * Product ID
  * Product SKU
  * Product Name
  * Price

To keep it simple, we removed taxes, discounts. Note also that all prices are in USD (US Dollars).

## Task 1: Python. Data Manipulation and usage of external APIs
In your first task, we would like you to consolidate your orders along with an exchange rate for the date of the order creations. This way, orders prices can be unified in Canadian Dollars (CAD), the currency that the Finance department of Namaste uses to report on.

For this purpose, we suggest you to use the free currency exchange rate API provided by: https://exchangeratesapi.io/

Your task is to implement a Python script that loads the orders, loads the exchange rate on the date of the order (via the Exchange Rate API) so each order contains a "currency rate" property from USD to CAD.

## Task 2: SQL
In this task, we would like you to persist the data obtained from task 1: upload your data to a SQL database of your choice (SQLite, MySQL, PostgreSQL ...).

- Design the right data model for your data
- Create the SQL tables
- Import your data

The outcome of this task is:
- SQL statements to create tables for the data
- A Python script to upload the data (or the one from Task 1, extended)

## Task 3: Reporting
The last task focuses on the results reporting.

Namaste Technologies uses Tableau to create reports for the Finance department.
We are also expecting that you can work with Tableau, so you will be able to maintain our existing dashboards and create new ones.

In this context, we would like you to create a public dashboard using https://public.tableau.com/en-us/s/download

Plug the data you created in the 2 first tasks, and use your knowledge about e-commerce services to provide our financial department with relevant metrics regarding Q1. You're intentionally free to present any metrics you think could be interesting for the Finance department.
Financial numbers should be presented in CAD.

The outcome of this task will be a link to your dashboard.

Thank you!
