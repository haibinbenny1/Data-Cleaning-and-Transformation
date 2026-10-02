# Data Cleaning and Formatting

## 1. Handling Missing Values

- **Missing Price:** Filled the missing prices using the median price of the available values.
- **Missing Category:** Replaced missing category values with **"Unknown"**.

## 2. Correcting Inconsistent Data

- **Product Name:** Corrected inconsistent capitalization, such as `laptop` to `Laptop`.
- **Category:** Corrected `Electroni` to **Electronics** using Replace Values.

## 3. Removing Duplicates

- Checked the dataset for duplicate rows using all columns.
- Removed **3 duplicate rows**.
- The dataset was reduced from **34 rows to 31 rows**.

## 4. Splitting and Merging Data

- **Manufacturing Date:** Split the Product ID to get the manufacturing date.
- **Country Code:** Split the Product ID to get the country code.
- **Product Brand:** Merged Brand Name and Product Name with a space.
- **Example:** `Dell` + `Laptop` = **Dell Laptop**

## 5. Number Formatting

- **Price:** Changed the Price column to **Currency ($)** format.
- **Manufacturing Date:** Displayed the date in **DD-MM-YYYY** format.
- **Example:** `28-01-2026`

## 6. Conditional Formatting

- **Price:** Added Data Bars to the Price column.
- **Electronics:** Highlighted the cells with the **Electronics** category using conditional formatting.
