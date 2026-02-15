# Congressional-Lobbying-Data-Engineering-Modeling

**Project:** Congressional Lobbying — Creating and working with complex datastructures to analyze lobbying expenditures.

**Purpose:** Repository for a class project exploring congressional lobbying and working with SQLite and MongoDB for OpenSecrets lobbying datasets. 

**Contents:**
- **Data:** `Data/` — Includes required datasets downloadable from OpenSecrets: https://www.opensecrets.org/bulk-data (Must create a registration).
  
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

Thank you to OpenSecrets for allowing access to their extensive lobbying datasets.

The dataset captures detailed information on lobbying activities, including reported spending amounts, clients, industries, issues, agencies, lobbyists, and related legislation, across multiple years. Because the data is self-reported by registrants and spans a wide range of industries and issue areas, it offers a comprehensive but imperfect view of lobbying behavior, making it well suited for exploratory analysis and modeling.

Follow this link to see more from OpenSecrets:

http://www.opensecrets.org/lobby/
OpenSecrets Mission Statement:

Nonpartisan, independent and nonprofit, our mission is to serve as the trusted authority on money in American politics. We pursue our mission by providing comprehensive and reliable data, analysis and tools for policymakers, storytellers and citizens. Our vision is for Americans to use data on money in politics to create a more vibrant, representative and responsive democracy.

We pursue our mission with three goals:

    Data: We collect, clean and create access to quality and timely data on money in politics for an informed public.
    Insights: We generate and publish regular analysis, reports and user-friendly tools for people to interpret our data.
    Engagement: We fuel a growing community of policymakers, storytellers, and citizens who follow the money in American politics.

Our award-winning website is the front door for engaging with our data on money in politics. There, you can find a wellspring of resources on elections, politicians, campaign raising and spending, lobbying, learning tools and analysis. OpenSecrets also regularly works with media outlets and journalists to provide exclusive data and analysis to power investigations alongside our own original reporting.

As a 501(c)3 tax-exempt, charitable organization, OpenSecrets relies on the financial support from a combination of institutional grants, the generosity of individuals (like you!) who care about our work, and income earned from custom research and licensing data for commercial use.

You can support our work directly by making a tax-deductible contribution here.

- License: see `LICENSE` in repo root.
