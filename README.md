# Data-Cleaning-and-Transformation
1. Handling Missing Values:
Missing Price: The missing prices were filled using the median price of the available values.
Missing Category: The missing categories were replaced with "Unknown".
2. Correcting Inconsistent Data:
Product Name: The product names were made consistent by correcting the capitalization, such as laptop to Laptop.
Category: The typo Electroni was changed to Electronics using Replace Values.
3. Removing Duplicates:
Duplicate Rows: Duplicate rows were checked using all the columns and removed.
Result: 3 duplicate rows were removed, so the data was reduced from 34 rows to 31 rows.
4. Splitting and Merging Data:
Manufacturing Date: The Product ID was split to get the Manufacturing Date.
Country Code: The Product ID was also split to get the Country Code.
Product Brand: Brand Name and Product Name were merged with a space.
Example: Dell + Laptop = Dell Laptop
5. Number Formatting:
Price: The Price column was changed to Currency ($) format.
Manufacturing Date: The date was displayed in DD-MM-YYYY format.
Example: 28-01-2026
6. Conditional Formatting:
Price: Data Bars were added to the Price column.
Electronics: The cells with Electronics category were highlighted using conditional formatting.
