# EPL Player Skill Map (Python + SQL)
Identify elite players with “top-right” scatter plots (e.g., npxG/90 vs xA/90).
**Tech:** Python (pandas, matplotlib), SQL (SQLite), Jupyter.

## Structure
- `data/` raw or sample CSVs
- `figures/` exported plots
- `notebooks/` analysis notebooks
- `sql/` SQL queries
- `requirements.txt` Python deps

## Reproduce
```bash
pip install -r requirements.txt
# open notebooks/01_explore.ipynb and run
```

## Results
![npxG vs xA](figures/demo_scatter.png)