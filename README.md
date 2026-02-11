## Data Description
The `data/raw` folder contains monthly personal expense records from 2022 to 2025.  
The data was recorded manually over the years, is real, originally in Portuguese, and has not been modified.
The `data/processed` folder contains cleaned and standardized versions of the same data, adapted specifically for analysis within this project.

## Project Overview
This project aims to consolidate and clean personal financial data stored across multiple Excel files (one for each year) to create a unified dashboard in Tableau.
This project demonstrates a full data workflow: from cleaning messy raw data with **Python** to creating strategic financial insights for decision-making.

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

---

## 🎯 The Challenges

### 1️⃣ Challenge: Income vs. Expenses (The Power of Consistency)
**Objective:** To identify earning vs. spending trends and prove that, even on a minimum wage, it is possible to save money consistently over time through disciplined organization.
* **Focus:** Analyzing raw real Income vs. Expenses data from 2022 to 2025.
* **Key Question:** "Can an individual accumulate capital over 4 years by maintaining constant financial organization, despite being on a minimum wage?"
* **Insight Goal:** A comprehensive dashboard tracking 4 years of financial history, highlighting the gap between earnings and costs.

### 2️⃣ Challenge: Future Financial Planning
**Objective:** A long-term projection based on the statistics and patterns identified in the previous 4 years.
* **Focus:** Projecting future wealth based on my current lifestyle and long-term personal goals.
* **Key Question:** "Based on my historical spending patterns, what income levels and savings rates are required to satisfy my future life objectives?"
* **Insight Goal:** A predictive model/dashboard that aligns historical data with future lifestyle aspirations.
---

## 📊 Visualizations

The results of these challenges are hosted in the `/visuals` folder:
* **[Dashboard 1: Saving Money]** - *Coming Soon*
* **[Dashboard 2: Future Planning]** - *Coming Soon*
