# Customer Churn Prediction & Power BI Dashboard

An end-to-end Big Data and Machine Learning project that processes customer
data with **PySpark**, trains predictive models with **Spark MLlib**, and
presents the results in an interactive **Power BI** report.

## Project Overview
The project analyses customer behaviour to answer two questions:
1. **Classification:** Which customers are likely to churn?
2. **Regression:** How much will a customer spend next month?

## Repository Contents
| File | Description |
|------|-------------|
| `Theory_Assignment1_BigData.ipynb` | PySpark notebook covering data cleaning, model training and evaluation |
| `power BI_Project Priyanka_2570138.pbix` | Power BI report with multi-page dashboards of the model outputs |

## Workflow
1. **Data ingestion:** Load raw customer data (CSV) into a Spark DataFrame
2. **Data cleaning:** Remove duplicate customers and missing values
3. **Classification model:** Logistic Regression (features scaled with
   StandardScaler) to predict churn
4. **Regression model:** Linear Regression to predict next-month spend
5. **Evaluation:**
   - Classification: Accuracy, Precision, Recall, F1 Score, ROC-AUC, Confusion Matrix
   - Regression: MAE, RMSE, R²
6. **Export:** Predictions and metrics saved as CSV files for Power BI
7. **Visualization:** Dashboards built in Power BI

## Features Used
`age`, `income`, `tenure_months`, `monthly_spend`, `usage_hours`,
`support_calls`, `satisfaction`

## Tech Stack
- Python, PySpark 3.5.1 (Spark MLlib)
- Pandas, NumPy
- Google Colab
- Microsoft Power BI Desktop

## How to Run
**Notebook:**
1. Open `Theory_Assignment1_BigData.ipynb` in Google Colab
2. Upload the raw customer CSV file
3. Run all cells in order

**Dashboard:**
1. Open the `.pbix` file in Power BI Desktop
2. Refresh the data source if prompted

## Author
Priyanka (Roll No. 2570138)
