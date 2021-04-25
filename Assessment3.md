## Assessment 3

This assessment is designed to give you exposure to the real-world environment of business analytics and stimulate your creativity as well as your ability to research and 
solve business problems. 

In a group of 2, you are required to investigate the dataset and create a business scenario, including questions that can help management to resolve business issues. 
You use the dataset to develop and evaluate models and develop a business case solution to address the identified questions and underlying problems.
You are asked to present this solution to the management to present them with options to resolve the addressed business problem.
 
**Packages to use:**
`tidyverse`

**What to submit:**

1. Written report as a `.rmd` document that clearly shows all steps in data wrangling, data viz, modeling and model assessment.
2. Video presentation to stakeholders and supporting slides. Slides can be done in PowerPoint or using R tools (e.g. [`xaringam package`](https://bookdown.org/yihui/rmarkdown/xaringan.html)

**List of datasets to choose:**


The data provided are the sales records of a retail business in February 2021. These data were extracted from different systems therefore they are in different formats:

pc.json: A JSON dataset extracted from the ERP system which contains the product categories
orders.csv: Order information including customer names and shipping addresses in the duration
order_details.csv: The details of orders
Examine the datasets to understand what data you have and what their information they have. Then, write Python programs to find out the facts required by the management as listed below.



### Questions
Based on the freights spent on these orders, please estimate the budget of monthly freights for this business.
Try to find the countries with the most orders, which implies the strong markets that the business should focus on.
The business wants to reward customers who buy frequently by rewarding them with discount coupons. Find 3 customers who have the highest number of orders in the dataset.
Which product category has the highest sales revenue? These products are popular and there may be implications for business operations. (Note: The total sales of a product is the sum of the values of unit price * quantity in all relevant orders. The sales of a product category are the sum of the total sales of the products in the category.)

### Requirements
(For Q4) You need to match the product category ID to its name using a program. Merely reporting the product category ID is not acceptable.
The facts should be outputted to the screen in a format of your discretion, however it should be clear and understandable.
Organise your code logically in multiple code files so that other business analysts can understand your code.
