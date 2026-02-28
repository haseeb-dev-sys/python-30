# python-30 — Day 2 (Control Flow)

**Project:** Day 2 — Control Flow (If / Elif / Else + Boolean Logic)

## One-line
Minimal, portfolio-ready examples demonstrating conditional logic in Python (boolean operators, short-circuiting) and a small practical extension (`extra_credit`) mapped to freelance automation use-cases.

## What’s included
- `fundamentals/Day2_ControlFlow.ipynb` — Google Colab notebook with:
  - basic `if/elif/else` example (age classification),
  - a reusable `grade()` decision function (AND / OR / NOT examples),
  - test vectors with predicted outputs,
  - an interactive demo cell for quick verification,
  - notes mapping the logic to real freelance tasks.

## How this is useful (freelance + product)
- **Invoice gating:** Replace `score`/`attendance` with `paid_percent`/`status_flag` to implement "send invoice if paid >= 80% OR status is 'priority'".  
- **Eligibility checks:** Build small decision engines for client workflows (approval, notification, routing).  
- **ML pipeline gating:** Use boolean gates to select preprocessing or fallback models in pipelines.

## How to run (Colab)
1. Open the notebook in Google Colab: `File → Open notebook → GitHub` → select this repo.  
2. Run cells **top → bottom**. Run the cell that defines `grade()` before running the demo cell.

## Notes for reviewers / clients
- The notebook is intentionally minimal and focused on **practical logic**, not exhaustive theory.  
- If you want a tailored automation (invoice, alerting, or CSV-based decision tool), message me with a short description — I deliver a working prototype quickly.

## Commit message used
`chore: day 2 control flow (if/elif/else, boolean logic, short-circuit examples)`

---
