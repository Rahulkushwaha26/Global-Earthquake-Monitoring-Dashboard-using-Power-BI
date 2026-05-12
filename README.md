# Global Earthquake Monitoring Dashboard — Power BI
An interactive Power BI dashboard for real-time global earthquake monitoring using live USGS API data. Built as part of the Data Visualization course at JIIT Noida.

## About
Disaster management teams need a unified tool to track seismic activity in real time. This dashboard pulls live earthquake data from the USGS API and presents it through interactive visualizations — helping identify hotspots, depth patterns, and temporal trends instantly.

## Dataset
- Source: USGS Earthquake Hazards Program (Real-time CSV API)
- Period: 1 month, 2026 (refresh data)
- DAX Query for Depth category & Magnitude Category
  
Global map showing geographic distribution of all seismic events
Line chart of daily earthquake frequency over 30 days
Pie chart for magnitude category breakdown
Bar charts for top hotspot locations and depth categories
KPI cards — Total Earthquakes, Max Magnitude, Avg Depth, Unique Locations
Interactive slicers for Magnitude, Depth, Date Range, and Event Type

## Key Findings

- Max magnitude recorded, (Strong category)
- % of earthquakes are Very Shallow
- where is the top hotspot with highest no. of events ?
- Peak activity: on which day highest no. of earthquakes in a single day
- % of events are Major magnitude (5.0 and above)

## Tech Stack
Microsoft Power BI Desktop, DAX, USGS Real-time CSV API, Power Query
