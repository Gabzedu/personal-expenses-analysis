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


# 💰 Personal Expenses Analysis & Financial Planning

This project demonstrates a full data workflow: from cleaning messy raw data with **Python** to creating strategic financial insights for decision-making.

---

## 🎯 The Challenges

I structured this project to answer two specific financial scenarios:

### 1️⃣ Challenge: The "Saving Money" Strategy
**Objective:** Identify where the money is going and find immediate opportunities to increase the savings rate.
* **Focus:** Analysis of "Needs" vs. "Wants" (variable expenses).
* **Key Question:** "Which category has the highest impact on my monthly budget that can be reduced?"
* **Insight Goal:** A dashboard showing the top 5 expense categories and a 'Potential Savings' simulator.

### 2️⃣ Challenge: Future Financial Planning
**Objective:** Project long-term financial stability and retirement/investment goals.
* **Focus:** Income growth vs. inflation and fixed costs over time.
* **Key Question:** "Based on my current savings rate, what will my net worth look like in 5, 10, and 20 years?"
* **Insight Goal:** A trend analysis dashboard showing wealth accumulation and the "Financial Freedom" milestone.

---

## 🛠️ Data Engineering Process (The "Behind the Scenes")

Before the visuals, the data required significant cleaning. Using **Python (Pandas)**, I handled:
* **Inconsistent Naming:** Fixed typos like `IMCOME` to `Income`.
* **Data Typing:** Ensured dates and currency values were in the correct format for Tableau.
* **Categorization:** Grouped raw transactions into logical buckets for easier analysis.

---

## 📊 Visualizations

The results of these challenges are hosted in the `/visuals` folder:
* **[Dashboard 1: Saving Money]** - *Coming Soon*
* **[Dashboard 2: Future Planning]** - *Coming Soon*

---

## 🚀 Technologies Used
* **Python 3.12** (Data Cleaning & ETL)
* **Pandas** (Data Manipulation)
* **Jupyter Notebook** (Prototyping)
* **Tableau** (Data Visualization & Storytelling)
