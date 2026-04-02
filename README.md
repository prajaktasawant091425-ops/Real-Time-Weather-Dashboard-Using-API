# Real-Time-Weather-Dashboard-Using-API
# COMPANY : CODETECH IT SOLUTIONS
# Name : Prajakta Sujit Sawant
# Intern id : CTIS6799
# Domain : Power BI
# Duration : 4 Weeks
# Mentor : Neela Santosh
# Description : Live Weather Monitoring Dashboard

🌦️ Live Weather Monitoring Dashboard

🔹 Project Overview<br>
• The Live Weather Monitoring Dashboard is a real-time Power BI dashboard that tracks and visualizes weather conditions across multiple cities using data from the OpenWeather API.<br>
• This dashboard provides live insights into temperature, wind speed, visibility, and atmospheric pressure, helping users monitor environmental conditions dynamically.<br>
• It demonstrates the integration of API-based real-time data with Power BI, enabling continuous data updates and interactive analysis.

🎯 Objectives<br>
• Monitor real-time weather conditions across cities.<br>
• Compare temperature and environmental metrics.<br>
• Visualize weather patterns and conditions.<br>
• Enable dynamic filtering by city and weather type.<br>
• Provide actionable insights using live data.

📈 Key Insights<br>
📌 Pune recorded the highest temperature (~37.9°C).<br>
📌 Shimla is the coolest city (~18°C).<br>
📌 Majority weather condition is Cloudy (~50%).<br>
📌 Wind direction indicates dominant South-West flow.<br>
📌 Visibility and pressure remain relatively stable across cities.<br>
📌 Coastal cities show slightly higher humidity-related conditions.

⚙️ Tools & Technologies Used : <br>
Power BI Desktop → Dashboard creation.<br>
OpenWeather API → Real-time data source.<br>
Power Query → API connection & transformation.<br>
DAX → Calculated measures.<br>
Map Visuals → Geospatial representation.

API Integration (OpenWeather)
How Data is Connected:<br>
• Used Web Connector in Power BI<br>
• Integrated OpenWeather API using:<br>
• API Key<br>
• City parameters<br>

🛠️ Task Implementation (How It Was Performed)<br>
Step 1: API Data Extraction<br>
 Connected Power BI to OpenWeather API <br>
 Pulled JSON data for multiple cities<br>
 Converted JSON → Table format

Step 2: Data Transformation (Power Query)<br>
Extracted fields:<br>
Temperature<br>
Pressure<br>
Wind Speed<br>
Visibility<br>
Weather Condition<br>
Converted temperature:<br>
Kelvin → Celsius

Step 3: Data Modeling<br>
Created structured table for all cities<br>
Ensured consistent schema for analysis

Step 4: DAX Calculations<br>
Created measures like:<br>
Avg Temperature<br>
Avg Wind Speed<br>
Avg Visibility<br>
Avg Pressure<br>

Advanced Features Used

✅ Real-Time API Integration<br>
Data updates dynamically whenever refresh is triggered.<br>
Ensures dashboard always reflects latest weather conditions.<br>

✅ Conditional Formatting (Gauge Visual)<br>
Gauge dynamically changes based on wind direction/value.<br>
Provides visual indication of intensity and direction changes.<br>

🚀 Conclusion

This dashboard demonstrates how real-time API data can be integrated into Power BI to build dynamic and interactive reporting solutions.<br>
It helps users:<br>
Monitor live weather conditions<br>
Compare cities effectively<br>
Understand environmental patterns<br>

OUTPUT :
<img width="1665" height="690" alt="image" src="https://github.com/user-attachments/assets/2b98fcdf-19ae-4a50-a4be-4f5b936d7c60" />

