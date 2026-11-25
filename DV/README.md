# Data Cleaning and Transformation

## Aim
Use Power Query to check data types, handle blanks, rename columns, and create a calculated column.

## Software
- Microsoft Power BI Desktop
- CSV dataset included in this folder

## Procedure
1. Open Power BI Desktop.
2. Select **Home → Get data → Text/CSV**.
3. Select `data.csv` from this folder and choose **Load**. For Practical 2, choose **Transform Data** instead.
4. Open the **Report** view and create the visual(s) listed below.
5. Add clear titles and check that the fields use the correct data types.
6. Save your work as `02_data_cleaning.pbix` in this folder.

## Suggested visual setup
- In Power Query, rename `Order Date` to `OrderDate`. Set OrderID and Quantity to Whole Number, OrderDate to Date, and Sales to Decimal Number.\n- Replace blank Region values with `Unknown`. Replace blank Sales with `0`, and blank Quantity with `0`.\n- Add a Custom Column named `TotalValue` with formula `[Sales] * [Quantity]`. Select **Close & Apply**.\n- Create a table with OrderID, Region, Category, Sales, Quantity, and TotalValue.

## Result
The visual(s) show the requested information and can be explored in Power BI.

## Conclusion
This practical helped me understand how to use Power BI for basic data analysis and visualization.

## Notes
- The included CSV is a small practice dataset created for this exercise; it is not an official or complete real-world dataset.
- Power BI Desktop project files (`.pbix`) must be created and saved in Power BI Desktop after following the steps above.
