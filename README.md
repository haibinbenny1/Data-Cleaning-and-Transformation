# Data-Cleaning-and-Transformation

1. Handling Missing Values:
Missing Price: Replaces missing values in the Price column with the median price of the available products.
Missing Category: Replaces missing category values with "Unknown" when the category cannot be determined.
2. Correcting Inconsistent Data:
Product Name: Standardizes inconsistent capitalization in the Product Name column, such as laptop → Laptop.
Category: Corrects the typo Electroni → Electronics using Replace Values.
3. Removing Duplicates:
Duplicate Rows: Removes rows that have identical values across all columns using Remove Duplicates.
Result: Removes 3 duplicate rows, reducing the dataset from 34 rows to 31 rows.
4. Splitting and Merging Data:
Manufacturing Date: Splits the Product ID using the - delimiter to separate the manufacturing date.
Country Code: Splits the Product ID to extract the country code.
Product Brand: Merges the Brand Name and Product Name columns using a space separator.
Example: Dell + Laptop → Dell Laptop.
5. Number Formatting:
Price: Formats the Price column as Currency ($).
Manufacturing Date: Formats the Manufacturing Date column as DD-MM-YYYY.
Example: 28-01-2026.
6. Conditional Formatting:
Price: Applies Data Bars to the Price column to visually compare product prices.
Electronics: Applies conditional formatting to highlight cells where the Category is "Electronics".
   
