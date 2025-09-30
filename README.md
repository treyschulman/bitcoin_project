# Bitcoin Price Prediction (t+7) — Penalized Regression

This repo contains the full workflow to predict Bitcoin’s **t+7 daily market price** using blockchain/network features.  
It follows the class guidance to favor **Ridge/LASSO/Elastic Net** over OLS due to multicollinearity, and uses **Test RMSE** as the primary selection metric (R² and others reported).

## Repo Structure
- data/ # Raw and intermediate data artifacts
- figures/ # PNGs exported by notebooks (pred vs actual, residuals, CV curves, etc.)
- notebooks/ # Reproducible notebooks for EDA → Cleaning → Feature Engineering → Modeling
- outputs/ # CSV metrics (cv_results_*.csv, val_metrics.csv, test_metrics.csv, coefficients, etc.)
- Bitcoin_Project_Report.docx: full writeup on project detailing methodologies and rationale
