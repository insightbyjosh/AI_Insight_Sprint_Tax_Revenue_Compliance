# Scripts

This folder contains the analytical workflow used to validate and analyze the tax administration dataset.

## Analytical Tools

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook

## Analytical Workflow

1. Load the taxpayer, assessment, payment and tax-calendar datasets.
2. Validate data structure, completeness and relationships.
3. Identify payment and reconciliation anomalies.
4. Calculate revenue, payment and exposure metrics.
5. Analyze taxpayer, tax-type and geographic patterns.
6. Translate validated findings into management insights.
7. Connect analytical findings to Power BI dashboard measures and visualizations.

## Key Analytical Checks

The analysis included checks for:

- Missing values
- Duplicate records
- Invalid dates
- Invalid tax types
- Broken relationships
- Zero-value payments
- Pre-assessment payments
- Overpayments
- Assessments without payment records
- Revenue concentration by taxpayer segment and geography

Anomalies were retained as analytical signals rather than automatically removed.

> **Data Note:** The underlying dataset is simulated and was created for analytical demonstration and portfolio purposes.
