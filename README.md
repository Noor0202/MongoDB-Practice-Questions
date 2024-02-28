# MongoDB Practice Questions

Welcome to the MongoDB Practice repository! This compilation of MongoDB queries is crafted to enhance your MongoDB proficiency using the Sakila sample database.

## How to Use:

### Download JSON Data:
- Download the Sakila sample database converted to JSON format. This dataset contains three collections mirroring the MySQL Sakila database.

### Import JSON Data into MongoDB:
- After downloading the JSON files, import them into your MongoDB database using the `mongoimport` command.

### Create a Database:
- Use the following query to create a database named "sakila" in MongoDB:

### MongoDB Import Query:
- Use the following `mongoimport` command to import the JSON files into your MongoDB database:
- --mongoimport --file "your file path with extra \ " -d database_name -c collection_name --jsonArray
- --eg - mongoimport --file "C:\\abcd\\efg\\hij\\klm\\nop\\qrst\\uvw\\customers.json" -d sample -c customers --jsonArray


### Explore the Questions:
- Navigate through the questions directory to find a variety of MongoDB practice questions categorized by topics.

### Practice and Learn:
- Execute the queries in your MongoDB environment and analyze the results. Use these exercises to strengthen your understanding of MongoDB concepts.

## Topics Covered:
1. Basic CRUD Operations
2. Querying with find()
3. Filtering with $match
4. Sorting with $sort
5. Aggregation Framework ($group, $project, etc.)
6. Conditional Aggregation with $cond
7. Limiting Results with $limit
8. Skipping Results with $skip
9. Indexing Strategies
10. Text Search
11. Working with Dates and Times
12. Handling Embedded Documents
13. Array Manipulation
14. Indexing for Text Search
15. Field Renaming and Projection
16. Updating Documents
17. Array Operations
18. Index Creation and Management
19. Data Aggregation and Analysis
20. Unique Indexes and Constraints

## Contributions:
Contributions are welcome! If you have interesting MongoDB practice questions or improvements, fork the repository and submit a pull request.

## Disclaimer:
This repository is created for educational purposes, allowing individuals to practice MongoDB queries using the Sakila sample database in JSON format.
