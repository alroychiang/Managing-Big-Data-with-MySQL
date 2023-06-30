## Managing-Big-Data-with-MySQL
This course was completed on Coursera in my free time as I aim to practise and understand SQL syntax more in-depthly. 
The files in this repository are practise questions that allowed me to generate queries from scratch to extract the relevant data or generate the required table of data to satisfy the business query. The database used is from a company called Dognition with different breeds of dogs that performed behavioural tests to categorize or label them with a personality trait. The data consists of dog IDs, location, gender, test completed, date-time and many more parameters that the company and pet owners use to track their dog's performance better.

### Excercise 1
Using Jupyter Labs, we use SQL library each time we generate a query. We connect to Dognition's Database with %sql mysql://studentuser:studentpw@mysqlserver/dognitiondb and start practising SHOW, DESCRIBE, SELECT, FROM and LIMIT clauses.

### Excercise 2
In this excercise we begin WHERE, IN, NULL, LIKE, YEAR, MONTH clauses. Additionally, operators like -, +, <, = are introduced and practised as well.

### Excercise 3
Excercise 3 focuses on DISTINCT, ORDER BY, DESC, ASC, IS NOT, AND, REPLACE, adn TRIM. This excercise helps us remove certain characters off values within our tables with TRIM and arrange our exclusive data with DISTINCT, DESC, ASC and ORDER BY.

### Excercise 4
For excercise 4 we touch on the COUNT function to identify the number of rows under a selected column. We also used SUM to identify null values. AVG, MIN, MAX, TIMESTAMPDIFF statistical functions are used to analyze certains columns in a table.

### Excercise 5
The GROUP BY clause is studied in-depthly here where values under a selected column can be clustered together and sorted ascendingly or descendingly (alphabetically or numerically).

### Excercise 7
For excercise 7, we touch on INNER JOINs clause. Combining with clauses like HAVING, ORDER BY and WHERE, we properly map the rows and columns together between two tables so that we end up with a common table of unique information to exatract insights from. We also are taught about the Cartesian product problem in relational databases prompting the database to forcefully duplicate and combine every row from the two tables together if there isnt a query telling the database how the two queries are related. 

### Exercise 8
Here, outer joins (left and right joins) have to be properly ordered when calling the clauses in order to retain the appropriate rows of interest when the table is produced. We also touch on how to extract all columns and rows of a table using '\*' and WHERE clauses. ALways look at samepl outputs of my queiries before strongly interpreting aggregated calculations, especially when joins are used.

### Excercise 9
Excercise 9 focuses on subqueries and derived tables to isolate each logical part of a statement which is better for troubleshooting long and complicated queries. We are able to generate small portions off table A to compare with table B for assessing whether groups or rows are members of other groups or rows. This may speed up the processing time compared to JOIN clauses. All inner most subqueries are executed first, extending out towards the outer most subquery.

### Excercise 10
We practised nested IF statements within the SELECT clause to display selected rows of data. The CASE clause is a more compact representation of multiple IF statements that provides the same functionality to group and extract rows that fufill the match case keyword. Subsequently, we incorportate logical expressions such as >=, <=, !=, AND, OR, and NOT that filters the table even more. The order of these logical expressions (if no parenthesis used) are important as NOT, AND, OR operators are executed with priority as stated respectively.

### Excercise 11
Excercise 11 touches on Analysis Planning to help address questions that are relevant to a business' objectives quickly and efficiently. Structured Pyramid Analysis Plan is a specific, measurable, attainable, relevant and time-bound perspective of the general project's objective. The excercise questions here are rigourous in manipulating the existing data and extracting only a custom, unique, important information off to address the business' objective E.g Assessing if a Dog's personality trait (playful, aggressive, sociable) are linked to the number of tests/challenges the Dog would complete. This question is then broken down into smaller questions (E.g What are the different kinds of personality traits, what are the different kinds of challenges in the data base) which would require even more queries to address these questions. 

### Excercise 12
For the last excercise, we practised querying the number of tests dogs completed on each day of the week, practised extracting the days of the week from timestamps, used CASE clauses for more descriptive outputs, sorting the results, handle duplicate rows, retreiveing distinct values and joining tables to exclude falgged entries. Finally we focus on analyzing the trends of completed tests on each weekday across different years in the database, adjusting the time_stamps to account for time zone differences.


## Certificate
![Duke Certificate](https://github.com/alroychiang/Managing-Big-Data-with-MySQL/blob/main/Managing%20Big%20Data%20with%20MySQL%20Certificate-1.png)
