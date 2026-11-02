# Alfido Tech – Task 3: Website Traffic Analysis

## Dataset
Kaggle: https://www.kaggle.com/datasets/bhanupratapbiswas/website-traffic-analysis

The supplied ZIP contained `traffic.csv`. The notebook accepts `traffic.csv` or a ZIP named `archive.zip`; in Google Colab it prompts for upload if neither is present.

## Files
- `Alfido_Website_Traffic_Analysis.ipynb` – cleaning, event-level metrics, daily trends, country and content analysis.
- `Alfido_Website_Traffic_Analysis_Report.pdf` – detailed report, findings, recommendations and limitations.
- `Alfido_Task_3_Executive_Summary.pdf` – concise executive summary.
- PNG charts – event distribution, daily trend, top countries, artists and tracks.

## Headline results
- Event records: 226,278
- Distinct link IDs: 3,839
- Pageview events: 142,015
- Click events: 55,732
- Preview events: 28,531
- Date range: 2021-08-19 to 2021-08-25

## Important limitations
The dataset has no user IDs, session IDs, precise event timestamps, page URLs, referrer fields or duration fields. Therefore unique users, sessions, bounce rate, average session duration, user journeys, landing/exit pages and referral-source analysis cannot be calculated. The click/pageview ratio is an event-count ratio, not a conversion rate. The dataset covers only seven days.

## Run
Open the notebook in Jupyter or Google Colab, upload `traffic.csv` or the original ZIP when prompted, then run all cells from top to bottom.
