Overview
A technical model analyzing 8,789 titles to identify geographic inventory gaps. 

The project quantifies expansion opportunities through a custom Market Gap Index (55.90%).

ETL & Data Logic
Deduplication: Processed raw Kaggle source.

Normalisation: Standardised schema (e.g., Asset ID, Genre, Duration (mins)).

Metric Engineering: Defined Market Gap logic based on 109 unrepresented territories.

Workbook Architecture

DASHBOARD_UI: Strategic interface featuring KPI tracking and catalog heatmaps.

CORE_PIVOTS: Pivot engine for annual growth and regional distribution analysis.

METRIC_LOGIC: Calculation layer for geographic penetration indices.

CLEANED_DATA: Normalized master dataset.

TALENT_DATA / GEO_DATA: Supporting pivots for granular talent and country statistics.

Technical Notes

UI/UX: Dark-mode aesthetic with Aptos Narrow typography and hidden interface elements for a standalone application feel.

Portability: Built for fast interpretation by stakeholders, using centralised logic sheets to maintain data integrity.
