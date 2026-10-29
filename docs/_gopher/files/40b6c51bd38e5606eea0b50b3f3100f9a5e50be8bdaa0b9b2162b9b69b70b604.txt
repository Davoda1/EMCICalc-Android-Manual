## Matrix

Open **MENU → Data & tools → Matrix**. Choose dimensions and fill every required cell. For a determinant example, enter rows `1, 2` and `3, 4`; the result is `−2`. Choose the operation and calculate, then inspect, copy, insert or export the result.

Matrices support up to **32×32** in this workbench. Operations still have mathematical requirements: an inverse needs a square nonsingular matrix; matrix products need compatible dimensions. Empty cells are not silently treated as zero. In the expression editor, clear filled cells before shrinking a structured matrix so values are not accidentally discarded. `sqrt(matrix)` is elementwise square root, not a matrix square-root algorithm.

## Data / Statistics

Open **MENU → Data & tools → Data / Statistics**. Enter values in the data grid, choose the relevant unpaired/paired and sample/population settings, then calculate. For values 1, 2 and 3 with frequency 1 each, the mean is 2.

The tool supports up to **10,000 rows**. Frequencies are nonnegative integer counts representing repeated observations, not arbitrary statistical weights. The total frequency must be between 1 and 10,000,000. Sample variance requires at least two observations. Missing required cells, invalid frequencies and nonfinite values produce diagnostics.

Read whether the summary is sample or population. Numerical summaries and regression are separate from the main calculator's exact symbolic arithmetic. CSV import/export is available; inspect the imported grid before calculating.

## Finance worksheets

Open **MENU → Data & tools → Finance**. Select a category and worksheet. Forms start without invented financial amounts; **Load example** explicitly supplies an example. Enter your own assumptions, tap **Calculate**, and review both the summary and any schedule, table or warning. Changing inputs makes the old result stale until recalculated.

The 29 worksheets cover loans and repayment comparisons; tax, deductions and gross-up; pricing, margin and break-even; allocation and inventory; savings, growth, inflation, NPV/IRR and dated cash flows; and conversion after fees.

For percentage fields enter **5%** or **0.05**, not 5, when you mean five percent. Match the rate convention and timing: annual nominal rate, effective annual rate and per-period rate are different inputs. Dates use `YYYY-MM-DD`. A 60-payment term is a number of payments, not automatically 60 years.

For a first guided exercise choose a loan worksheet, use **Load example**, calculate, then inspect the repayment table and assumptions before changing one input. Use **Copy summary** and **Copy table CSV** for the clipboard. These Copy actions do not themselves create files.

Monetary rounding can be presentation-only or per transaction; choose the worksheet's explicit decimal places and rounding convention. IRR searches are bounded and may find several rates; a returned rate is not a promise of uniqueness. Taxes, fees and legal assumptions are supplied by you—the app does not select a jurisdiction's rules.

For every worksheet's inputs, conventions, examples and limitations, open the [Finance reference](finance/).

---

[Previous: Graphs and tables](09-graphs-tables.md) · [Manual contents](./) · [Next: Other ways to calculate](11-input-workflows.md)
