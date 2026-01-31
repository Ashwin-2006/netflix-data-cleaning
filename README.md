# netflix-data-cleaning
* In this repository i have performed basic data cleaning process on netflix dataset using excel

## Dataset Used

* Netflix Movies and TV Shows (CSV format)

### Steps Performed

* Downloaded the dataset in CSV format and opened it in Microsoft Excel.
* Verified that the first row was correctly recognized as column headers.
* Saved the original file as **Raw_Data.xlsx** to preserve raw data.
* Froze the header row and applied filters to all columns for easier data exploration.
* Identified missing values using column filters and conditional formatting.
* Analyzed missing data and decided whether to leave blank, replace with appropriate values, or remove rows based on column importance.
* Created a backup copy of the dataset before handling duplicates.
* Removed duplicate records using relevant key columns.
* Cleaned text columns using TRIM, PROPER, and UPPER functions to remove extra spaces and standardize formatting.
* Corrected data formats by validating date, numeric, and categorical columns.
* Created a separate sheet named **Cleaned_Data** and copied only the cleaned data into it.
* Added a **Data_Quality_Notes** column to document missing values, corrections, and assumptions made during cleaning.
* Saved the final cleaned dataset as **Cleaned_dataset.xlsx**.
* Exported the cleaned data as **cleaned_dataset.csv** for further analysis.
  
### Deliverables

* Raw_Data.xlsx
* Cleaned_dataset.xlsx
* cleaned_dataset.csv

### Tools Used

* Microsoft Excel
