# Fitbit Activity Analysis
**April–May 2016 | Python, pandas, Tableau | Data: Kaggle — Fitbit Fitness Tracker**

An analysis of real-world Fitbit data from 30 users, exploring what drives calorie burn, how activity varies by time and day, and whether physical activity actually affects sleep duration.

---

## Key Findings

**What drives calories burned:** MET (Metabolic Equivalent of Task) is the strongest predictor of calorie burn (R² ≈ 0.99). Exercise intensity is nearly as strong (R² ≈ 0.96). Heart rate is weaker and less stable (R² ≈ 0.72).

**What drives intensity:** Step rate is a stronger predictor of intensity (R² ≈ 0.83) than heart rate (R² ≈ 0.63). Physical movement predicts effort more reliably than physiological response.

**Daily activity pattern:** Activity is lowest between midnight and 4 AM, rises gradually through the morning, and peaks at 5–6 PM. Behaviour follows consistent daily routines rather than random variation.

**Weekly pattern:** Activity is relatively stable across the week. Slight increase on weekends, particularly Saturday. Lowest activity recorded on Thursday and Friday.

**Does activity affect sleep?** Surprisingly, no meaningful link was found. Sleep vs moderate activity: R² ≈ 0.00. Sleep vs high activity: R² ≈ 0.02. Sleep duration appears largely independent of prior-day physical activity in this dataset.

**Sleep patterns:** Longest time in bed on Sundays, with a slight mid-week increase on Wednesdays — likely reflecting accumulated fatigue and recovery.

---

## Project Structure

```
├── notebooks/                          # Data cleaning & analysis
├── PDF_Presentation_Fitbit.pdf         # Full slide deck with charts
└── README.md
```

---

## Tools & Methods

- **Python** (pandas, NumPy) — data cleaning, aggregation, correlation analysis
- **Tableau** — scatter plots with regression lines, time-series and bar charts
- **Statistical analysis** — linear regression across multiple variable pairs (R² comparison)
- **Dataset** — 30 anonymised Fitbit users, daily-level records, April–May 2016

---

## Data Source & License

Data sourced from [Kaggle — Fitbit Fitness Tracker Data](https://www.kaggle.com/), released under CC0 (Public Domain). Project is for educational and portfolio purposes only.
