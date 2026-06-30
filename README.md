# Significant Earthquakes Capstone
Capstone project analyzing data from NOAA about significant earthquakes.
<br>

## About the Data
* Source: [NOAA Significant Earthquakes Database](https://data.noaa.gov//metaview/page?xml=NOAA/NESDIS/NGDC/MGG/Hazards/iso/xml/G012153.xml&view=getDataView&header=none)
* Records: 6,273 significant earthquake events
* Time Period: Historical earthquake records through the present
* Data Includes:
  * Date and time
  * Magnitude
  * Intensity
  * Geographic location
   * Tsunami occurrence
   * Deaths, injuries, and damages
   * Regional classifications

## Project Overview
This capstone project analyzes the NOAA Significant Earthquakes dataset to identify global earthquake patterns, high-risk regions, and the impacts of significant earthquakes. Using the complete data analysis process, the project transorms historical earthquake records into insights that can support disaster preparedness and emergency planning.

## Problem Statement
Significant earthquakes are not evenly distributed around the world. Understanding where earthquakes are likely to cause the most damage helps governments, researchers, and emergency responders be prepared for disasters in high-risk areas.

## Business Questions
* Which regions experience the highest number of significant earthquakes?
* How has the frequency of significant earthquakes changed over time?
* Where are the global hotspots for significant earthquakes? 
* Which regions experience the highest number of tsunami-generating earthquakes compared to non-tsunami earthquakes?
* Which individual earthquakes caused the highest number of deaths, and what were their year, location, intensity, and tsunami occurrence?

## Data Prepartion
The dataset was prepared by:
* Removing unnecessary columns
* Checking for duplicates
* Handling missing values
* Converting region codes into region names
* Converting damage from millions of dollars to actual dollar amounts
* Preparting the data for analysis and visualization

## Key Findings
### Regions with the Most Significant Earthquakes
Over half of the significant earthquakes occurred in 4 regions (East Asia, Southern Europe, Central and South Pacific, Middle East). Those 4 regions are all located near intersections of tectonic plates and are near population centers.

### Earthquake Frequency Over Time
The recorded frequency of significant earthquakes increases over time, largely due to improvements in historical record keeping and increasing population growth that results in more documented high-impact events.

### Global Earthquake Hotspots
Earthquake hotspots are concentrated along major tectonic plate boundaries, particularly around the Pacific Ring of Fire. Earthquakes occurring near densely populated areas generally resulted in the highest death tolls.

### Tsunami vs. Non-Tsunami Earthquakes
Most regions experienced more non-tsunami earthquakes than tsunami-generating earthquakes. Ocean-based regions (Central and South Pacific, Caribbean, Kamchatka and Kuril Islands) had the highest proportion of tsunami-generating events.

### Deadliest Earthquakes
The deadliest earthquakes occurred widely across time and were primarily located in Asia and the Middle east. All of the deadliest earthquakes had MMIs of IX or higher.

## Power BI Dashboards
### Overview
![Overview Dashboard](/Dashboards/Overview.png)

### Region Breakdown
![Region Breakdown Dashboard](/Dashboards/Region_Breakdown.png)

### World Map
![World Map Dashboard](/Dashboards/World_Map.png)

## Tools & Technologies
* Google BigQuery
* SQL
* Python
* Pandas
* Matplotlib
* Jupyter Notebook
* Power BI

## Conclusion
This project demonstrates how historical earthquake data can be transformed into meaningful insights through data cleaning, exploratory analysis, and visualization. The analysis identified regions with the highest concentration of significant earthquakes, examined long-term trends, mapped global seismic hotspots, compared tsunami and non-tsunami events, and identified the deadliest earthquakes in recorded history.

While historical data cannot predict future earthquakes, it provides valuable context for understanding long-term seismic patterns and supports disaster preparedness, emergency response planning, and future research.

## Possible Improvements
* Real-time earthquake data
* Develop machine learning models
