# Accident Location Analysis & Enhancing Road Safety

## Project Overview
This project focuses on improving road safety by analyzing accident-prone locations using advanced data analysis and geospatial tools. By leveraging real-time alerts, hospital proximity data, and ambulance services, we aim to enhance emergency response times, thereby reducing accident-related fatalities.

## The project integrates datasets related to:
+ Vehicle alerts (Forward Collision Warning, Pedestrian Collision Warning, etc.)
+ Road networks
+ Traffic conditions
+ Hospital and ambulance locations
+ Key Objectives
+ Accident Prone Location Detection: Using geospatial analysis to identify high-risk accident zones.
+ Emergency Response Optimization: Calculating the shortest path to nearby hospitals using Dijkstra's algorithm.
+ Ambulance Service Integration: Optimizing response time by integrating local ambulance data.
  
## Data Sources
+ Intel Corporation datasets for vehicle alerts and road conditions.
+ Hospital and Ambulance Services data in Chennai, Chengalpattu, and Kanchipuram near NH 32.
+ Geospatial data visualized using QGIS (Quantum Geographic Information System) and Kepler GIS.
  
## Features
+ Real-Time Alerts: Analysis of alerts like Forward Collision Warning (FCW), Pedestrian Collision Warning (PCW), and Headway Monitoring Warning (HMW).
+ Geospatial Mapping: Visualizing accident hotspots and nearby hospital locations.
+ Speed & Alert Type Correlation: Identifying patterns based on vehicle speed and type of alert.
+ Shortest Path Calculation: Utilizing Dijkstra's algorithm to determine the fastest route to the nearest hospital.
+ Ambulance Integration: Mapping of ambulance services to improve response times in emergencies.
  
## Technologies Used
+ QGIS: For mapping accident locations and plotting hospitals and ambulance routes.
+ Kepler GIS: For detailed geospatial data visualization.
+ Dijkstra's Algorithm: To compute the shortest path for ambulances to reach hospitals.
+ Machine Learning: Analyzing and visualizing accident data.
  
## Key Insights
+ Accident Hotspots: Identified accident-prone areas that require targeted interventions.
+ Alert Patterns: Headway Monitoring Warning (HMW) alerts are the most frequent, highlighting the importance of driver focus on maintaining safe distances.
+ Response Time Optimization: Enhanced hospital routing and ambulance dispatch times in accident situations.
  
## How to Run the Project
Clone the repository:
1. Copy code : git clone https://github.com/Keerthana203/IntelUnnati_Grand-Challenge
2. Install necessary dependencies.
3. Use QGIS and Kepler GIS to visualize geospatial data.
4. Run the scripts provided to analyze accident data and calculate shortest paths for emergency response.
   
## Future Enhancements
+ Extend the system to cover more regions and road networks.
+ Integrate additional real-time data sources like weather conditions and traffic congestion.
+ Implement IoT-based vehicle alert systems for proactive safety measures.

## References
+ Accident Locations on Indian Roads, 2023. Intel Unnati Training Program.
+ Traffic accident blackspot identification and ambulance fastest route mobilization process for the cities, Budiharto, U., Saido, A.P., 2012.
+ Black Spot Analysis Methods: Literature Review, K Gearts & G Wets, 2003.
+ Blackspot determination of accident locations & its spatial analysis based on GIS, Chen, H., 2012.
+ GIS – based spatial analysis of urban traffic accidents, Gholam Ali Shafabakhsh, 2017.
