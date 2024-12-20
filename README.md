# EV-data-analysis



This project analyzes a dataset of electric vehicles to uncover trends, explore relationships between vehicle characteristics, and visualize key insights into the electric vehicle market. It combines data cleaning, exploratory data analysis, and advanced visualizations to provide actionable insights.

## Description

Electric vehicles are becoming increasingly popular due to their environmental benefits and technological advancements. This project focuses on analyzing various aspects of electric vehicles, such as their electric range, MSRP, geographic distribution, and eligibility for clean alternative fuel incentives (CAFV). The analysis helps identify trends, performance metrics, and market adoption patterns, making it valuable for manufacturers, policymakers, and consumers.

## Key Features

- **Data Cleaning**: Ensures the dataset is free of missing or inconsistent values.
- **Exploratory Data Analysis (EDA)**: Summarizes and explores the dataset's structure and trends.
- **Advanced Visualizations**: Includes interactive charts using Plotly and static plots using Seaborn/Matplotlib for clear insights.
- **Geospatial Analysis**: Highlights geographic distribution patterns for electric vehicles by state and city.
- **Trend Analysis**: Examines advancements in technology over the years (e.g., trends in electric range and MSRP).
- **Correlation Analysis**: Investigates relationships between electric range, MSRP, and other variables.

## Skills Used

- **Data Analysis**: Pandas and statistical insights.
- **Visualization**: Plotly, Seaborn, and Matplotlib for clear and interactive data presentations.
- **Geospatial Analysis**: Mapping vehicle distribution by state and city.
- **Programming**: Python for data processing, analysis, and visualization.

## Key Metrics

1. **Electric Range**: Distance a vehicle can travel on a full charge.
2. **Base MSRP**: Manufacturer's Suggested Retail Price.
3. **CAFV Eligibility**: Indicates whether a vehicle qualifies for clean alternative fuel incentives.
4. **Model Year**: Used to track advancements and production trends.
5. **Geographic Distribution**: Adoption patterns of electric vehicles across regions.

## Dataset

The dataset contains the following columns:
- `VIN (1-10)`: Partial Vehicle Identification Number.
- `County`, `City`, `State`, `Postal Code`: Geographic details.
- `Model Year`, `Make`, `Model`: Vehicle details.
- `Electric Vehicle Type`: EV classification.
- `CAFV Eligibility`: Indicates if the vehicle qualifies for clean fuel incentives.
- `Electric Range`: Distance covered on a single charge.
- `Base MSRP`: Manufacturer's Suggested Retail Price.
- `Legislative District`, `Electric Utility`, `2020 Census Tract`: Additional location and demographic data.

## Visualizations

- **Scatter Plot**: Relationship between MSRP and electric range.
- **Violin Plot**: Electric range distribution by model year.
- **Bar Chart**: Top makes based on electric range and MSRP.
- **Sunburst Chart**: Distribution of vehicle types by state.
- **Geographic Map**: Distribution of vehicles across the USA.
- **Correlation Heatmap**: Numeric variable relationships.
