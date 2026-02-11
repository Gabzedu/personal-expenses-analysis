# personal-expenses-analysis
This repository contains my personal monthly expenses data from 2022 onwards, used for data analysis and visualization practice.

## 📊 Data Description
The `data/raw` folder contains monthly personal expense records from 2022 to 2026.  
The data was recorded manually over the years, is real, originally in Portuguese, and has not been modified.

The `data/processed` folder contains cleaned and standardized versions of the same data, adapted specifically for analysis within this project.


## Project Overview
This project aims to consolidate and clean personal financial data stored across multiple Excel files (one for each year) to create a unified dashboard in Tableau.

## Technologies Used
* **Python:** For Data Engineering and Cleaning.
* **Pandas:** For data manipulation and standardization.
* **Tableau:** For data visualization and dashboarding.
* **Git/GitHub:** For version control.

## Data Cleaning Process (The "IMCOME" Case)
One of the key challenges in this project was data inconsistency. I used Python to:
1. **Unify Datasets:** Merged multiple yearly Excel files into a single dataframe.
2. **Handle Typos:** Corrected critical spelling errors in categories (e.g., changing 'IMCOME' to 'Income').
3. **Data Formatting:** Removed hidden whitespace in column headers and standardized numeric values for Tableau compatibility.

## How to Run
1. Navigate to the `notebooks/` folder.
2. Run `expenses_analysis.ipynb` to generate the `expenses_final_cleaned.xlsx` file.
3. Open the Tableau workbook and refresh the data source.
