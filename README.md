# NCDC-COVID-19-Report
### Table of contents

1. [Project Overview](#project-overview)  
2. [Data Source](#data-source)  
3. [Tools Used](#tools-used)  
4. [Analytical Process](#analytical-process)  
5. [Dashboard](#dashboard)  
6. [Executive Summary](#executive-summary)  
7. [Recommendations](#recommendations)  
8. [Conclusion](#conclusion)


## 1. Project Overview
This project offers a comprehensive, data-driven view of the COVID-19 pandemic as it unfolded across Nigeria. Built using real-time case data from the Nigeria Centre for Disease Control (NCDC), the dashboard highlights the national and state-level impact of the virus, tracking confirmed cases, recoveries, deaths, and active infections over time.
Designed for both public health stakeholders and analysts, the interactive dashboard presents clear trends, regional disparities, and health response patterns. It allows users to explore the data across multiple time frames and geographic filters to support data-informed decision-making during and after the pandemic.
By visualizing the evolution of the virus from early outbreak to eventual containment phases, the project serves as a digital historical record and a practical tool for understanding public health dynamics in Nigeria.

## 2. Data Source
The dataset was obtained from the official COVID-19 reports published by the Nigeria Centre for Disease Control (NCDC). It covers daily confirmed cases, recoveries, and death counts for each state in Nigeria. Each entry includes:
-	State name
-	Date of report
-	Number of confirmed cases
-	Number of recoveries
-	Number of deaths
From this dataset, additional fields such as Active Cases, Monthly Trends, and Total Aggregates were derived for analytical depth.

## 3. Tools Used
-	Microsoft Excel
Used for data cleaning, structure adjustment, column renaming, and preliminary calculations (e.g., active cases, data formatting).
-	Power BI
Utilized for dashboard design, DAX calculations, and interactive visualizations. Filters were applied to enable dynamic views by Year, Month, and State, while chart visuals conveyed trends and distributions clearly.

## 4. Analytical Process
**Step 1:** Data Cleaning and Transformation (Power BI Power Query Editor)
All data preparation was performed within Power BI using Power Query, ensuring the dataset was optimized for accurate analysis and responsive dashboards. Key steps included:
- Removed missing values and null records to ensure accuracy in case counts
- Filtered and validated state names to avoid duplication and spelling inconsistencies
- Standardized date formats to enable accurate monthly/yearly aggregations
- Derived active cases by calculating:

Active Cases = Confirmed Cases - Recoveries - Deaths
- Extracted month and year columns from the original date to analyze pandemic progression over time
- Sorted the dataset chronologically to support clean time series visuals and avoid temporal distortions

**Step 2:** Dashboard Creation and Design (Power BI Visual Layer)
Using Power BI’s visual and analytical capabilities, a fully interactive dashboard was developed with the following features:
- Dynamic trend analysis of total confirmed cases, deaths, and recoveries
- State-level heatmap to compare regional outbreak severity across Nigeria
- Month-over-month analysis to track the rise and fall of cases across different phases of the pandemic
- Top 10 States by Confirmed Cases using bar charts with tooltips and slicers
- KPI Cards to highlight national totals for Confirmed, Deaths, Recoveries, and Active Cases
- User controls including slicers for State, Year, and Month, allowing tailored insights for decision-makers
- Color-coded metrics for intuitive understanding (e.g., red for deaths, green for recoveries)

Each visual was purposefully placed to flow like a health status report — starting from total national figures, down to monthly trends, then drilling into state-specific views.

## 5. Dashboard
![NCDC](https://github.com/user-attachments/assets/ad693109-8ff2-4fe3-9ed5-d0358e552da4)

Access the interactive dashboard <a href=cv"https://app.powerbi.com/groups/me/reports/4c04da6f-1af3-4207-b039-9e07b11683ba/ReportSection?experience=power-bi">Here</a>

## 6. Executive Summary: Key Findings from the COVID-19 Nigeria Dashboard
This analysis offers a strategic overview of how COVID-19 affected Nigeria across time and space. By tracking real-time data on confirmed cases, recoveries, and deaths — and segmenting them by state, month, and year — the dashboard presents a compelling data narrative of the country’s response, outbreak intensity, and recovery trends.
From the initial waves through subsequent months, case patterns revealed both national and regional challenges. While some states consistently reported high case numbers, others saw more moderate impacts or periods of rapid recovery. Through structured filters and visual comparisons, this dashboard supports public health planning, resource allocation, and targeted policy interventions.

#### The Key Findings are as follows :
#### National Case Trends
-	**Confirmed Cases:** Nigeria recorded over 200,000 confirmed cases during the observed period, highlighting the significant scale of the pandemic.
-	**Deaths:** Fatalities exceeded 2,900 nationwide, with notable spikes during peak waves.
-	**Recoveries:** The country experienced a strong recovery rate, with more than 190,000 individuals recovering, showing the effectiveness of public health interventions.
-	**Active Cases:** Fluctuations in active cases were directly influenced by the timing of infection surges and recovery efficiency. Peaks occurred primarily during certain months, notably around mid-2020 and early 2021.

Time-based analysis reveals clear surges and declines across multiple waves, particularly in months like July, December, and January, reflecting global seasonal patterns and public movement trends

### Regional Analysis
-	Lagos State emerged as the epicenter of the pandemic in Nigeria, consistently reporting the highest confirmed cases, followed by FCT (Abuja), Rivers, and Kaduna.
-	Lagos alone accounted for a significant portion of national totals, underscoring its population density and economic centrality.
-	Other states like Kano, Plateau, and Oyo also experienced high transmission rates during specific periods.
-	The geographical breakdown shows that urban states bore the brunt of the virus, while others had sporadic outbreaks or maintained relatively lower figures.
This regional disparity points to the need for localized response strategies, particularly in high-density or high-mobility regions.

## 7. Recommendations
### National Public Health Strategy
-	**Strengthen Surveillance in High-Burden States:** Given that Lagos, FCT, and Rivers account for the highest case volumes, these states should remain focal points for testing, monitoring, and rapid response protocols.
-	**Enhance Preparedness During Peak Months:** Data trends show consistent spikes in December and January. Resources (e.g., test kits, hospital capacity, and public education) should be scaled up ahead of these periods to mitigate spread and strain on the health system.
-	**Monitor Recovery Patterns Closely:** While Nigeria recorded a commendable recovery rate, maintaining real-time recovery monitoring is essential to evaluate the long-term impacts and avoid post-recovery complications or reinfections.
### State-Level Interventions
-	**Tailor Interventions by Region:** The diverse distribution of cases across states indicates varying degrees of exposure, infrastructure, and public behavior. Health campaigns and containment measures should be region-specific, considering cultural, economic, and demographic differences.
-	**Empower Local Authorities:** Decentralizing certain decision-making and equipping state health departments with data tools can enhance localized responses, especially in under-resourced or high-density areas.
###Community Awareness & Behavior
-	**Reinforce Public Health Messaging:** Community compliance remains crucial. Data from active case waves should be used to inform more targeted, relatable messaging to encourage safe behaviors, particularly in regions with prior spikes.
-	**Focus on Urban Centers:** High-population cities such as Lagos and Abuja require ongoing engagement campaigns on mask usage, vaccination, and early testing, due to their higher exposure risks.
### Data Infrastructure & Reporting
-	**Invest in Real-Time Data Dashboards:** The effectiveness of this dashboard demonstrates the value of interactive tools in informing decisions. Expanding this capability to other health domains (e.g., vaccination coverage, maternal health) would strengthen national data governance.
-	**Standardize Data Collection Across States:** Ensuring consistency in how states report confirmed cases, recoveries, and deaths will improve the quality and comparability of national insights.

## 8.  Conclusion
The NCDC COVID-19 Nigeria Dashboard offers not just a historical account of the pandemic, but a strategic lens through which the nation’s preparedness and response capabilities can be examined and enhanced.
With over 200,000 confirmed cases, concentrated in urban and economically vibrant states, Nigeria's experience underscores the need for robust surveillance, flexible policy frameworks, and region-specific interventions. The consistent monthly trends, high recovery rates, and state-level disparities provide actionable insights for future epidemic response planning.
By leveraging data-driven tools like this dashboard, public health agencies, policymakers, and development partners can prioritize resources, tailor interventions, and ultimately build a more resilient health system—one that is informed, adaptive, and prepared for future public health threats.
