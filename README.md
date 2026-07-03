# Bank Term Deposit Campaign — Subscribers vs. Non-Subscribers

A comparative analysis of 11,162 client contacts from a bank's term-deposit marketing campaign, examining what separates clients who subscribed from clients who declined.

![Bank Campaign Dashboard](dashboard/bank-campaign-dashboard.jpg)

## Overview

| | Subscribers | Non-Subscribers |
|---|---|---|
| Total contacts | 5,289 (47.38%) | 5,873 (52.62%) |
| Avg. call duration | 537.18s | 223.13s |
| Avg. balance | $1,804 | $1,280 |
| Avg. age | 42 | 41 |
| No housing loan | 63.41% | 43.03% |
| Reached via cellular | 82.6% | 62.54% |

Source data is visualized in two Power BI–style dashboards (`dashboard/bank-campaign-dashboard.jpg`), one per client outcome, each covering: previous campaign outcome, marital status, contact method, loan status, monthly contact volume, housing status, education level, and job category.

## Repository Contents

```
.
├── README.md                     This file — project summary and key metrics
├── dashboard/
│   └── bank-campaign-dashboard.jpg   Source dashboard (subscribers + non-subscribers)
├── presentation/
│   └── Bank_Campaign_Analysis.pptx   8-slide summary deck
└── docs/
    ├── data-dictionary.md        Field definitions used across the dashboards
    ├── findings.md               Detailed write-up of the six major findings
    └── recommendations.md        Actionable recommendations derived from the findings
```

## Key Findings

1. **Call duration is the strongest signal** — subscribers averaged 537s per call vs. 223s for non-subscribers (2.4x gap).
2. **Cellular outreach outperforms other channels** — 82.6% of subscribers were reached via cellular vs. 62.5% of non-subscribers.
3. **Household debt load matters** — 63.4% of subscribers carry no housing loan, vs. only 43.0% of non-subscribers.
4. **Occupation shapes conversion likelihood** — blue-collar clients are over-represented among non-subscribers (21.05% vs 13.39%).
5. **Prior campaign success predicts future success** — a successful previous outcome is far more common among subscribers.
6. **May is the seasonal peak** — both groups peak in May, but non-subscribers are more concentrated in a handful of months.

See [`docs/findings.md`](docs/findings.md) for the full detail and [`docs/recommendations.md`](docs/recommendations.md) for suggested next steps.

## Presentation

The full 8-slide deck (Dataset Overview → Key Visualizations → Major Findings → Recommendations → Conclusion) is in [`presentation/Bank_Campaign_Analysis.pptx`](presentation/Bank_Campaign_Analysis.pptx).

## License

This repository is for internal analysis and portfolio purposes. Add a license of your choice if publishing publicly.
