# Final Project: Infectious Cases Data Analysis

## Overview

This project focuses on importing, normalizing, and analyzing infectious disease data using PostgreSQL.

The dataset `infectious_cases.csv` contains yearly data on infectious diseases across different countries and regions.

## Technologies

- Python
- Google Colab
- PostgreSQL
- SQLAlchemy
- Pandas

## Database Design

The data is stored in the `pandemic` schema.

The database contains three main tables:

- `infectious_cases` — the original dataset imported from the CSV file.
- `entities` — unique entities and their codes.
- `infectious_cases_normalized` — yearly disease data linked to entities through a foreign key.

The data was normalized to reduce duplication and establish relationships between tables.

## Tasks Completed

1. Imported the CSV dataset into PostgreSQL.
2. Created a normalized database structure.
3. Calculated average, minimum, maximum, and total rabies cases for each entity.
4. Created date calculations using PostgreSQL date functions.
5. Created and tested two SQL functions:
   - `year_difference()` — calculates the number of complete years since January 1 of a given year.
   - `average_cases()` — divides a disease count by a specified divisor.
6. Tested the functions using different values and SQL queries.

## Project Files

- Google Colab notebook — SQL queries, execution results, and analysis.
- `README.md` — project description.

## Conclusion

This project demonstrates practical experience with PostgreSQL, database normalization, aggregation queries, date functions, and user-defined SQL functions.
