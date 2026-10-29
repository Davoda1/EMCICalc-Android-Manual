The app saves preferences and session state in its application data directory. History and registers are retained separately. Settings shows the **Saved data** path and provides **Copy saved-data path**. Copying that path is informational; it does not bypass Android's access rules or create a backup.

## Export a workspace

1. Open **MENU → Saved workspace → Export workspace**.
2. Keep the sections you want: History, registers, definitions, stored values, matrices, datasets, graphs and layouts.
3. Tap **Save**, then choose a destination in Android's document picker.
4. Keep the resulting `.emci` file somewhere you can access independently of the app.

A workspace export is a selectable mathematical-workspace transfer, not an image of every app setting or cache. Keep separate notes or exports for preferences and worksheet information you need that is not included in its sections. History CSV, graph exports and Finance clipboard exports serve different purposes.

## Import carefully

Choose **Import workspace**, select an `.emci` file and inspect the section preview. The conflict choices are **Merge; keep existing names**, **Replace selected sections**, and **Merge; rename incoming names**. Export your current workspace first when you intend to replace sections. Import validates saved formulas without executing them automatically. Workspace input is limited to 32 MiB.

For document exports, select the final destination and confirm the picker. Cancelling the picker cancels the export. If the provider reports an error, choose another writable destination; a clipboard Copy command is not a successful file export.

Changes are saved automatically, including when leaving the foreground normally. An abrupt process kill can still lose a very recent uncommitted edit. Android uninstall or Clear storage can remove data, and the app does not rely on Android automatic cloud backup.

---

[Previous: Make the interface comfortable](12-appearance-help.md) · [Manual contents](./) · [Next: Troubleshooting and quick reference](14-troubleshooting.md)
