# data-operations-it-assets_1  
Mini project - writing python code for uploading local file to elastic search

# Data Operations on IT Assets

## 📌 Overview of Each Phase

1. **Phase 1: Data Collection**
   - Imported raw asset data from Excel (`it_asset_inventory_cleaned.csv`).

2. **Phase 2: Data Cleaning**
   - Cleaned and standardized fields like `country`, `operating_system_provider`, and `lifecycle_status`.

3. **Phase 3: Indexing**
   - Indexed the cleaned data into Elasticsearch for visualization in Kibana.

4. **Phase 4: Visualization**
   - Created pie charts and bar graphs for:
     - Assets by Country
     - Lifecycle Status Distribution
     - High vs Low Risk Assets
     - Top OS Providers

5. **Phase 5: GitHub Submission**
   - Organized project files and insights into a structured repository.

---

## 🧹 Excel Cleaning Techniques Used

- Removed duplicates and null values.
- Standardized country names to uppercase.
- Normalized lifecycle status values (`EOL`, `EOS`, `Planned`, etc.).
- Converted date formats to ISO standard.
- Categorized performance scores into risk levels.

---

## 🐍 Python Scripts and Their Purpose

- `index_data.py`: Script to index cleaned data into Elasticsearch.
- `transform_data.py`: Script to transform and categorize data (e.g., risk levels).

---

## 🖼️ Screenshots

Screenshots of successful:
- Data indexing
- Data transformations
- Kibana visualizations

Stored in: `visualization_screenshots/`

---

## 📊 Final Business Insights

- **19.51% of assets are EOL** — indicating an urgent need for OS upgrades, especially in **UNKNOWN** and **INDIA**.
- Majority of assets are concentrated in a few countries, suggesting regional infrastructure focus.
- SUSE and RedHat are among the top OS providers, highlighting reliance on Linux-based systems.



