# Glassworks Workroom: operations CRM prototype

A working CRM-style prototype built for the Business Systems & AI Operations Lead role at Glassworks London.
One file (`index.html`), no build step, no backend. All names and figures are fictional sample data.
Changes save in the viewer's own browser; "Reset sample data" in the sidebar restores the demo.

## How it works
Every module runs on the same record engine, borrowing proven CRM patterns:
- **Record pages** in three columns: editable properties on the left, tabs and activity timeline in the middle, related records on the right.
- **Stage path** across the top of each record, with guidance for the current stage and a one-click move to the next.
- **Table and board views** of the same data, with saved views, owner filter, search, column sorting, bulk update and CSV export.

## Modules
Home, Workflow map (Founder dependency index), Recruitment (candidates and jobs), People (employees, onboarding and probation), Retail training (matrix, release gate, quiz), Ecommerce issues, Stock movements, Marketing, Meetings (notes to actions), Tasks, SOPs, Files (naming checker), Decision gate, IT and access (requests and devices), AI workflows (templates and review log), Reports (weekly report generator).

## Deploy on GitHub Pages
1. Create a public repo, e.g. `glassworks-workroom`.
2. Upload `index.html` and this README to the repo root.
3. Settings > Pages > Deploy from a branch > `main` / root > Save.
4. Live in about a minute at `https://<your-username>.github.io/glassworks-workroom/`

Prepared by Ramakrishnan M.
