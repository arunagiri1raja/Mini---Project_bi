# Copilot-Assisted DAX Development

## 1. MoM Sales Growth

- Copilot suggested a DAX measure using the current month's sales and the previous month's sales.
- The suggested DAX was reviewed and added to `Fact_Sales.tmdl`.
- Correction: the TMDL measure declaration and indentation had to be corrected so the measure was placed correctly inside the `Fact_Sales` table.

## 2. Running Total Sales

- Copilot suggested a running total using `CALCULATE`, `FILTER`, `ALLSELECTED`, and the date column.
- The suggested DAX worked correctly.
- No major DAX correction was required.

## 3. Target Attainment %

- Copilot suggested dividing total sales by a target value of 100000.
- The DAX logic was correct.
- Correction: the TMDL `measure` declaration and indentation had to be fixed before Power BI accepted the measure.

## 4. Item Sales Rank

- Copilot suggested a `RANKX` measure using total sales for each item.
- The highest-selling item receives rank 1.
- The suggested DAX was reviewed and added to the `Fact_Sales` table.
