# Field Report

A post-contest review tool for DraftKings NFL classic GPPs. Upload your contest standings CSVs and see how your lineups stacked up against the field: finishes, ownership ("chalk check"), weekly ownership calls, stacks, projection rank and P&L.

**Privacy:** everything runs in your browser. Files are never uploaded; they're kept in your browser's storage until you click "Clear my files".

## What to upload

1. **Contest standings** (required): one CSV per contest from a completed DraftKings contest.
2. **Entry history** (optional): DraftKings → My Contests → History → Download Entry History. Adds fees, winnings and dates.
3. **Salaries or projections** (optional): the slate's DKSalaries.csv or a projections export with player, team and salary columns. Unlocks stacks and projection rank.

## Hosting

This is a single static page (`index.html`) served by GitHub Pages. No build step.

For link previews on X/Discord, change the two `og-image.png` / `twitter:image` tags in `index.html` to the full URL, e.g. `https://YOUR-USERNAME.github.io/field-report/og-image.png`.

Not affiliated with DraftKings.
