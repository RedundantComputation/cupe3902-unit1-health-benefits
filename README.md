# CUPE 3902 Unit 1 Health Benefits Guide

A one-page, mobile-friendly guide to CUPE 3902 Unit 1 health benefits at the University of Toronto. The whole site is `index.html`; there is no build step.

This guide was developed based on material compiled by Niharika Russell and developed by Patrick Lee.

## Publish on GitHub Pages

1. Create a new public repository on GitHub (for example, `unit1-health-benefits`).
2. Upload `index.html`, `README.md` and `.nojekyll` to the repository's main branch.
3. In the repository, go to **Settings > Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose **main** and **/ (root)**, then **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/<repository-name>/`.

To make a change later, edit `index.html` on GitHub (pencil icon) and commit. The live site updates within a few minutes.

## Updating each year

Check these every September, when the new plan year starts:

| What | Where it is in `index.html` | Source |
| --- | --- | --- |
| UTGSU Health Plan amounts | "UTGSU Health Plan" list in the coverage section | UTGSU plan site: https://utgsu.alumo.ca/health and https://utgsu.alumo.ca/dental |
| Plan A amounts and HCSA amounts | "Plan A" and "Plan B" lists | CUPE 3902 table of maximums, linked from https://www.cupe3902.org/u1-benefits |
| Change of Coverage Period dates | UTGSU Health Plan bullet | https://utgsu.alumo.ca/ |
| Collective agreement and bargaining note | Yellow note in the coverage section | https://weareuoft.com/2627-coordinated-bargaining-campaign |
| Edition and "last updated" text | Header ("Fall 2026") and footer | — |

Sources for the current version:

- UTGSU paramedical amounts: UTGSU plan site (checked November 2026).
- All other coverage amounts: CUPE 3902 table of maximums, GSU/Top-Up Plan 2025/2026 Plan Year.
- Eligibility, enrolment timing, ID formats and claims deadlines: CUPE 3902 Unit 1 & 7 Health Benefits FAQ (https://www.cupe3902.org/unit-1-7-faq) and Unit 1 benefits page.

The blackout status message at the top of the page changes automatically with the date (September 1 to October 31 shows the blackout message). Its dates are set in the `<script>` at the bottom of `index.html`.
