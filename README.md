# SQL Course Compilation
This repository will contain all the practice code for SQL:

- Examples
- Projects
- Queries

## Examples

### Example 1: Selecting data from a table

To select all columns from a table named `employees`, you can use the following SQL query:

```sql
SELECT * FROM employees;
```

### Example 2: Selecting specific columns from a table

```python
import sqlite3
# Create a connection to the database
connection = sqlite3.connect('example.db')
# Create a cursor object
cursor = connection.cursor()
# Execute the query
cursor.execute('SELECT * FROM employees')
# Fetch the results
results = cursor.fetchall()
# Close the connection
connection.close()
# Print the results
print(results)
```

## Projects

## Queries
