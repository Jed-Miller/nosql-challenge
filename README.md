# Nosql Challenge

## Database and Jupyter Notebook Set-Up

After importing the establishments.json file from my terminal and creating the database (uk_food) and collection (establishments), I created an instance of MondoDB to check that my database was ready to use. Once confirmed, I set 'establishments' into a variable to use throughout the rest of the project.

## Update the Database

First, I added Penang Flavours, a new Halal restaurant, to the database, updating it's business type id. Next, we removed unwatned establishments from the database and updated the datatype of some of the columns.

## Exploratory Analysis

Once the databases had been updated and were ready for analysis, I ran queries for these questions (presenting the results in dataframe format)

    1. Which establishments have a hygiene score equal to 20?
    2. Which establishments in London have a RatingValue greater than or equal to 4?
    3. What are the top 5 establishments with a RatingValue of 5, sorted by lowest hygiene score, nearest to the new restaurant added,  "Penang Flavours"?
    4. How many establishments in each Local Authority area have a hygiene score of 0? Sort the results from highest to lowest, and print out the top ten local authority areas.
