# REQ102342_Wan-Huang
# Project: Dashboard Creation Utilizing BC Data Catalogue

Project Link
https://github.com/wan-huang/REQ102342_Wan-Huang.git


Dashboard Link
https://public.tableau.com/views/REQ102342_Dashboard_Wan-Huang/Dashboard?:language=en-US&:display_count=n&:origin=viz_share_link

Story Slide Link
https://public.tableau.com/views/REQ102342_StorySlide_Wan-Huang/BCSurgeryWaitTime?:language=en-US&:display_count=n&:origin=viz_share_link


# Project Overview 
BC Surgery Wait Time Monitoring and Analysis Dashboard 

Background:
- It is a well-known issue that the waiting time to receive medical services in BC has been long.
- The issue is likely to persist in the nearby future.
- This research aims to analyze historic surgery wait time data in BC to address the challenges.


Key Objectives:
- Analyze historic surgery wait time data to identify trends and patterns.
- Monitor the backlog of surgery cases in waiting over time.
- Investigate the impact of disruptive events, such as COVID-19, on surgery wait times.
- Identify procedures that suffer the greatest impact and those that resist impact.
- Examine population and hospital distribution to understand healthcare resource allocation.
- Create a tool for monitoring surgery wait times and identifying potential improvements.


Step 1: Dataset Exploration with Python Code 
- Utilized BC Data Catalogue API to extract relevant packages (datasets)
	- https://catalogue.data.gov.bc.ca/dataset/bc-data-catalogue-api
- Python code written to fetch datasets programmatically.
	- REQ102342_BC Data Catalogue API.ipynb


Step 2 
Identified datasets for dashboard creation 
- Dataset 1 Hospitals in BC https://catalogue.data.gov.bc.ca/dataset/hospitals-in-bc
- Dataset 2 BC Surgical Wait Times https://catalogue.data.gov.bc.ca/dataset/bc-surgical-wait-times
- Dataset 3 BC Population Projections https://catalogue.data.gov.bc.ca/dataset/bc-population-projections
- Dataset 4 B.C. COVID-19 Case Details https://catalogue.data.gov.bc.ca/dataset/b-c-covid-19-case-details

Rationale for Dataset Selection 
- 1. Hospitals in BC dataset provides insights into healthcare facilities' distribution and resources.
- 2. BC Surgical Wait Times data allows for monitoring and improving surgical processes.
- 3. BC Population Projections provide future population trends and demographic insights.
- 4. B.C. COVID-19 Case Details offer insights on impact on surgical services by disruption events. 


Step 3: Data Cleaning and Preparation
- Performed data cleaning to ensure data quality and consistency.
- Saved the cleaned datasets as CSV files for further analysis.


Step 4: Dashboard Creation in Tableau
- Developed interactive charts and visualizations in Tableau.
- Created a comprehensive dashboard and a compelling data story.


Key Insights:

1. Historic Surgery Wait Time Trends: 
Analyzing historic surgery wait time data reveals areas that require improvement and opportunities for optimizing resource allocation. Identifying trends can guide decision-making to streamline processes and enhance patient care.
2 Monitoring Backlog of Cases: 
Continuous monitoring of the backlog of surgery cases provides valuable insights for developing strategies to reduce wait times. Prioritizing and managing the backlog can lead to improved patient outcomes and increased efficiency.
3. COVID-19 Impact Analysis: 
Studying the impact of COVID-19 on surgery wait times provides insights into the healthcare system's resilience and adaptability during disruptive events. Lessons learned can inform preparedness for future challenges.
4. Identifying Procedures with Varying Impacts: 
Identifying procedures with differing impacts helps focus improvement efforts on high-impact areas. Tailored strategies can lead to faster service delivery and enhanced patient satisfaction.
5. Population and Hospital Distribution: 
Analyzing population and hospital distribution data contributes to optimizing healthcare resource allocation. Understanding regional needs can facilitate efficient service planning and equitable access to care.


Recommendations:

1. Dashboard as Decision-Making Tool: 
Utilize the interactive dashboard as a powerful decision-making tool for healthcare management. Regularly review key performance indicators to guide informed decisions and resource allocation.
2. Implement Targeted Strategies: 
Develop and implement targeted strategies to reduce wait times for procedures that are most impacted. Streamline processes, improve efficiency, and prioritize high-demand services.
3. Foster Healthcare System Resilience: 
Foster resilience in the healthcare system by developing contingency plans and response protocols for handling future disruptive events. Robust planning can mitigate the impact on patient care.
4. Consider Regional Factors: 
Consider regional population and hospital distribution while planning healthcare resource allocation. Tailor services to address specific needs and ensure equitable access to care across different areas.


Next Steps:

1. Deeper Analysis with Advanced Analytics: 
Conduct deeper analysis using advanced analytics and predictive modelling techniques. Explore predictive patterns to anticipate demand and optimize surgical scheduling.
2. Regular Dashboard Updates: 
Regularly update the dashboard with the latest data for real-time insights. Timely information ensures informed decision-making and facilitates proactive management of surgery wait times.
3. Collaborate with Healthcare Stakeholders: 
Collaborate with healthcare stakeholders, including clinicians, administrators, and policymakers, to implement improvement initiatives. Engage in data-driven discussions to drive positive change.

