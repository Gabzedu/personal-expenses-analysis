# Personal Financial Analysis (2022–2025)

## Project Overview

This repository presents a comprehensive analysis of personal income and expenses covering four years (2022–2025). The analysis explores patterns of financial discipline, evaluates savings potential under constrained income, and projects future financial needs based on historical behavior.

The study is structured into two main phases:

1. **Historical financial performance** – assessing income vs. expenses.
2. **Future financial planning** – projecting ideal income targets based on expense trends.

---

## Phase 1 – Income vs. Expenses

### Objective

To assess whether disciplined financial tracking can generate net savings over a multi-year period, even while earning minimum wage.

### Visualization

![Yearly Income vs Expenses](visuals/yearly_income_expenses.png)

### Key Insights

- Total Income (2022–2025): **€65,385**  
- Total Expenses (2022–2025): **€56,625**  
- Net Savings: **€9,725**

Despite earning at minimum wage levels, consistent tracking and structured financial planning enabled positive savings over the four-year period.

---

## Monthly and Category Breakdown

### Monthly Average Income

![Monthly Average Income](visuals/monthly_AVG_income.png)

**Insight:** Monthly income shows growth and variability over the year, indicating potential for improved savings management.

### Average Expenses by Category

![Average Expenses by Category](visuals/category_AVG_expenses.png)

**Insight:** Rent represents the largest recurring expense, followed by groceries and projects/studies. This breakdown highlights key spending categories that can be optimized for improved budgeting.

---

## Data Cleaning & Preparation

The dataset was manually assembled and later processed for analysis. Key steps included:

- Standardizing category naming
- Converting dates to consistent formats
- Handling missing values
- Extracting additional features (month/year)

Cleaned datasets are stored in `data/processed`.

---

## Technologies Used

- **Python (Pandas)** – data preparation and transformation  
- **Tableau** – data visualization  
- **Git & GitHub** – version control and documentation  

---

## Interactive Dashboard

Explore the full interactive dashboard (Tableau Public):  
👉 <div class='tableauPlaceholder' id='viz1770985778542' style='position: relative'><noscript><a href='#'><img alt='Final dashboard ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;pr&#47;projectpersonalfinances&#47;Finaldashboard&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='projectpersonalfinances&#47;Finaldashboard' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;pr&#47;projectpersonalfinances&#47;Finaldashboard&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='pt-BR' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1770985778542');                    var vizElement = divElement.getElementsByTagName('object')[0];                    if ( divElement.offsetWidth > 800 ) { vizElement.style.width='1200px';vizElement.style.minHeight='727px';vizElement.style.maxHeight='887px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else if ( divElement.offsetWidth > 500 ) { vizElement.style.width='1200px';vizElement.style.minHeight='727px';vizElement.style.maxHeight='887px';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';} else { vizElement.style.width='100%';vizElement.style.height='1277px';}                     var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script>

---

## Conclusion

This project illustrates:

- Disciplined financial tracking can support long-term savings, even under income constraints.  
- Structured analysis clarifies spending drivers and opportunities for optimization.  
- Historical financial data provides a foundation for future income planning and financial goal setting.

Future work could include predictive modeling and automated data ingestion processes.
