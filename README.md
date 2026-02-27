# Austin Bikeshare: Data Wrangling & Operational Analysis

### Project Overview
This project focuses on cleaning and analyzing city-scale bikeshare data for the Austin Transportation Department. The goal was to take raw, messy data and transform it into a reliable foundation for business decisions regarding bike availability, station performance, and rider behavior.

### **The Business Challenge**:
The department received complaints about:
* **Bike Availability**: Stations running empty during peak demand.
* **Inconsistent Performance**: Difficulty tracking station-level metrics due to data gaps.
* **Operational Outliers**: Erroneous trip durations skewing performance reports

### **Key Technical Steps**
1.  **Data Cleaning**: Standardized inconsistent station names and imputed missing values to ensure reporting accuracy.
2.  **Data Validation**: Filtered out "impossible" trips (durations > 24 hours or negative times) to remove noise.
3.  **Feature Engineering**: Created temporal features (hour, day) to identify peak usage patterns.
4.  **Visual Analysis**: Developed visualizations to identify high-traffic hubs and distinct rider behaviors.

### Key Insights
* **Peak Demand**: Usage spikes at Midday (12:00 PM), providing a clear window for scheduling maintenance during low-usage night hours.
* **High-Traffic Hubs**: A small number of stations (like 11th & Congress) handle nearly double the traffic of others.
* **Rider Behavior**: Short-term users take much longer trips on average than annual members, impacting bike turnover rates.

### **Tools Used**
* **Python** (Pandas)
* **Matplotlib & Seaborn** (Data Visualization)
* **Jupyter Notebooks**
