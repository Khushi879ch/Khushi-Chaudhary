# Task 1 – Data Cleaning & Preprocessing (Excel-Based)
 
Clean a raw dataset using Excel by identifying and fixing:
-  Missing values
-  Duplicate rows
-  Inconsistent text/casing
-  Non-uniform date formats
-  Incorrect datatypes

 🛠 Excel Cleaning Steps

 1️⃣ Missing Values
- Applied filters → found blanks in `condition`, `odometer`, `color`
- Removed 3 rows with critical missing data
 2️⃣ Remove Duplicates
- Used Data → Remove Duplicates (across all columns)
 3️⃣ Standardized Text Formats
- Applied `=PROPER()` to fix inconsistent casing (e.g., `bmw` → `Bmw`)
- Used Find & Replace to clean up repeated seller formats
 4️⃣ Column Header Formatting
- Renamed columns: `Year` → `year`, `SellingPrice` → `selling_price`, etc.
- Ensured no spaces, consistent lowercase
5️⃣ Date Formatting
- Fixed `saledate` column to show consistent format → `dd-mm-yyyy`
6️⃣ Verified Data Types
- Checked that `odometer`, `mmr`, and `sellingprice` are numeric
- Dates set to proper format in Excel

 ✅ Results After Cleaning
- Dataset now has no nulls, no duplicates, and clean, readable formatting.
- All text is standardized, numeric formats are correct, and dates are consistent.
- Ready for analysis or visualization!

📁 Files Included in this Repo
File	Description
car_price_raw.xlsx                   	Original raw dataset
car_price_cleaned.xlsx               	Cleaned dataset after all steps
README.md	                            Task explanation and documentation
screenshots                            visuals from Excel
This task gave me hands-on experience with Excel’s powerful data cleaning tools.
