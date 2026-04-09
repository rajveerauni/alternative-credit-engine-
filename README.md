# Alternative Credit Scoring Engine (Production-Ready Fintech Simulation)
An end to end credit risk platform designed for underbanked populations, leveraging alternative behavioral data and explainable machine learning to enable fair, scalable lending decisions.

![App Screenshot](Screenshot%2026-04-09%195647.png).

## What this app does
- Generates realistic underbanked applicant profiles using alternative behavioral data
- Engineers credit-risk features from rent, utilities, mobile, gig, and e-commerce signals
- Trains interpretable and high-performance models (Logistic Regression, XGBoost + Optuna tuning)
- Scores applicants and simulates approval strategies via adjustable risk thresholds
- Outputs business-critical metrics: approval rate, default risk, profitability, and fairness (AIR)

## Quickstart
1. Create and activate a Python environment (3.10+ recommended).
2. Install dependencies:
   - `pip install -r requirements.txt`
3. From this folder, launch dashboard:
   - `streamlit run dashboard/streamlit_app.py`
4. In the app, click **Run / Re-run Training Pipeline**.

## Business outputs in dashboard
- Approval rate and approved-book default rate
- Revenue estimate (interest - expected loss - funding cost)
- AIR fairness proxies by gender and region (80% rule check helper)
- Risk tier summary for accepted applicants

## Limitations & Real-World Considerations
- Synthetic data ≠ real-world bias/noise
- No bureau data integration (e.g., Experian/Equifax)
- Model drift and macroeconomic shocks not simulated
- Regulatory frameworks like Equal Credit Opportunity Act not fully implemented


## Notes
- Demographic attributes are kept for bias auditing only.
- This repository uses synthetic data for portfolio demonstration.
