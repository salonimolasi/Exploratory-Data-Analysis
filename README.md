# Sales Data: Exploratory Data Analysis

An exploratory data analysis of 11,245 sales transactions, built with Python, pandas, matplotlib, and seaborn. The goal is to understand **who buys, what they buy, and where**, so marketing and stocking decisions can be based on data.

**Author:** Dr. Saloni Molasi | [LinkedIn](https://www.linkedin.com/in/drmolasi05)

---

## Questions explored

1. Which gender and age groups drive transactions and sales?
2. Which states generate the most orders and revenue?
3. Which product categories and professions matter most?

## Key findings

| Question | Finding |
|---|---|
| Gender | Female customers account for about **70%** of sales (74.5M vs 31.9M for male customers) |
| Age group | The **26-35** age group leads, contributing about **40%** of total sales |
| State | **Uttar Pradesh** leads in both orders (6,669) and sales (19.4M), followed by Maharashtra and Karnataka |
| Product category | **Beauty** is the top category (22.5M), narrowly ahead of Sports and Electronics |
| Profession | **IT Sector** leads in sales (14.8M), followed by Healthcare and Aviation |

Total sales analysed: **106.4M** across **11,245 transactions**.

## Charts

### Gender
![Gender analysis](images/01_gender_analysis.png)

### Age group
![Age group analysis](images/02_age_group_analysis.png)

### States
![State analysis](images/03_state_analysis.png)

### Product categories
![Product category analysis](images/04_product_category_analysis.png)

## What I did

- **Cleaned the data:** removed 12 fully empty rows and an empty column, fixed hidden non-breaking spaces in text columns (e.g. state and category names), and standardised gender labels.
- **Summarised** the data with `describe()` and `groupby()` to compare groups.
- **Visualised** results with count plots, bar charts, and grouped bar charts.
- **Wrote insights from the data itself:** the notebook prints each takeaway from the numbers, so the text always matches the charts.

## Tools

Python, pandas, matplotlib, seaborn, Jupyter Notebook (VS Code)

## Project structure

```
sales-eda-project/
├── README.md
├── Sales_Data_EDA_Portfolio.ipynb   # full analysis with charts
├── Sales_Data.csv                   # dataset
└── images/                          # charts used in this README
```

## How to run it

1. Download or clone this repository.
2. Install the libraries:
   ```bash
   pip install pandas matplotlib seaborn
   ```
3. Open `Sales_Data_EDA_Portfolio.ipynb` in Jupyter or VS Code.
4. Keep `Sales_Data.csv` in the same folder and click **Run All**.

## Limitations

- This is descriptive analysis of one dataset. It shows what happened, not why.
- The data has no date column, so seasonal trends could not be studied.
- Differences between groups show association, not cause.

## Next steps

- Build a Power BI dashboard from the cleaned data.
- Test whether the differences between groups are statistically significant.
- Add a time dimension to study seasonality.

## Note on the data

The dataset was provided as part of a Skill Course exploratory data analysis project and is used here for learning and portfolio purposes.
