# Black Friday Sales Analysis

Retail analytics project exploring Black Friday purchasing behaviour through a Power BI report and a processed transaction dataset.

## Project Overview

The repository contains a Power BI report and a processed CSV dataset. The existing project documentation describes analysis across customer demographics, product categories, occupation, city segments, and purchase amounts.

**Scope note:** The current repository tree contains the dashboard and processed dataset, but no Python source scripts or notebooks. This README describes the available deliverables without claiming a reproducible Python preprocessing pipeline.

## Repository Contents

| Path | Description |
|---|---|
| `reports/Black Friday.pbix` | Power BI report |
| `data/processed/black_friday_cleaned.csv` | Processed transaction dataset |
| `requirements.txt` | Existing file; the repository contains no Python source that uses these dependencies |
| `LICENSE` | Copyright notice; not a complete license grant |

## Dataset

The processed CSV contains 783,667 rows and 12 columns in the inspected copy. The source, license, and transformation steps are not documented in the repository. The Power BI report and processed file are available, but the preprocessing cannot be reproduced from the current repository contents.

Document the following to improve transparency:

- Original dataset source, license, and attribution.
- Original and processed row counts.
- Column definitions and data types.
- Missing-value and duplicate handling.
- Treatment of categorical fields and product categories.
- Whether the Power BI report uses the processed CSV.

## Dashboard

Open `reports/Black Friday.pbix` in Power BI Desktop to inspect the report and interact with its filters and visuals.

The existing project documentation describes these analysis areas:

- Customer demographics
- Purchase distribution
- Product-category analysis
- City-category analysis
- Occupation analysis
- KPI cards and interactive filters

Add screenshots from the actual report after validating the pages and visuals.

## Technology

- Power BI
- CSV
- Python, Pandas, and NumPy are listed in the existing project documentation/dependency file; corresponding source pipeline files are not currently visible in the repository tree.

## Getting Started

1. Clone this repository.
2. Open `reports/Black Friday.pbix` in Power BI Desktop.
3. Explore the report pages and interactive filters.
4. Review the processed dataset in `data/processed/`.

## Reproducibility & Quality Improvements

- [ ] Record the original dataset source and license.
- [ ] Document the exact cleaning and transformation process.
- [ ] Add source scripts or a notebook only if they reflect the actual workflow.
- [ ] Add schema and data-quality checks.
- [ ] Document Power BI version and refresh instructions.
- [ ] Verify that the report opens and uses the intended dataset.
- [ ] Confirm redistribution rights for the dataset and report.
- [ ] Replace the current copyright-only `LICENSE` file with a recognized license only after confirming rights to license all included materials.

## Future Work

- Customer segmentation with a documented methodology.
- Predictive purchase modeling with a defined target and baseline.
- Sales forecasting if date-grained data is available.
- A reproducible preprocessing workflow if the original transformation logic can be recovered.

## Author

**Ahlad Novuduri** · [GitHub](https://github.com/AhladNovuduri)

