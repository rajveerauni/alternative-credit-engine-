# Alternative Credit Scoring Engine (Production-Ready Fintech Simulation)

An end to end credit risk platform designed for underbanked populations, leveraging alternative behavioral data and explainable machine learning to enable fair, scalable lending decisions.

## What this app does
1. Synthetic but realistic applicant generation
2. 10,000 profiles with correlated financial behavior patterns
3. Default rate calibrated (~18%) to mimic subprime segments
4. Alternative data feature engineering
5. Payment consistency (utilities, rent)
6. Income volatility (gig work)
7. Digital footprint stability (mobile usage)
8. E-commerce behavioral signals
9. Modeling
10. Logistic Regression → interpretable baseline
11. XGBoost → non-linear performance boost
12. Hyperparameter tuning via Optuna
13. Policy Simulation Engine
14. Adjustable approval thresholds
15. Risk-based segmentation (tiers)
16. Scenario testing for business strategy

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

## Notes
- Demographic attributes are kept for bias auditing only.
- This repository uses synthetic data for portfolio demonstration.
