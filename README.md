# 🌋 Vega-Lite Natural Disasters Dashboard

This project is a data visualization dashboard focused on **natural disasters in Southeast Asia between 2010 and 2021**, developed using Vega-Lite. It aims to provide an interactive and insightful overview of disaster patterns, impacts, and trends in the region, empowering policymakers, researchers, and the public to better understand and respond to natural disaster risks.

## Live Demo

> [View the Dashboard Here](https://juan-nathan.github.io/natural-disasters-dashboard/)

## Domain & Purpose

Natural disasters are a persistent threat in Southeast Asia, impacting millions of lives each decade. This visualization project was built to:

- **Understand** the frequency, type, and impact of natural disasters from 2010 to 2021.
- **Visualize** regional differences in disaster occurrence and severity.
- **Support** disaster risk assessment, preparedness, and policy-making.
- **Raise awareness** among citizens, researchers, and environmental agencies.

## Data Source

The dataset was sourced from [Open Development Mekong](https://data.opendevelopmentmekong.net/), and includes key attributes such as:

- Latitude and longitude  
- Disaster type  
- Number of deaths and injuries  
- Country and year of occurrence

The data has been cleaned, filtered, and restricted to natural disasters between 2010 and 2021.

## Technologies Used

- **Vega-Lite** for declarative and interactive data visualizations
- **HTML** for web structure, **CSS** for styling and design
- **Natural Earth Data** ([naturalearthdata.com](https://www.naturalearthdata.com)) for obtaining high-quality spatial data of country boundaries
- **Mapshaper** ([mapshaper.org](https://mapshaper.org)) for converting spatial data to TopoJSON format compatible with Vega-Lite
- **TopoJSON** for compact and accurate geographic representation, supporting efficient rendering, clean shape simplification, and native compatibility with Vega-Lite

## Visualizations & Features

This dashboard includes a variety of visualizations designed to highlight different aspects of the data:

### Maps
- **Proportional Symbol Map**  
  Circles represent both the **location** and **scale** of disaster impacts in terms of casualties, with colors indicating the disaster type.
- **Choropleth Map**  
  Color-coded risk levels per country, helping identify **high-risk regions** in Southeast Asia.

### Charts
- **Bar Chart**  
  Shows the **total frequency** of disasters per country for comparative insights.
- **Donut Chart**  
  Displays the **distribution** of disaster types within each country.
- **Stacked Area Chart**  
  Tracks the **trend of deaths** over time, showing changes in disaster severity across the years.
- **Lollipop Chart**  
  Highlights the **average death toll** per disaster type, identifying the deadliest disaster categories.

### Interactivity
The dashboard includes interactive filters for:
- Country  
- Disaster Type  
- Year

These filters help users customize their view based on specific interests or regions, making exploration more personalized and insightful.

## Key Insights

- Regional hotspots for frequent and deadly disasters
- Dominant disaster types per country
- Yearly trends showing spikes or declines in disaster deaths
- The deadliest disaster types

## Author

Developed by Juan Nathan.







