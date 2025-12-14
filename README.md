# Product Data Quality Checks
Basic data quality checks for product-related data using Excel

## Project Overview
This project shows how basic data quality checks can be done in Microsoft Excel for product-related data. The main goal was to check wheter key fields contain correct and consistent values before the data is used in an e-commerce setting.

## Scope of Checks
The following checks were created:
   1. Quantity check (must be integer greater than 0).
   2. Discount rate check (number between 0 and 1).
   3. Product ID format check.
   4. Product ID existence check based on a Products reference table.

## Data Quality Rules
All rules and assumptions are described in the 'data_quality_rules' sheet. This includes:
   1. fields descriptions,
   2. allowed value rangers,
   3. reference data requirements.

## Error Identification
Each check returns an 'OK' or 'ERROR'; result for every record. Conditional formatting is used to make records with errors easier to spot and filter.

## Data Quality Summary
A separate summary shows how many errors were found for each check and what percentage of records they represent.

## Tools Used
1. MS Excel
2. Tables and formulas
3. Lookup and logical functions
4. Conditional formatting

## Notes
The project focused on identifying data issues. Data values are not changed; potential problems are only marked for further review.
