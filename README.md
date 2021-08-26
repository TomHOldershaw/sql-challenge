# sql-challenge
SQL Challenge - homework week 9

Contains code for homework week 9 - SQL Challenge

## Main homework
### ERD.png
ERD diagram. Shows tables and columns, with primary keys (including where two columns form a composite key) and links to foreign keys
Column types are defined as the usable type in the database. Two date columns need to be imported as string and converted to date inside the database.

### schema.sql
Scheme for creating database tables, columns, primary keys and foreign keys
Some small edits from the ERD, notably:  
- Composite key defined for table dept_emp  
- Date columns defined as strings for the purposes of creating tables and reading data

### date_columns.sql
Reformats dates and sets column type to date
Required because data is supplied in MDY format, whereas locale (and therefore database default) is DMY

### queries.sql
List of select statements to extract information as stated in homework brief

## Bonus
### Employee_data_analysis.ipynb
Jupyter Notebook containing additional analysis:
- Extract data from database to Pandas dataframes
- Histogram of salary amounts
- Bar chart of average salary by job title
