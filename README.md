# Nashville Housing Data Cleaning Project

This project demonstrates the complete data cleaning process for the Nashville Housing dataset using SQL Server.  
The main objective was to transform raw housing data into a clean, structured, and analysis-ready dataset by applying different SQL data cleaning techniques.

---

## Project Description

Real-world datasets often contain missing values, duplicate records, inconsistent formatting, and unstructured data.  
In this project, I used SQL to clean and prepare housing data for future reporting, visualization, and analysis.

The cleaning process focused on improving:
- Data accuracy
- Consistency
- Readability
- Usability for analysis

---

## Technologies Used

- Microsoft SQL Server
- SQL

The dataset contains housing sales information including:
- Property addresses
- Owner information
- Sale dates
- Property values
- Tax district details


## Data Cleaning Process

## Standardized Date Format
Converted the sale date column into a consistent SQL date format to improve accuracy and usability.

## Handled Missing Values
Populated missing property addresses using self joins and matching Parcel IDs.

## Split Complex Columns
Separated combined address columns into individual fields such as:
- Address
- City
- State

This improves readability and makes filtering easier.

## Standardized Data Values
Cleaned inconsistent categorical values in the `SoldAsVacant` column by converting:
- `Y` → `Yes`
- `N` → `No`

## Improved Data Structure
Added and updated columns to create a cleaner and more organized dataset.

---

## SQL Skills Demonstrated

- Data Cleaning
- Data Transformation
- Joins
- Common Table Expressions (CTEs)
- String Functions
- Handling NULL Values
- Data Standardization
- Column Manipulation
- Query Optimization

---

## Project File

- `Datacleaning project.sql` → Contains all SQL queries used throughout the cleaning process.

---

## Project Outcome

After completing the cleaning process, the dataset became:
- More consistent
- Easier to analyze
- Better structured for dashboards and reporting
- Ready for further data analysis projects
