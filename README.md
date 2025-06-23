🛍️ Product Dataset Cleaning & Analysis
This project focuses on cleaning, preparing, analyzing, and retrieving data from a product dataset. The dataset contains various details like product IDs, pricing, discount offers, size options, and ratings.

📌 Project Objectives
A. Data Cleaning and Preparation
✅ Remove duplicate entries from the dataset to ensure data accuracy.

✅ Standardize the DiscountOffer column to maintain a consistent format across all values.

✅ Identify and fill missing DiscountPrice values with the average discount price of the respective category if both DiscountPrice and DiscountOffer are null.

✅ Replace all null entries in the SizeOption column with "Not Available" to avoid missing values.

B. Data Analysis
📊 Calculate the overall average original price for products with ratings greater than 4.

📈 Count how many products have a discount offer greater than 50% OFF.

👕 Count the number of products available in size "M".

🏷️ Create a new column called DiscountLabel that labels each product as:

"High Discount" if the discount offer is greater than 50% OFF

"Low Discount" otherwise

C. Data Retrieval and Lookup
🔍 Use VLOOKUP/XLOOKUP to find the brand, price, and rating for the product with Product_id = 11226634.

🔎 Retrieve the DiscountPrice of the product with Product_id = 6744434 using INDEX and MATCH functions.

🧩 Use nested XLOOKUP to fetch details of any column using a product's ID.

📁 Files Included
Cleaned dataset (CSV)

Excel workbook with analysis, formulas, and lookups

Python/Excel scripts (if any used for automation)

🛠️ Tools Used
Microsoft Excel / Google Sheets

Python (Optional, if used)

Data functions: VLOOKUP, XLOOKUP, INDEX, MATCH, IF, AVERAGE, COUNTIF

