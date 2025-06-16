# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

## WMCA-DA-Project One
# Retail Data Analysis

### Dataset Content:
Data comes from this [kaggle dataset](https://www.kaggle.com/datasets/manjeetsingh/retaildataset)

## Business Requirements:
- Show the impact of Public Holidays and Markdown Sales on Store/Department Revenues.
- Provide actionable insights based on conclusions drawn from the analysis, with prioritisation placed on largest business impact.

## Hypotheses:
### Hypothesis 1:
- Markdown Sales to increase sales revenues across all stores/departments.
#### Result: 
In general, it appears that Markdown promotions show weak positive correlation with Sales, and are strongest during Holidays.

### Hypothesis 2:
- Holidays, especially Christmas to increase sales revenues.
#### Result: 
Certain departments, such as **Dept 72** see dramatic revenue uplifts during holidays, likely due to seasonal items (e.g. Toys)

### Hypothesis 3:
- Larger stores (Type A) generate more revenue on average, compare to other stores. 
#### Result:
Larger stores (Type A) generate the highest weekly sales, confirming that store size impacts revenue. 

## Rationale mapping business requirements to the Data Visualisations:
### Visualisation 1
- **Purpose:** To evaluate whether markdown promotions are effective at increasing weekly sales across stores.
- **Why Chosen:** A bar chart sorted by the correlation coefficient allows for a clear comparison across stores, highlighting where markdowns have the strongest or weakest effects.
- **Insight Delivered:** Markdown effectiveness is limited and varies widely — only a few stores show a mild positive correlation.

### Visualisation 2
- **Purpose:** To assess the impact of holiday periods on departmental sales.
- **Why Chosen:** A grouped bar chart provides a side-by-side comparison that clearly illustrates which departments see uplift during holidays.
- **Insight Delivered:** Department 72 (likely toys) shows a dramatic sales increase during holidays, with others like 5 and 7 showing modest boosts.

### Visualisation 3
- **Purpose:** To confirm whether larger stores (Type A) generate more revenue on average.
- **Why Chosen:** This Plotly chart fulfills this project’s requirement to include at least one interactive visual and offers a clean, engaging way to compare store types.
- **Insight Delivered:** Type A stores lead in weekly sales revenue, confirming that store size correlates strongly with performance.

### Visualisation 4
- **Purpose:** To identify and show how Holidays impact overall sales revenues.
- **Why Chosen:** Line Plot to clearly show total revenue across all stores within dataset.
- **Insight Delivered:** Clearly demonstrates the sales impact of major federal holidays e.g. Thanksgiving and Christmas. 

## Analysis techniques used:

- Extract Transform Load pipeline using Jupyter Notebooks
- Visualisations: (See above)

## Technologies used:

- Visual Studio Code
- Jupyter Notebook
- Chat GPT
- Microsoft Copilot

## Data Analysis Libraries:
- Pandas
- NumPy
- Seaborn
- Plotly
- Matplotlib

## Ethical Considerations

While this project analyses anonymised retail sales data, there are still important ethical considerations to be aware of:

### 1. Data Privacy
- The dataset does not include personal customer data, which reduces the risk of privacy breaches.
- However, if extended with customer-level data in future (e.g., loyalty cards, purchase history), **privacy and GDPR compliance** would become essential.
- **Recommendation:** Ensure customer data is anonymised, and usage complies with relevant data protection laws.

### 2. Fairness and Bias
- Store performance comparisons (e.g., by type or region) must be interpreted with caution.
- Factors such as **demographics, income levels, or regional investment** can influence sales, potentially skewing results.
- **Recommendation:** Avoid drawing conclusions that might penalise underperforming stores without understanding the wider context.

### 3. Responsible Use of Predictive Models
- Predictive models (e.g., for sales or markdown impact) could lead to **over-reliance on automation** in decision-making.
- **Recommendation:** Ensure models support — but do not replace — human judgement, especially in marketing, staffing, or resource allocation.

### 4. Broader Societal Impact
- Encouraging excessive promotions may contribute to **overconsumption or waste**.
- **Recommendation:** Align markdown strategies with sustainability goals and consider ethical retail practices.

By considering these aspects, we help ensure that data analysis contributes to responsible, fair, and informed decision-making in a retail context.


## Credits:
- Code Institute Learning Management System modules on Pandas and data visualisations with Seaborn and Plotly.
- Chat GPT to help with planning and code generation, and general encouragement.
- Microsoft Copilot integrated into VSCode to help with code generation and annotations. 
- [Markdown Guide](https://github.com/adam-p/markdown-here/wiki/markdown-cheatsheet#tables) for README.md markdown formatting. 
- [venv Setup Guide](https://drive.google.com/file/d/1LfTlnz0PJtzRl6EAv7c6W5Y5OmIGMRGl/view) Video by John Rearden demonstrating correct procedure for setting up Jupyter Notebook in Visual Studio Code. 

## Acknowledgements:
Thanks to Data Institute Course Instructors, Emma Lamont, John Rearden, and Vasi for all their help and support on the course. 

Shout out to my fellow cohort members, Julian Elliot and Petal Smart for their help and support throughout the whole process.

Thanks to the musical artists 'Underworld' for providing the perfect soundtrack for focussed study.



