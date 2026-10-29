Open **MENU → Calculate & explore → Graph / Table**. A new graph is empty.

1. Open **Series → Add curve**.
2. Choose explicit `y=f(x)` and enter `x^2`.
3. Set a useful view in **Range**, for example x from −5 to 5 and y from −1 to 10.
4. Press **Plot**.
5. Drag to pan; pinch or use **+ / −** to zoom. **View → Reset view** restores the view while retaining the series.

Up to 20 series can be stored. Types include explicit, polar, parametric, implicit, inequalities and `z=f(x,y)` surfaces. For an implicit circle enter `x^2+y^2-1` as the zero-expression. Each series has its own angle convention; RAD is the graph default. A degree-based polar interval must use degree values.

**Equal axes** helps preserve geometric proportions in 2D. **View → Fit view** fits sampled vertical extent. **Series → Manage curves → Clear all curves** removes series. In 3D, dragging rotates the surface; it is a height visualization with independently normalized axis extents.

For a table, select a series, open **Table**, enter From/To/Step and use **Generate table**. The step must be positive and From must not exceed To. Tables accept at most 10,000 rows and also share the sampling budget. Implicit, region and surface tables use a **y=0 slice**; they are not a full two-variable grid.

Quick/Normal/Fine control bounded sampling work. Undefined values or unresolved sharp features can appear as gaps. Roots, intersections, extrema and area annotations are numerical estimates, not proofs that every feature was found. Read per-row and per-series status when work reaches its limit.

Export **PNG** for the current view, **SVG** for 2D geometry, or **CSV** for table samples. A saved graph configuration restores without plotting automatically. A graph opened from Details can retain the saved calculation context; **Current context** explicitly switches it to the current environment.

---

[Previous: Algebra, calculus, Details and Steps](08-algebra-steps.md) · [Manual contents](./) · [Next: Matrices, data and Finance](10-workbenches.md)
