**MENU → Personalize → Input modes** opens **Expression**, **Classic** and **RPN** workflows.

- **Expression** uses normal precedence: `2+3*4` gives 14.
- **Classic** works in immediate left-to-right order: `2 + 3 × 4 =` gives 20. Repeated equals reuses the confirmed right operand; `2 + 3 = =` gives 5, then 8. Relative and Direct percentage handling are explicit choices.
- **RPN** uses a stack with the top shown first. Enter 2, press Enter, enter 8, press Enter, then subtract to obtain −6. The second-from-top is the left operand. Empty Enter duplicates the top; Drop, Swap, Roll and Clear rearrange or clear the stack. Successful operations commit results; merely pushing or rearranging values does not.

The **Programmer** workbench uses 8-, 16-, 32- or 64-bit integers. Choose signed/unsigned and checked/wrapping behaviour before operating. It supports arithmetic, logical operations, shifts and rotations. Signed 8-bit `0xFF` means −1. Checked overflow is an error; Wrap reduces the operation's result modulo the chosen width. Out-of-range input, division by zero and invalid shift counts remain errors.

In **Saved workspace → Definitions**, create reusable named variables or functions. Use distinct names and review their bodies before applying them. In **Personalize → Keypad designer**, start from a stock template, edit the portrait/landscape profiles and validate before applying. Invalid or overlapping layouts cannot be applied. Selecting Pocket, Compact or Expanded in Settings returns to a stock layout; the fixed gear remains available for recovery.

---

[Previous: Matrices, data and Finance](10-workbenches.md) · [Manual contents](./) · [Next: Make the interface comfortable](12-appearance-help.md)
