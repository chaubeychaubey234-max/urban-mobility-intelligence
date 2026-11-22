# Urban Mobility Intelligence & Analytics

An analytics and data warehousing pipeline for urban trip records and weather datasets. This project explores data modeling, predictive analytics, association rule discovery, and spatial-temporal pattern identification.

## Repository Overview

- **`Urban_Mobility_Intelligence.ipynb`**: Interactive notebook executing data ingestion, cleaning, star-schema population, machine learning models, and evaluation routines.
- **`Urban_Mobility_Dashboard.html`**: Standalone HTML dashboard providing visualizations and analytical summaries.
- **`Urban_Mobility_Supporting_Files.zip`**: Complete bundle of supporting resources including the Power BI definition, database schemas, OLAP scripts, and statistical mining outputs.

## Key Capabilities

1. **ETL & Data Modeling**:
   - Uniform Bernoulli sampling across multi-month trip records.
   - Star schema data warehouse design (`FACT_TRIP` with associated dimension tables).
   - Relational database support for both SQLite and PostgreSQL.

2. **Data Mining & Analytics**:
   - Association rule discovery (Apriori) exploring relationships between temporal conditions, weather factors, and demand patterns.
   - Predictive classification and regression workflows benchmarking multiple machine learning algorithms.
   - Geospatial zone clustering and anomaly detection.

3. **Reporting & Business Intelligence**:
   - Integrated metrics reporting via interactive browser dashboard.
   - Power BI workspace integration.

## Usage Instructions

### Jupyter Notebook
Launch the analytical notebook:
```bash
jupyter notebook Urban_Mobility_Intelligence.ipynb
```

### Dashboard
Open `Urban_Mobility_Dashboard.html` directly in any web browser.

### Supporting Files
Extract `Urban_Mobility_Supporting_Files.zip` to access:
- Power BI project files (`.pbip`)
- SQLite database (`mobility.sqlite`) and PostgreSQL migration scripts
- Benchmark datasets and evaluation logs
