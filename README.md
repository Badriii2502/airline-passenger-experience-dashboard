# ✈️ Airline Passenger Experience & Performance Dashboard

An interactive Power BI dashboard designed to analyze airline passenger satisfaction, service quality, flight delays, and passenger segments.

## 📊 Project Overview

This project transforms airline passenger survey data into an interactive business intelligence dashboard for analyzing passenger experience and operational performance.

The dashboard combines KPI monitoring, trend analysis, service-quality analysis, passenger segmentation, analytical insights, and detailed drill-through functionality in a single Power BI solution.

## 🎯 Objectives

- Monitor overall passenger satisfaction
- Analyze passenger experience across key service categories
- Examine the relationship between flight delays and passenger satisfaction
- Compare different passenger segments
- Identify factors associated with passenger satisfaction and dissatisfaction
- Provide detailed passenger-level drill-through analysis
- Implement service-based Row-Level Security (RLS)

## 🛠️ Tools & Technologies

- Microsoft Power BI
- DAX
- Power Query
- Data Modeling
- Row-Level Security (RLS)
- Drill-through
- Key Influencers
- Decomposition Tree

## 📑 Dashboard Pages

### 🏠 Home

A landing page providing navigation to the main analytical sections of the dashboard.

![Home](screenshots/home.png)

### 📌 Overview

Provides a high-level view of passenger experience and operational performance through key performance indicators and interactive filters.

![Overview](screenshots/overview.png)

### 📈 Trends

Analyzes relationships between passenger satisfaction, service quality, flight delays, flight distance, and customer characteristics.

![Trends](screenshots/trends.png)

### 💡 Insights

Uses Power BI analytical features such as Key Influencers and Decomposition Tree to explore factors associated with passenger satisfaction and dissatisfaction.

![Insights](screenshots/insights.png)

### 👥 Passenger Segment Details

A drill-through page providing detailed passenger-level information for a selected segment.

The page includes passenger demographics, travel characteristics, flight distance, departure and arrival delays, satisfaction, and service ratings.

![Passenger Segment Details](screenshots/passenger-details.png)

### 📋 Data

Provides access to passenger-level records for detailed data exploration.

![Data](screenshots/data.png)

## 🔐 Row-Level Security

The dashboard implements dynamic service-based Row-Level Security.

Users can be mapped to specific service categories, allowing service-specific users to access relevant service information.

The service categories include:

- Cleanliness
- Seat Comfort
- Baggage Handling
- Check-in Service
- In-flight Service
- In-flight Wifi Service

The implementation uses the logged-in user's identity and a user-service mapping table to determine the service-level access.

## 🔎 Drill-through Analysis

The Passenger Segment Details page supports interactive drill-through from the analytical pages.

Users can select a passenger segment and navigate to detailed passenger-level records, including:

- Customer Type
- Gender
- Type of Travel
- Class
- Flight Distance
- Departure Delay
- Arrival Delay
- Satisfaction
- Service Rating

## 📈 Key Metrics

The dashboard tracks key passenger experience and operational metrics, including:

- Total Passengers
- Satisfied Passengers
- Satisfaction Rate
- Average Arrival Delay
- Average Departure Delay
- Delayed Passenger Rate
- Average Service Rating

## 🧠 Analytical Features

The dashboard uses several Power BI analytical capabilities:

### Key Influencers

Identifies factors that are associated with changes in passenger satisfaction.

### Decomposition Tree

Enables interactive exploration of satisfaction across different passenger and operational dimensions.

### Interactive Filtering

Allows users to analyze passenger experience across dimensions such as:

- Age Group
- Class
- Customer Type
- Gender
- Type of Travel
- Flight Distance
- Delay Categories
- Satisfaction

### Drill-through

Enables users to move from aggregated dashboard insights to detailed passenger-level records.

## 🔧 Technical Implementation

Power Query is used for data preparation and transformation, while DAX measures are used for KPI calculations and analytical metrics.

The dashboard also incorporates:

- Interactive slicers
- Dynamic KPI calculations
- Service-level filtering
- Dynamic Row-Level Security
- Drill-through navigation
- Power BI analytical visuals
- Passenger-level data exploration

## 📂 Repository Structure

```text
Airline project/
│
├── README.md
│
├── dashboard/
│   └── Airline_Passenger_Experience_Dashboard_Final.pbix
│
└── screenshots/
    ├── home.png
    ├── overview.png
    ├── trends.png
    ├── insights.png
    ├── passenger-details.png
    └── data.png