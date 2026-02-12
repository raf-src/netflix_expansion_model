Netflix Catalog Intelligence & Expansion Model
Overview
This repository contains a technical Excel-based analytics model designed to identify content inventory gaps and geographic market opportunities. Using a dataset of 8,789 titles, the model calculates a Market Gap Index and visualizes distribution trends to drive strategic content recommendations.

Data Transformation (ETL)
The master dataset was sourced from Kaggle and underwent the following cleaning process:

Deduplication: Identified and removed redundant entries, refining the count from 8,790 to 8,789 unique records.

Normalization: Standardized column headers (e.g., listed_in to Genre, show_id to Asset ID) for professional reporting.

Feature Engineering: Calculated Duration (mins) metrics and established the Market Gap logic based on geographic representation.

Core Components
DASHBOARD_UI: Frontend interface with high-level KPI cards for total inventory (7,268) and penetration metrics.

CORE_PIVOTS: Consolidated calculation engine for annual growth, genre splits, and regional distribution.

METRIC_LOGIC: Algorithmic sheet for the 55.90% Market Gap Index based on 109 unrepresented territories.

RAW_DATA: Normalized master dataset containing title metadata, ratings, and release years.

TALENT_DATA / GEO_DATA: Supporting pivot tables analyzing unique talent density and granular country stats.

Technical Implementation
Dynamic Architecture: All visuals are linked to live Pivot Tables on the CORE_PIVOTS tab for automatic updates.

Professional UI: Dark-mode aesthetic using Aptos Narrow typography and hidden interface elements for a standalone application feel.
