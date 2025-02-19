# EV Dashboard Analysis

## Overview
This project analyzes the growth of electric vehicles (EVs), the existing charging infrastructure, customer demographics, and energy consumption. The objective is to assess whether the current EV infrastructure can support the increasing number of electric vehicles. The project provides insights for stakeholders, including government organizations, business owners, and consumers, to make strategic decisions toward sustainable mobility.

## Key Features
- **Data Sources:** Government websites, EV analytics companies, OpenChargeMap, public datasets, and web scraping.
- **Data Processing:** ETL operations using Google Cloud Platform (GCP), Google Trifacta DataPrep, and MySQL.
- **Data Visualization:** Interactive dashboards created with Tableau.
- **Database Technologies:** BigQuery, Neo4j, and Kuzu (graph database for charging station analysis).
- **Programming & Tools:** Python, Pandas, NumPy, Seaborn, BeautifulSoup (for web scraping), and APIs.

## Methodology
1. **Data Collection:**
   - Vehicle models, registrations, charging station availability, and energy demand estimation.
2. **ETL Process:**
   - Data was extracted from multiple sources, transformed (cleaning, formatting, deduplication), and loaded into BigQuery.
3. **Analysis:**
   - Evaluated the adequacy of charging infrastructure using metrics like vehicle load per station and energy demand vs. supply.
   - Identified spatial and temporal trends in EV adoption and infrastructure growth.
4. **Visualization:**
   - Created interactive dashboards to analyze trends and gaps in EV infrastructure.

## Findings
- **Increasing EV adoption:** EV registrations have been rising since 2019.
- **Charging infrastructure gaps:** Public charging stations are growing at a slower rate compared to EV registrations.
- **Energy demand vs. supply:** There is a shortfall in energy supply, highlighting the need for more charging stations.
- **State-wise trends:** High adoption states (e.g., California) still have inadequate charging facilities in remote areas.

## Recommendations
- Expand public charging stations, particularly in high EV adoption states.
- Address disparities between public and private charging stations.
- Utilize data insights for policymaking and infrastructure development.
- Optimize underutilized stations for public use.

## Technologies Used
- **Cloud & Databases:** Google Cloud Platform (BigQuery), Neo4j, Kuzu, MySQL.
- **Data Processing:** Google Trifacta DataPrep, Python, Excel.
- **Visualization:** Tableau.
- **Version Control:** Git.
- **Task Management:** Jira.

## Team Members
- Kanchan Naik
- Mrunali Katta
- Prasad Shimpatwar
- Yashasvi Kanchugantla

## Repository
- [GitHub Repository](https://github.com/Yashasvi1225/electric_vehicles_analytics)

## Contact
For any queries, please reach out via the GitHub repository.

