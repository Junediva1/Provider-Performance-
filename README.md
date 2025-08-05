# Provider-Performance-



PROJECT TITLE:  "Provider Performance Dashboard: Healthcare Analytics Project"


OVERVIEW: 
This project analyzes provider performance across a healthcare network using patient treatment data. The dashboard offers insights into treatment counts, medication usage, and patient readmission rates. Built using MySQL for backend data modeling and Power BI for visualization.

OBJECTIVE: Assist clinical leadership in optimizing care delivery

TOOLS USED: 
* SQL (MySQL) – for data cleaning, joining, and aggregation
* Power BI – dashboard creation, DAX measures, and interactive filtering
* Excel – initial data formatting
* ODBC Connector - for databasep to PBI pipleline

DATA MODELING:
Used a star schema with treatments as the fact table, linked to dimensions like providers, patients, admissions, and medication_lookup. Relationships enabled robust filtering across slicers.

KEY METRICS & VISUALS:
* Total Providers / Avg Treatments / Readmission Rate (KPI cards)
* Treatments by Provider (bar chart)
* Medication Distribution by Class (donut chart)
* Breakdown Table (highlighted for clarity)
* Slicers: Provider, Drug Class, Diagnosis Category, Date

CHALLENGES & SOLUTIONS:
Challenge: Power BI import wouldn’t accept MySQL data 
Solution: Used ODBC and SQL pre-calculation for smoother integration

WHAT DID I LEARN:
* Improved skills in SQL joins and relational modeling
* Learned Power BI’s DAX for KPI measures
* Practiced dashboard design with user experience in mind
* Enhanced troubleshooting skills under pressure


HOW WOULD I IMPROVE IT:
Use Power BI gateway and enhance user interactivity with drill-through pages by provider and drug class.
