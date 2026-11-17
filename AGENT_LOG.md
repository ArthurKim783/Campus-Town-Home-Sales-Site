# Agent log

## 2026-11-17: College-town median sale prices

- **Asked:**
  > Read AGENTS.md and docs/data_description_sheet.md first. Then show every median sale price on index.html rounded to whole dollars, in both the charts and table.
  >
  > Main has changed since your copy was made: it now has a bar chart over the table. Pull the latest main first, drop the chart you added, and only round the prices in the existing chart and table to whole dollars.
  >
  > Ok looks good, commit this change on a new branch, push it, and open a pull request into main.
  >
  > Can you do the remaining actions for me before I submit?

- **Agent produced:** Built the median price chart and table from the CSV, displaying whole-dollar USD values and excluding sales below $10,000. Opened PR #1, which was merged into `main`.

- **Checked or changed:** The CSV has 35,402 sales at or above $10,000 across 18 cities. GitHub shows the repository is public, its About homepage points to the live site, and the Pages workflow after the merge succeeded. The user confirmed that the live site worked. Codex initially used a $1,000 cutoff and misread the guide's demo state as the user's repository state. The user caught the mismatch with screenshots: the guide's chart was from a separate example, while this repository had only the initial placeholder commit. The cutoff was changed to $10,000 to match the guide's stated rule and 35,402-row result.
