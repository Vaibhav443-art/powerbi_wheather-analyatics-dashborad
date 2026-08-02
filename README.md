🌦️ Weather Analytics Dashboard

Real-Time Weather Insights & Forecast Overview

An interactive Power BI / BI-tool dashboard that visualizes weather data across major Indian cities, covering temperature, humidity, visibility, wind speed, pressure, UV index, and rainfall.

📅 Filters
Date Range: 01-01-2025 to 29-06-2025
City: All (filterable)
Weather Condition: All (filterable)
📊 Key Metrics (KPI Cards)
Metric	Value
Avg Temperature	30.88 °C
Avg Humidity	65%
Avg Visibility	6.3 km
Avg Wind Speed	18.8 km/h
Avg Pressure	1010 hPa
Avg UV	6.2
Total Rainfall	6938 mm
🧩 Dashboard Components
1. Temperature by City (Map)

Geographic bubble map plotting temperature readings across cities including Delhi, Kolkata, Mumbai, Pune, Nagpur, and Hyderabad.

2. Count of AQI by AQI Category (Donut Chart)

Breakdown of Air Quality Index readings by category:

Very Unhealthy — 47 (26%)
Poor — 45 (25%)
Moderate — 37 (20.5%)
Unhealthy — 32
Good — 19 (10.56%)
3. Rainfall by City (Bar Chart)

Ranked rainfall totals by city, led by Mumbai and Delhi (1.1K each), down to Hyderabad (0.6K).

4. Summary of Weather (Table)

City-level breakdown showing Avg Temp, Sum of Temperature, and Sum of UV Index for Bengaluru, Chennai, Delhi, Hyderabad, Kolkata, and Mumbai, with a Total row (30.88 avg / 5559 sum).

5. Count of Weather Condition by Weather Condition (Donut Chart)

Distribution of weather conditions: Fog (34), Storm (26), Sunny (31), Rainy (30), Partly Cloudy (30), Snowy (29).

6. Sum of Wind Speed by City (Horizontal Bar Chart)

Wind speed totals led by Mumbai (500), Bengaluru (494), Delhi (454), Chennai (424), and Pune (423).

🎛️ Navigation Panel (Left Sidebar)

Icon-based quick filters/effects for:

🌡️ Temperature
🌬️ Fresh Air
🌧️ Rainfall
📈 Temperature Trend
👁️ Visibility
☀️ UV Ray
⚙️ Settings
🎨 Design Notes
Theme: Dark mode with high-contrast color-coded KPI cards (orange, blue, teal, indigo, purple, gold)
Layout: Card-based grid with map, donut charts, bar charts, and a summary table
Purpose: At-a-glance monitoring of weather patterns, air quality, and climate trends across Indian cities
🛠️ Suggested Tech Stack
Tool: Power BI (or similar BI platform)
Data Source: Weather API / CSV dataset with fields — City, Date, Temperature, Humidity, Visibility, Wind Speed, Pressure, UV Index, Rainfall, AQI, Weather Condition
Refresh: Real-time / scheduled refresh recommended for live insights
