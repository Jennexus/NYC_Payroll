# NYC_Payroll
This project analyzes New York City payroll data to explore employee compensation during fiscal year 2021. The analysis uses Python and Pandas to prepare and filter a large public dataset, calculate compensation measures, and compare payroll patterns across employees, agencies, and work locations.

The original dataset contains more than 4.4 million payroll records. The analysis focuses on the 573,477 records from fiscal year 2021.

## Data Source

**NYC Open Data — Citywide Payroll Data**

The dataset includes employee and agency information, base salary, regular gross pay, overtime hours and pay, other pay, work location, and related payroll information.

## Tools & Technologies

* Python
* Pandas
* NumPy
* Jupyter Notebook

## Analysis

The project includes:

* Initial inspection of a dataset containing more than 4.4 million records
* Standardization of text fields for consistency
* Filtering the dataset to fiscal year 2021
* Review of base salary, regular gross pay, and overtime compensation
* Creation of a calculated `Total Gross Paid` field combining regular gross pay, overtime pay, and other pay
* Calculation of mean and median total gross compensation
* Comparison of median and maximum individual gross pay across 156 NYC agencies
* Analysis of compensation within the Office of the Mayor
* Analysis of average base salary by work location

## Key Findings

* The fiscal year 2021 dataset contains **573,477 payroll records across 156 agencies**.
* Median total gross pay was approximately **$43,359**, while mean total gross pay was approximately **$52,018**.
* The **Financial Information Services Agency** had the highest median total gross pay among the agencies analyzed, at approximately **$120,891**.
* The **NYC Housing Authority** had the highest maximum individual total gross pay, at approximately **$515,260**.
* Mayor Bill de Blasio received approximately **$253,065 in total gross pay** during fiscal year 2021.
* Among the work locations represented in the data, **Washington, DC had the highest mean base salary**, at approximately **$133,560**.

## Skills Demonstrated

This project demonstrates practical use of Python and Pandas for:

* Importing and working with large datasets
* Data inspection and preparation
* DataFrame copying and filtering
* String standardization
* Creating calculated fields
* Boolean filtering with multiple conditions
* Descriptive statistics
* GroupBy operations
* Aggregation
* Sorting and ranking
* Subsetting data for targeted analysis
* Interpreting payroll data across organizational and geographic categories

## Repository Contents

* `NYC_Payroll.ipynb` — Jupyter Notebook containing the complete analysis
* `README.md` — Project overview, methodology, and key findings

## Notes

This project was developed from coursework and subsequently refined for inclusion in a professional data analytics portfolio. The portfolio version focuses on a selected set of analyses that demonstrate data preparation, transformation, aggregation, filtering, and exploratory analysis using Python and Pandas.

