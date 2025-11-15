# Customer-Personality-Analysis
1. Missing Values Handled

Checked nulls using .isnull()

Replaced missing values in Income with mean income

Removed rows with missing values in essential field ID

Standardized empty text entries (“”, “NA”, “?” → NaN)

 2. Removed Duplicate Records

Used .drop_duplicates() to remove fully repeated rows.

 3. Standardized Text Format

Converted all text columns to lowercase

Removed extra spaces

Standardized:

Marital Status → married, single, divorced, widowed

Education → graduate, postgraduate, highschool

 4. Date Format Fix

Converted Dt_Customer column to datetime using uniform format dd-mm-yyyy.

 5. Renamed Columns

Converted column names to:

lowercase

no spaces

snake_case format

 6. Corrected Data Types

Converted numerical fields to proper types (int/float)

Converted date field to datetime

 7. Final Cleaned Dataset Created

Saved as: cleaned_customer_personality.csv                                                                                                                                                                                    

📌 Summary
This project analyzes customer behavior using the Customer Personality Analysis dataset. The data was cleaned using Python, where missing values, duplicates, and inconsistent formats were fixed. A Power BI dashboard was then created using DAX measures to calculate key metrics like total spending, customer age, purchases, and campaign performance.
The visual report highlights customer demographics, spending patterns, top product categories, and purchase channel performance. Insights from the dashboard help identify high-value customers, successful campaigns, and opportunities to improve marketing strategies.
