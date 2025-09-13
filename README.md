# EPL Player Skill Map (Python + SQL)
Identify elite players with “top-right” scatter plots (e.g., npxG/90 vs xA/90).
**Tech:** Python (pandas, matplotlib), SQL (SQLite), Jupyter.

## Structure
- `data/` https://www.kaggle.com/datasets/siddhrajthakor/fbref-premier-league-202425-player-stats-dataset
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
![Goals vs xGoals](figures/goals_vs_xg.png)




## Progress

- **2025-09-12**  
  - Filtered dataset to remove players with 0 goals/assists.  
  - Added elite scatter plots for FW/MF/DF using 75th percentile thresholds.  
  - Learned about `plt.savefig` vs `plt.show` (must save before showing).  

- **2025-09-11**  
  - Set up GitHub repo with VS Code and pushed first commits.  
  - Installed Python, pandas, matplotlib, and adjustText.  
  - Loaded FBref dataset and made first scatterplot (Goals vs xG).  