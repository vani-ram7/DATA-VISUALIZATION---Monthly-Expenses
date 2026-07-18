# 📊 Company Monthly Expense Visualization

## 📌 Overview

This project demonstrates a basic data visualization analysis of a company's monthly expenses using Python. A sample dataset containing weekly expenses for four months (January to April) is created and transformed into a suitable format for visualization. The project helps understand spending patterns through bar charts and pie charts.

---

## 🎯 Objectives

* Analyze monthly company expenses.
* Compare weekly expenses across different months.
* Visualize total monthly expenditure.
* Practice basic data manipulation and visualization using Python libraries.

---

## 🛠️ Technologies Used

* Python
* Pandas
* Matplotlib
* Seaborn

---

## 📂 Dataset

The dataset contains expense records for four months:

| Month    | Week1 | Week2 | Week3 | Week4 |
| -------- | ----: | ----: | ----: | ----: |
| January  |  7000 |  8000 | 10000 |  1000 |
| February |  9000 |  9200 | 12000 |  2000 |
| March    | 10500 | 12000 | 11000 |  3000 |
| April    | 11750 | 15000 |  1750 |  1500 |

---

## 📈 Visualizations

### 📊 Bar Chart

* Displays weekly expenses for each month.
* Uses different colors to distinguish weekly spending.
* Helps compare expense trends across months.

### 🥧 Pie Chart

* Shows the percentage contribution of each month's total expenses.
* Provides a quick overview of monthly spending distribution.

---

## 🔄 Workflow

1. Import required Python libraries.
2. Create a sample expense dataset using Pandas.
3. Convert the dataset into long format using `pd.melt()`.
4. Generate a grouped bar chart with Seaborn.
5. Calculate total monthly expenses using `groupby()`.
6. Visualize the monthly expense distribution using a pie chart.

---

## 📊 Key Insights

* Weekly expenses can be compared across different months.
* Total monthly expenses are calculated for better financial analysis.
* Pie chart highlights the contribution of each month to the overall expenditure.
* The project demonstrates how simple visualizations can make financial data easier to understand.

---

## 📁 Project Files

```
monthly expense.ipynb   # Jupyter Notebook
README.md               # Project Documentation
```

---

## 🚀 Future Enhancements

* Add expense categories (Rent, Salaries, Marketing, Utilities, etc.).
* Read data from a CSV or Excel file.
* Create interactive dashboards using Plotly or Streamlit.
* Include line charts and trend analysis.
* Add monthly budget vs actual expense comparison.

---

## 📚 Learning Outcomes

Through this project, you will learn:

* Data preprocessing with Pandas
* Data reshaping using `melt()`
* Grouping and aggregation with `groupby()`
* Creating bar charts using Seaborn
* Creating pie charts using Matplotlib
* Basic Exploratory Data Analysis (EDA)



⭐ If you found this project useful, consider giving it a star on GitHub!
