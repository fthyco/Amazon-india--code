# E-commerce Sales Analysis 📊

This project is a Jupyter Notebook that analyzes e-commerce sales and expense data from multiple sources, focusing on Amazon sales. The notebook performs data cleaning, aggregation, and visualization to better understand business performance.

---

## 📁 Datasets Used

The notebook loads the following CSV files (must be placed in the same directory):

- `Amazon Sale Report.csv`
- `Sale Report.csv`
- `InternationalsaleReport.csv`
- `P  L March 2021.csv`
- `May-2022.csv`
- `Expense IIGF.csv`
- `Cloud Warehouse Compersion Chart.csv`

---

## 🔍 Key Features

- **Data Cleaning**: Handling missing values, dropping unnecessary columns, fixing data types.
- **Category-Level Analysis**: Sales grouped by product category.
- **Monthly Trends**: Line chart showing monthly sales volume.
- **Null Value Handling**: Using category-based modes to fill missing amounts.
- **Descriptive Statistics**: Summary statistics for numeric and categorical columns.

---

## 📦 Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- jupyter

Install using pip:

```bash
pip install pandas numpy matplotlib seaborn notebook
