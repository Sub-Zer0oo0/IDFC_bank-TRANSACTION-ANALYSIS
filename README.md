# IDFC_bank-TRANSACTION-ANALYSIS
Interactive Excel banking dashboard that visualizes transaction data by domain, location, and month, using pivot tables, slicers, and charts to track total value, transaction count, and average ticket size for faster decision-making

Feature

One of the best parts of working on this project was handling a large‑scale dataset of over 1 million transaction records, which made the analysis more realistic and closer to production‑level banking data.

Project overview


Interactive Excel dashboard for an Indian bank that summarizes transaction data by domain, location, and time period.

Built entirely in Excel using pivot tables, slicers, formulas, and charts to transform raw transaction data into decision-ready insights.

Data and metrics
Tracks total transaction value, total transaction count, and average transaction value as key KPIs at the top of the dashboard.
Breaks down transaction values by business domain (Retail, Restaurant, Public, Medical, Investments, International, Education) to highlight which segments drive the highest volume and value.
Uses a time slicer to filter transactions by month, enabling quick analysis of seasonality and monthly performance trends.
Includes a full list of cities/branches as slicers, allowing users to drill down to specific locations and compare regional performance.

Visuals and analytics
Horizontal bar chart for “Domain Contribution by Location” to compare transaction value across domains and identify top-performing and underperforming segments.
Pie chart for “Monthly Transaction Value Contribution” to show percentage share of each domain in total monthly transaction value.
Line chart of “Transaction Value” over months to detect trends, spikes, or dips that may indicate seasonality, campaigns, or operational issues.

Key analytical takeaways
You can list bullets like these as insights you would typically derive from the dashboard (replace with your actual observations from the data):
Certain domains (for example, Retail or Medical) contribute the largest share of total transaction value, indicating where the bank’s revenue base is concentrated.
Locations such as metro or Tier‑1 cities may show higher average transaction value, while other locations contribute more to transaction count, hinting at different customer profiles and product needs.
Monthly line chart may reveal peak transaction periods (festive seasons, quarter ends) that can inform staffing, marketing campaigns, and risk monitoring.
Comparing average transaction value with total transaction count helps distinguish high‑value, low‑volume segments from low‑value, high‑volume segments for targeted cross‑sell strategies.
Domain and location filters together can uncover branches or cities where specific domains (e.g., Education or International) are underpenetrated, suggesting opportunities for product expansion.

Technical points to mention
Data preparation: cleaning and standardizing transaction dates, locations, and domain categories before building pivot tables.
Use of pivot tables for aggregation by domain, city, and month, and use of slicers for interactive filtering.
Custom formatting for Indian currency, KPI cards, and conditional formatting to make important numbers stand out.
Modular workbook structure with separate sheets for raw bank dataset, pivot tables, and the final dashboard layout.

