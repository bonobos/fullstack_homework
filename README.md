# Background
Your mission is to create a webpage that displays a list of e-commerce products.  We expect it will take 3-4 hours to build this, and you have 1 week to submit your solution.  The reason we do homeworks is so that people can code in their natural environment where they are comfortable.  This way we can rely less on in-person coding during an interview.

# Guidelines
Before starting the homework we recommend reading it in its entirety so that you have a broad understanding of what you're building. You can use any languages, databases and tools you want.
Submit your application on Github with a README file with build instructions, an explanation of the approach you took, and how you could potentially improve it in the future.

## Goal #1: Load the product and inventory data into a database
- Create a database for the data in [products.csv](https://github.com/bonobos/fullstack_homework/blob/master/products.csv) and [inventory.csv](https://github.com/bonobos/fullstack_homework/blob/master/inventory.csv)
  - [products.csv](https://github.com/bonobos/fullstack_homework/blob/master/products.csv) contains a list of products and [inventory.csv](https://github.com/bonobos/fullstack_homework/blob/master/inventory.csv) lists the inventory count for those products in various sizes and styles
- Load the data into a database

## Goal #2: Make an HTTP API for the data
Create an HTTP API to fetch the data you loaded into the database in part 1. The response should be in JSON. Add a test to verify the HTTP API works.

## Goal #3: Make a webpage that displays the data

Call the HTTP API you made for Goal #2 and display a single list of product and inventory data together.  Inventory should be grouped by product.

# Additional goals for senior candidates

The following goals are only applicable to candidates applying for senior positions. The functionality below should be implemented in *addition* to all of the functionality above.

## Goal #4: Closest word search

Implement an HTTP API endpoint that allows you to search for products. When the search term doesn't yield any results, the endpoint should return the closest word match.

Searching for "wish" would return the "washed chinos" product for example.
