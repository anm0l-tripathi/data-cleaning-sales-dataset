# data-cleaning-sales-dataset
# Sales Data Cleaning

**Tool used:** Excel
**Dataset:** messy_sales_data.csv (212 rows, 11 columns)

## Issues found and fixes
| Issue | Fix |
|---|---|
| 12 duplicate rows | Removed using Data → Remove Duplicates |
| Missing email, age, city, rating | Filled/removed (explain your choice) |
| unit_price stored as "Rs. 45,000" text | Removed "Rs." and commas, converted to number |
| order_date in 3 mixed formats | Standardised to YYYY-MM-DD |
| City/product spelling variants (Bombay, Mobile, etc.) | Standardised names |
| Name casing and extra spaces | Used TRIM and PROPER |
| Invalid ages and quantities | Corrected or removed |

## Result
Rows before: 212 | Rows after: ___

## Files
- messy_sales_data.csv: original
- cleaned_sales_data.csv: cleaned
