Tap a key to enter its active symbol. Tap **SHIFT** or **ALPHA** to select the small alternate label, then tap the required key. You can also hold a modifier while touching another key. Active modifiers remain visibly pressed. Tap the modifier again or leave the temporary layer when finished.

Hold an ordinary key to read its help above the keypad without entering that key. **Settings → Touch and feedback → Key help mode** offers an additional help mode. **Key tooltips** controls key help; **Screen tooltips** independently controls help for display controls.

Long-press an expression to open editing and keyboard controls. Use selection, copy, cut, paste and undo when editing a long expression. The left/right keys move the cursor; their SHIFT actions move to the beginning/end. A tap or drag in the editor helps position the cursor or adjust a selection.

## Natural and Linear input

**Settings → Input and display → Input style** selects:

- **Natural:** editable mathematical structures such as fractions, powers and roots.
- **Linear:** a ordinary text-style syntax.

Switching style preserves the mathematical input. A boxed empty argument must be filled before evaluation. The function Toolbox inserts empty templates so you choose the values yourself.

For a fraction, tap **SHIFT**, then **Ans**, and fill the numerator and denominator. **ALPHA**, then **Ans**, creates a mixed-fraction template. The ordinary **÷** key inserts inline division rather than the fraction template. Use **Right** to move through slots or leave a completed exponent/root/fraction. With an external keyboard, Tab and Shift+Tab move between slots; Shift+Enter inserts a visual line break.

Examples to try:

| Task | Enter | Expected result or action |
| --- | --- | --- |
| Exact arithmetic | `(1+2)/(3+4)` | `3/7` in Exact presentation |
| Power | `2^10` | `1024` |
| Exact radical | `sqrt(2)` | An exact radical, with an approximate decimal available |
| Factorial | `5!` | `120`; on Compact, factorial is SHIFT+4 |
| Fraction template | SHIFT+Ans | Fill both boxes; then evaluate |
| Mixed fraction | ALPHA+Ans | Fill whole number, numerator and denominator |

The main expression editor accepts up to 4,096 characters and limits structural nesting. Copying a result preserves its full canonical value rather than only the digits currently visible.

---

[Previous: Your first calculation](02-first-calculation.md) · [Manual contents](./) · [Next: Angle, base, precision and complex numbers](04-calculation-modes.md)
