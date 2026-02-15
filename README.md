# Congressional-Lobbying-Data-Engineering-Modeling

**Project:** Congressional Lobbying — Creating and working with complex datastructures to analyze lobbying expenditures.

**Purpose:** Repository for a class project exploring congressional lobbying and working with SQLite and MongoDB for OpenSecrets lobbying datasets. 

**Contents:**
- **Data:** `Data/newsapi_keyword_articles.csv` — NewsAPI keyword pulls used for analysis.
- **Notebooks:**
	- `Notebooks/Collaborative Contributions/8414_Final_Project_Codebook_prod.ipynb` — Full project notebook (group work).
	- `Notebooks/Section_7_Topic_Modeling.ipynb` — Standalone, runnable notebook with the Topic Modeling section I developed (recommended for portfolio review).
- **Environment:** `requirements.txt` is included for reproducibility.

**My Role:**
- **Topic modeling:**
  - Designed SQLite and MongoDB data structures for 7 OpenSecrets lobbying datasets (n ≈ 12.5M) to organize reports, lobbyists,
issues, bills, agencies, and industry totals.
  - Applied PCA and OLS regression with log transforms to analyze lobbying expenditures, using SQL aggregations, statistical tests,
and visualizations to summarize patterns.

**Notes & Assumptions**
- The notebooks expect the datasets at `Data/newsapi_keyword_articles.csv` (fill as requested from OpenSecrets).


**Attribution & License**
- License: see `LICENSE` in repo root.
