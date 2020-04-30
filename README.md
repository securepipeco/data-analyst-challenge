Hey!

We've come up with 3 not-so-hard tasks to check your skills in Python, SQL and Tableau.
These tasks are aligned with some of our Namaste workflows.

You can add the solutions to the tasks in a public repository of your choice, or send us a .zip file.

## Scope and Preparation
Namaste Technologies sells cannabis online via their e-commerce Shopify platform, CannMart.
In order to fulfill their reporting requirements, the Namaste Finance department asks you to create a report so they can process their Q1 financial results.
This exercise is a simplified view, focused on the Shopify orders.

Because extracting the orders from Shopify may take some time to implement, we are providing you with a dump of orders made in Q1. 

**Your goal:** provide a dashboard to the Finance department about the sales results for Q1.

Don't worry, we will guide you through the steps.

The dump we are providing you is a JSON object that contains orders, following this structure:
* Order ID
* Customer ID
* Customer name
* Customer email
* Order price
* For each line item:
  * ID
  * Product ID
  * Product SKU
  * Price

## Task 1: Exchange Rate Consolidation
In your first task, we would like you to consolidate your orders with the exchange rate, so orders prices can be unified in CAD, the currency that the Finance department of Namaste uses to report on.

For this purpose, we are proposing you to use the free currency rate exchange available here: https://exchangeratesapi.io/

Implement a Python script that loads the data provided, integrate with the Exchange Rate API, so each order contains a "currency rate" property to CAD.

## Task 2: SQL Tables Creation
In this task, we would like you to prepare the reporting to the Finance department: we would like you to upload the data you obtained to a SQL database of your choice (SQLite, MySQL, PostgreSQL, etc.). 

- Create the right data model for your data
- Create the SQL tables
- Import your data

The outcome of this task is to provide a SQL dump / backup / a list of SQL statements.

## Task 3: Reporting
Finally, this task focuses on the data reporting.

Namaste Technologies uses Tableau to create reports for the Finance department.
We are also expecting that you can create a dashboard in Tableau, so you will be able to maintain our existing dashboards and create new ones.

In this context, we would like you to create a public dashboard on https://public.tableau.com/en-us/s/download

Plug the data you have been creating beforehand, and use your knowledge about e-commerce services to provide our financial department with relevant metrics regarding Q1. You're intentionally free to present any metrics you think could be interesting for the Finance department.

The outcome of this task will be a link to your dashboard.

## Outcome
Package the solutions to the 3 tasks in your repository or in a ZIP and send it to us.

Thank you!
