# Alfido Tech Sales Performance Project

## Files
- `Alfido_Tech_Sales_Performance_Analysis.ipynb`: executable analysis notebook.
- `Alfido_Tech_Sales_Performance_Summary.pdf`: submission-ready project brief and action plan.
- `README.txt`: setup and interpretation notes.

## Run the notebook
1. Download the dataset from https://www.kaggle.com/datasets/bhanupratapbiswas/superstore-sales
2. Extract the CSV/XLSX file into this folder beside the notebook.
3. Install dependencies: `pip install pandas numpy matplotlib openpyxl jupyter`
4. Launch Jupyter and run all cells.
5. The notebook exports `cleaned_superstore_sales.csv` and summary tables in the working directory.

## KPI definitions
- Revenue = sum of Sales
- Profit = sum of Profit (negative values retained)
- Profit margin = total Profit / total Sales
- AOV = total Sales / distinct Order IDs
- Conversion = not calculable without a visitor/session/lead denominator and conversion event.

## Important
This is an analytical case study using a generic Superstore dataset. It does not establish Alfido Tech's actual performance. Verify actions with Alfido Tech's own data before implementation. Seasonality requires multiple comparable years and should be interpreted in context.
