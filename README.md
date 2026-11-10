# Maguna Distributors Sales & County Analytics
A simple Python script I put together to analyze wholesale distribution data, track product revenue, and spot regional sales gaps using SQLite, Pandas, and Matplotlib.
## What the Data Showed
* **Rice & Maize Flour are King:** Rice brings in KES 855k (48% of total revenue) and Maize Flour brings in KES 588k. Together, these two products drive **81% of all sales**.
* **Regional Split:** Nairobi (46.5%) and Kisumu (33.6%) make up 80% of total volume. 
* **The Mombasa Opportunity:** Mombasa is lagging behind at just 5.5%. If we allocate more stock and give it some attention, it could easily pull in an extra KES 500k+ per quarter based on Nairobi's numbers.
## What the Script Does
1. Sets up a local SQLite database with sample wholesale records.
2. Runs aggregations to calculate revenue share per county and product.
3. Automatically generates a two-panel bar chart and saves it as `maguna_analysis.png`.