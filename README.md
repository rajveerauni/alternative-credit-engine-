# Alternative Credit Scoring Engine (Production-Ready Fintech Simulation)

An end to end credit risk platform designed for underbanked populations, leveraging alternative behavioral data and explainable machine learning to enable fair, scalable lending decisions.

## What this app does
⚙️ Core Capabilities
Synthetic but realistic applicant generation
10,000 profiles with correlated financial behavior patterns
Default rate calibrated (~18%) to mimic subprime segments
Alternative data feature engineering
Payment consistency (utilities, rent)
Income volatility (gig work)
Digital footprint stability (mobile usage)


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
