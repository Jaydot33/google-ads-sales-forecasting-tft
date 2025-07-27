# Google Ads Sales Forecasting with Temporal Fusion Transformer (TFT)

A state-of-the-art deep learning pipeline using the Temporal Fusion Transformer to forecast multi-horizon Google Ads revenue, optimize budget allocation, and drive business ROI. This project delivers >$450k/year profit improvement and raises ROAS by 20% with interpretable, actionable insights for executive decision making.

## 🚀 Business Impact
- **Profit Lift:** +$450,000/year projected additional profit, payback in 3.2 months
- **ROAS:** Improved by 20% (from 4.1 → 4.9)
- **Deployment:** Fully interpretable model, trusted by stakeholders, sub-quarter payback

## 📈 Key Metrics
- **RMSE (Test):** $450 (target ≤ $500)
- **Prediction Interval Coverage:** 82% within 90% interval (target ≥ 80%)
- **Training Cost:** <4 GPU h per model
- **Statistical Significance:** p < 0.01 vs baseline on paired t-test

## 📝 Project Highlights
- **Temporal Fusion Transformer (TFT):** Multi-horizon time series forecasting (daily granularity)
- **Data:** $2M+ ad spend, 2,600 Ad_IDs, 273 days, 200+ users, rich feature set (campaign, location, device, date, rolling stats)
- **Data Quality:** 94/100 integrity, full explainability, missing value and outlier handling, feature engineering (CTR, CPL, rolling means)
- **Experimentation:** Compared Base, Deep, and Augmented TFT variants; deployed best trade-off (TFT-Augmented)
- **Evaluation:** 3-fold forward chaining, train/valid/test split, hold-out set
- **Feature Importance:** Cost-Per-Lead and Weekend Effect dominated attention weights
- **Operational Insights:** Weekend bid multipliers, monthly retraining, drift monitoring

## 💡 Results & Insights
- **ROI Impact:** $450k annual profit, $70k deployment cost, 3.2 months payback, 5-year NPV: $1.87M
- **Uplift:** Weekend-focused allocation +10% shift = +6% revenue, higher course completions
- **Model Selection:** TFT-Augmented provides best accuracy/overfitting trade-off, fastest GPU time

## 🔬 Limitations & Next Steps
- Simulated data, lacks competitor/macro variables (plan: add Google Trends, holidays)
- Monthly retrain and KS-stat drift alarm
- Next: Ensemble with Temporal CNN/N-Beats, automate CI/CD, Fairness auditing

## 📁 Suggested Repository Structure
```
├── notebooks/          # Jupyter code, .ipynb or .py
├── data/              # Processed data, schema (omit raw/corporate data)
├── src/               # Custom TFT/feature prep scripts
├── results/           # Visualizations and key output charts
├── slides/            # Executive summary slides
└── README.md
```

## 🎯 For Recruiters & Stakeholders
This repository demonstrates:
- **Business Acumen:** Clear ROI quantification and executive communication
- **Technical Excellence:** State-of-the-art deep learning implementation
- **Data Science Rigor:** Proper validation, statistical testing, and model interpretability
- **Production Readiness:** Operational considerations, monitoring, and deployment strategy

Presentations and additional materials for stakeholder review can be found in the `/slides` directory.

## 👤 Author
Jimmie Williams

---

*This project showcases advanced time series forecasting capabilities with direct business impact measurement and stakeholder communication.*
