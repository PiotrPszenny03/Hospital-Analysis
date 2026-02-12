HealthStat: Hospital Performance & Cost Efficiency Dashboard

<img width="1149" height="651" alt="image" src="https://github.com/user-attachments/assets/04bd8a63-07af-46dd-8b7f-b4059cdf0b76" />

🎯 Project Goal
The primary objective of this project was to analyze the operational efficiency and financial performance of hospital facilities in New York State.

Unlike standard reporting, this dashboard focuses on optimizing costs and reducing Length of Stay (LOS). It allows stakeholders to:

Benchmark facilities: Identify which hospitals are cost-effective vs. which are outliers.

Analyze drivers: Understand how clinical severity impacts financial outcomes.

Optimize operations: Find the "Sweet Spot" between quality of care and cost efficiency.

💻 Technologies & Tools
Microsoft Power BI – Main dashboarding tool for data visualization.

DAX (Data Analysis Expressions) – Used for complex measures, including Year-Over-Year growth and dynamic averages.

Power Query (M) – ETL process used for data cleaning and transformation (handling missing values).

AI Key Influencers – Machine Learning visual used for root cause analysis of stay duration.

📊 Key Insights & Visuals

<img width="1153" height="650" alt="image" src="https://github.com/user-attachments/assets/1ffa486b-e0a3-474d-8062-5a260dca8608" />

1. Cost vs. Efficiency Matrix
The Insight: I created a scatter plot correlating Average LOS (X-axis) with Average Cost (Y-axis).

Business Value: This visualization instantly highlights "expensive and slow" facilities (Top-Right quadrant) vs. "efficient" ones (Bottom-Left), serving as a primary tool for management benchmarking.

2. Root Cause Analysis (AI)
The Insight: Using Power BI's AI capabilities, I identified that Extreme Severity of Illness is the primary driver for increased Length of Stay (+8.89 days on average), rather than hospital inefficiency alone.

Business Value: This helps separate "justified" high costs (due to complex cases) from actual operational inefficiencies.

📂 Project Structure
The repository is organized as follows:

images/ - Folder containing screenshots used in this documentation (home_page.png, scatter_plot.png, etc.).

HealthStat_Dashboard.pbix - The main Power BI file. Download this to view the interactive report.

README.md - Project documentation (This file).

🚀 How to Run
Download the HealthStat_Dashboard.pbix file from this repository.

Open it in Power BI Desktop.

The dataset is embedded within the file, so no external SQL connection is needed to explore the insights.

👤 Author
Piotr Pszenny Aspiring Risk & Data Analyst 
