## History

Tap **HIST**, or use **MENU → Saved workspace → History**. History keeps up to 10,000 confirmed successful calculations, newest first. Search examines the retained archive; the list displays 100 entries per page.

Recall a saved calculation to restore its expression, matching result and calculation modes without evaluating it again. This matters for random expressions and values that have changed since the calculation. Use **Details** when you want to inspect a result more closely. Recalculation is an explicit separate action.

History CSV export includes **all retained entries**, even when the visible list is filtered. It includes expressions, results and calculation metadata. Clearing History is separate from AC and from clearing registers.

## One memory and ten registers

**MS** stores the confirmed result in M, **MR** inserts/recalls M, **SHIFT+MR** adds the confirmed result to M, and **SHIFT+MS** clears M in Compact. M and Ans are separate values.

Use **R0–R9** for ten named stored values. For example, enter `R0:=12/5` and explicitly evaluate; then `R0*10` gives `24`. Assignment is not performed by automatic preview.

**SHIFT+.** opens the REG layer in place on the keypad. Number positions become R0–R9, and choosing a register inserts its token while keeping the REG layer active. Use the decimal-point or SHIFT position to leave it. Other keys are deliberately inactive in this layer.

Open **Toolbox → Registers** to inspect stored values, copy their complete canonical decimal form or clear selected registers. The manager distinguishes empty and occupied registers. Clearing registers does not clear M, Ans, the expression or History.

---

[Previous: Navigate the workspace](05-navigation.md) · [Manual contents](./) · [Next: Constants, units and currency](07-conversions.md)
