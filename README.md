# Data Engineering Coding Challenges

## Judgment Criteria

- Beauty of the code (beauty lies in the eyes of the beholder)
- Testing strategies
- Basic Engineering principles
- Understanding of data processing concepts in Python

## Problem 1

### Working with dataframes

- Parse and load the `person.csv` and `condition.csv` files in to a dataframe of your choice
- Using a query library that allows you to query dataframes (e.g. [pandasql for pandas](https://pypi.org/project/pandasql/)), write and execute queries for the following:
  - Write SQL to count the number `person` with the diagnosis `E11.9`
  - Write SQL to list the states where patients with the diagnosis `E11.9` are present
  - Select `personId` of `person` with the condition `Chronic kidney disease stage 1`

## Problem 2

### Data processing

- Generate a csv file containing first_name, last_name, address, date_of_birth
- Process the csv file to anonymise the data
- Columns to anonymise are first_name, last_name and address
- Think about how we can run this on a larger file (>4GB)
