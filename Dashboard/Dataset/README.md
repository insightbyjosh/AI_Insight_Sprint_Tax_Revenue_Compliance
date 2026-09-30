# Dataset

This folder documents the datasets used for AI Insight Sprint™ Case Study #2.

## Data Sources

The analytical model uses four datasets:

- `taxpayers_raw.csv` — taxpayer registration and demographic information
- `assessments_raw.csv` — tax assessment records
- `payments_raw.csv` — payment transaction records
- `tax_calendar.csv` — tax type and filing-frequency reference data

## Data Model

The datasets are connected through:

- `taxpayers_raw[taxpayer_id]` → `assessments_raw[taxpayer_id]`
- `assessments_raw[assessment_id]` → `payments_raw[assessment_id]`
- `tax_calendar[tax_type]` → `assessments_raw[tax_type]`

## Data Quality

The analytical review found no structural missing values, duplicate records, broken relationships, invalid dates or invalid tax types.

However, several records were identified as reconciliation signals, including zero-value payments, pre-assessment payments and payment amounts exceeding linked assessments.

These records were flagged for investigation rather than automatically removed.

> **Data Note:** The dataset is simulated and was created for analytical demonstration and portfolio purposes. It does not represent official Nigerian government revenue records.
