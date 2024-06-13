# Data

This is a brief summary of what each directory or file contains.

- `/json:` The original JSON files containing the SQL queries which we extracted by writing a python script.

- `/db:` The database dump files to populate the MySQL DB instances locally. This was used to then run the queries and obtain their execution times.

- `/csv:` Extracted queries from the files in `/json`.

- `/runtime:` CSV files containing the measured runtime (in ms) of each query.

- `table_sizes.json:` Contains the size (number of rows) for each table in each database. This is obtained after all the preprocessing and data cleaning is done.
