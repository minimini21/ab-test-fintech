# A/B Test Case Study — Synthetic Fintech Data

## Overview
This project simulates and analyzes an A/B test for a fintech product.
We evaluate the treatment’s impact on **conversion rate**, **ARPU**, and **30-day retention**.

## Contents
- `data/ab_test_data.csv` — synthetic dataset (5,000 users)
- `notebooks/ab_test_analysis.ipynb` — Python + SQL analysis
- `sql/summary_queries.sql` — SQL aggregation queries
- `docs/decision_memo.pdf` — 1-page executive summary

## Key Findings
- Conversion improved from 28% → 32% (+3.2%, p=0.02)
- No significant change in ARPU
- Retention improved from 18% → 22% (p=0.04)
- Sample size gave ~80% power to detect a 3% lift

## How to Run
1. Clone this repo
2. Open `notebooks/ab_test_analysis.ipynb` in Jupyter or Google Colab
3. Run all cells

## Deliverables
- [Decision Memo (PDF)](docs/decision_memo.pdf)
- [Notebook](notebooks/ab_test_analysis.ipynb)
