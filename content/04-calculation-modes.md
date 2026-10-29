## Angles

Use **DRG** to cycle **DEG**, **RAD** and **GRAD**. Check the display before a trigonometric calculation: `sin(30)` is one half in DEG, but not in RAD. A unit-qualified expression such as `sin(30 deg)` states its own angle unit. SHIFT+DRG inserts `rad`; ALPHA+DRG inserts `deg` in the Compact layout.

## Number bases

In Compact, **SHIFT+×** selects BIN, **SHIFT+÷** OCT, **SHIFT++** DEC and **SHIFT+−** HEX. The current base affects number entry and presentation. Each base retains its own input draft. Digits invalid for the current literal are unavailable, so a disabled 8 in OCT is intentional.

The calculator's base modes support fractional real numbers; they are not fixed-width integer modes. Nondecimal output cannot represent every symbolic, unit-bearing, complex or nonfinite result. Return to DEC for those calculations. Explicit `0b` and `0x` prefixes can identify binary and hexadecimal literals. Use the separate **Programmer** workbench for bit widths, two's-complement interpretation and overflow rules.

## Precision and notation

**Settings → Calculation → Significant digits** accepts **10–200**, with **30** as the default. Increasing precision can help decimal calculations; it does not turn an approximate input into an exact measurement. Normal, Scientific, Engineering, FIX and SI presentations are available through notation controls; **SHIFT+EXP** cycles notation. The FIX decimal-place setting is separate from significant-digit calculation precision.

Choose **Number domain → Real numbers** or **Complex numbers** in Settings. In Complex mode, `sqrt(-1)` can produce `i`. In Real mode the keypad changes its complex-only alternatives and real-domain restrictions apply. On Compact, **SHIFT+7** switches the domain.

---

[Previous: Touch editing and keypad layers](03-touch-editing.md) · [Manual contents](./) · [Next: Navigate the workspace](05-navigation.md)
