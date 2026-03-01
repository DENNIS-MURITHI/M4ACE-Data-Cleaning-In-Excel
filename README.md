# Data Cleaning

## Overview

This project focuses on cleaning and structuring a raw employee dataset
to prepare it for analysis. The original dataset contained formatting
inconsistencies, extra spaces, mixed data types, and structural issues.

## Data Issues Identified

-   Extra spaces in text fields\
-   Combined name field (Last Name, First Name)\
-   Inconsistent department naming (e.g., MKTG, R & D)\
-   Mixed date and numeric values in the same column\
-   Potential duplicate records\
-   Irregular formatting

## Cleaning Steps Performed

1.  Split semicolon-delimited data using Text to Columns\
2.  Removed leading and trailing spaces using TRIM()\
3.  Separated first and last names using LEFT(), MID(), and FIND()\
4.  Standardized department names for consistency\
5.  Converted salary to numeric format and corrected date formatting\
6.  Removed duplicate records\
7.  Applied sorting and filtering for structured review\
8.  Converted formulas to values using Paste Special → Values

## Final Dataset Structure

| First Name \| Last Name \| Hire Date \| Salary \| Department \|
  Position \|

The dataset is now clean, consistent, and ready for analysis or
reporting.
