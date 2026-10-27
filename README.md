# payroll-data-analysis
Python and Pandas Payroll Data Analysis Project
# City of Chicago Payroll Data Analysis

## Project Overview

This project explores and analyzes the City of Chicago payroll dataset using Python and Pandas. The goal is to understand employee compensation, salary and hourly payment structures, department-wise employee distribution, and job title information.

The project uses practical data analysis techniques to answer business-style questions and extract useful insights from payroll data.

## Objectives

* Explore the payroll dataset and understand its structure.
* Identify missing values and generate descriptive statistics.
* Analyze employee distribution by salary and hourly payment type.
* Find departments with the highest number of employees.
* Calculate minimum, maximum, and average annual salaries.
* Analyze hourly pay rates and identify employees receiving the highest hourly rate.
* Compare hourly rates with the overall average.
* Analyze full-time hourly employees.
* Explore department-wise average salaries.
* Identify common job titles and count titles containing the word "officer".
* Export the processed DataFrame to a CSV file.

## Tools and Technologies

* **Python** — Data analysis and programming
* **Pandas** — Data manipulation, filtering, grouping, and aggregation
* **Jupyter Notebook** — Interactive analysis and documentation
* **CSV** — Dataset input and output format

## Dataset

**Dataset name:** City of Chicago Payroll Data

**Input file:** `City_of_Chicago_Payroll_Data.csv`

The notebook uses payroll-related fields, including:

* `Name`
* `Department`
* `Job Titles`
* `Annual Salary`
* `Hourly Rate`
* `Salary or Hourly`
* `Full or Part-Time`
* `Typical Hours`

The analysis also creates two additional numeric columns:

* `Salary` — Annual salary converted from a dollar-formatted string to a numeric value.
* `H_Rate` — Hourly rate converted from a dollar-formatted string to a numeric value.

*Note: The original dataset is not included automatically with the notebook. Add it to the repository if you have permission to share it.*

## Analysis Performed

### 1. Data Exploration

* Loaded the CSV dataset into a Pandas DataFrame.
* Viewed the dataset and its initial records.
* Examined column data types and dataset information.
* Checked missing values in each column.
* Generated descriptive statistics.

### 2. Employee and Department Analysis

* Counted employees by salary or hourly payment type.
* Identified the department with the most employees.
* Analyzed salary and hourly employees in the Police department.
* Calculated the number of unique departments and job titles.

### 3. Annual Salary Analysis

* Converted annual salary values into numeric data.
* Calculated minimum, maximum, and average annual salary.
* Identified employees with the highest and lowest annual salaries.
* Calculated average and maximum salaries for each department.

### 4. Hourly Rate Analysis

* Converted hourly rates into numeric values.
* Calculated minimum, maximum, and average hourly rates.
* Identified employees receiving the maximum hourly rate.
* Counted employees earning below the average hourly rate.

### 5. Employment Type Analysis

* Identified hourly-paid, full-time employees.
* Filtered full-time employees earning an hourly rate of $10.00.

### 6. Job Title Analysis

* Retrieved the job title of a specific employee.
* Examined the most common job titles.
* Counted job titles containing the word "officer", ignoring letter case.

### 7. Data Export

* Exported the final DataFrame to a CSV file named `xyz.csv`.

## Python Concepts Practiced

* Reading CSV files with `pd.read_csv()`
* Inspecting data with `.head()`, `.info()`, and `.describe()`
* Detecting missing values with `.isnull().sum()`
* Using `.unique()` and `.nunique()`
* Grouping data with `.groupby()`
* Aggregating with `.count()`, `.mean()`, `.min()`, and `.max()`
* Filtering rows with conditions
* Sorting and counting categories with `.value_counts()`
* Cleaning numeric values with `.str.replace()` and `.astype(float)`
* Finding rows with `.idxmax()` and `.idxmin()`
* Applying custom functions with `.apply()`
* Exporting results with `.to_csv()`

## How to Run This Project

### Prerequisites

Install Python and Jupyter Notebook, along with Pandas.

```bash
pip install pandas jupyter
```

### Steps

1. Clone or download this repository.
2. Make sure `City_of_Chicago_Payroll_Data.csv` is available in the expected working directory.
3. Open a terminal in the project folder.
4. Start Jupyter Notebook:

```bash
jupyter notebook
```

5. Open `day 15 project payroll.ipynb`.
6. Run the notebook cells in order.

## Project Files

```text
payroll-data-analysis/
├── day 15 project payroll.ipynb
├── City_of_Chicago_Payroll_Data.csv
├── README.md
└── xyz.csv
```

The CSV files are shown as expected project files; include them only if they are available and appropriate to publish.

## Key Learnings

Through this project, I practiced using Pandas to explore real-world-style payroll data, clean salary-related values, filter employee records, group data by department, calculate descriptive statistics, and answer practical data analysis questions.

## Future Improvements

* Improve missing-value handling and data validation.
* Add visualizations to compare salary distributions across departments.
* Create a summary dashboard for payroll insights.
* Improve the final output with clearer column names and export settings.
* Add a concise findings section based on verified analysis results.

## Author

**Tanvir Ahmed**

GitHub: https://github.com/tanvirahmed437
