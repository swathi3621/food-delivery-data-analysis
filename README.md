# Food Delivery Data Analysis System

## Project Overview
The Food Delivery Data Analysis System uses Python to clean and analyze food delivery order data and present findings through charts.

## Objectives
- Check missing values and duplicate rows.
- Clean missing values and remove duplicate records.
- Summarize food categories, order amounts, delivery times, ratings, and order statuses when these columns are available.
- Calculate descriptive statistics using Pandas and NumPy.
- Visualize order patterns using Matplotlib.

## Tools Used
- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook / Google Colab

## Project Files
- `Food_Delivery_Analysis.ipynb` — main notebook containing the analysis workflow.
- `requirements.txt` — Python libraries required to run the project.
- `.gitignore` — excludes common temporary files.

## How to Run
1. Download `Food_Delivery_Analysis.ipynb`.
2. Open [Google Colab](https://colab.research.google.com/) or Jupyter Notebook.
3. Open the notebook and run the cells from top to bottom.
4. When prompted, upload your food delivery dataset as a CSV file.
5. Check the printed summaries and charts.

## Expected Dataset Columns
The notebook recognizes these column names when present:
- `Food_Category`
- `Order_Amount`
- `Delivery_Time_Min`
- `Rating`
- `Order_Status`

Column names are case-sensitive in the current notebook. If your CSV uses different names, update the column names in the notebook or rename the CSV columns.

## Outputs
The notebook displays:
- Dataset size, missing values, and duplicate counts before and after cleaning.
- Summary statistics for numerical columns.
- Order counts by food category.
- Order status distribution.
- Average delivery time by food category.
- Charts for the available analysis columns.

## Dataset Note
Add your CSV dataset only if you are allowed to share it. Do not upload private, customer-identifying, or restricted data.

## Project Type
Academic Data Analytics Project
