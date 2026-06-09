# 🚖 Uber Trip Insights: End-to-End Power BI Dashboard

A dynamic and interactive data visualization tool built to analyze Uber trip data, focusing on booking trends, revenue generation, trip efficiency, customer behavior, location insights, and time-based demand patterns.

The Uber Trip Insights Dashboard is a comprehensive Power BI report designed to analyze over 103,000 Uber trips and provide insights into booking performance, trip distances, revenue, and customer preferences. This dashboard helps business analysts and operations teams understand ride patterns and make data-driven decisions to improve operational efficiency and customer experience.

## . Tech Stack

The dashboard was built using the following tools and technologies:

* 📊 Power BI Desktop – Main data visualization platform used for report creation.
* 📂 Power Query – Data transformation and cleaning layer for preparing the dataset.
* 🧠 DAX (Data Analysis Expressions) – Used for KPI calculations, dynamic measures, and conditional logic.
* 📝 Data Modeling – Relationships established between tables to enable filtering, aggregation, and drill-through analysis.
* 🔖 Bookmarks and Buttons – Used for navigation, reset filters, and detailed data exploration.
* 🎨 Conditional Formatting – Applied to highlight important values and improve readability.
* 📁 File Format – .pbix for development and .png for dashboard previews.

## . Data Source

Source: Uber Trip Dataset (June 2024)

The dataset contains more than 103,000 trip records including booking details, trip distance, pickup and drop-off locations, vehicle types, payment methods, passenger count, and booking values.

The data is organized to support three analytical pages:

* Overview Analysis
* Time Analysis
* Details (Drill-through Page)

This structure enables users to analyze bookings, revenue, locations, and time-based trends through interactive visualizations.

## . Features / Highlights

### • Business Problem

Ride-sharing companies generate massive amounts of trip data daily, making it difficult to extract meaningful insights from raw records.

Key questions such as:

* What are the peak booking hours?
* Which vehicle types are preferred by customers?
* Which locations generate the highest demand?
* How much revenue is generated from bookings?
* How do booking patterns change across days and time periods?

are difficult to answer quickly without a visual analytical solution.

### • Goal of the Dashboard

To deliver an interactive visual tool that:

* Enables users to analyze booking trends and revenue generation.
* Supports operational decisions such as pricing and driver allocation.
* Identifies customer preferences and vehicle performance.
* Uncovers location-based and time-based demand patterns.
* Provides detailed trip-level analysis through drill-through functionality.

### • Walkthrough of Key Visuals

#### Key KPIs (Top Section)

* Total Bookings: 103.7K
* Total Booking Value: $1.6M
* Average Booking Amount: $15
* Total Trip Distance: 349K Miles
* Average Trip Distance: 3 Miles
* Average Trip Time: 16 Minutes

#### Date and City Filter Panel

Interactive slicers allow users to filter all visuals based on selected date range and city.

#### Payment Type Analysis (Donut Chart)

Shows booking distribution across:

* Uber Pay
* Cash
* Amazon Pay
* Google Pay

Helps understand customer payment preferences.

#### Trip Type Analysis (Donut Chart)

Compares:

* Day Trips
* Night Trips

to identify customer travel behavior throughout the day.

#### Vehicle Type Analysis (Table)

Displays:

* Total Bookings
* Total Booking Value
* Average Booking Amount
* Total Trip Distance

across different vehicle categories:

* UberX
* Uber Comfort
* Uber Black
* UberXL
* Uber Green

#### Daily Booking Trend (Line Chart)

Analyzes fluctuations in booking volume over days and helps identify peak and low-demand periods.

#### Location Analysis

Provides insights into:

* Most Frequent Pickup Point
* Most Frequent Drop-off Point
* Farthest Trip
* Top 5 Booking Locations
* Most Preferred Vehicle by Pickup Location

#### Pickup Time Analysis (Area Chart)

Shows booking patterns throughout the day using 10-minute intervals and helps identify peak demand hours.

#### Booking Trend by Day Name (Line Chart)

Displays booking distribution from Monday to Sunday and helps compare weekday and weekend demand.

#### Hour and Day Heatmap (Matrix)

Rows represent hours (0–23) and columns represent days of the week.

The heatmap highlights peak booking hours and busy days.

#### Details Page

A drill-through enabled table displaying:

* Trip ID
* Pickup Date
* Pickup Hour
* Vehicle Type
* Payment Type
* Number of Passengers
* Trip Distance
* Booking Value
* Pickup Location

allowing users to perform detailed trip-level analysis.

### • Business Impact & Insights

#### Operational Optimization

The dashboard helps identify peak demand periods and locations, enabling better driver allocation and improved service availability.

#### Revenue Analysis

Business teams can monitor booking values and average fares to optimize pricing strategies.

#### Customer Behavior Understanding

Insights into payment methods, vehicle preferences, and travel timings help improve customer experience.

#### Demand Forecasting

Location and time analysis assist in predicting future demand and optimizing resources.

#### Strategic Decision-Making

Transportation companies can use the dashboard to improve operational efficiency and make data-driven decisions.

## . Screenshots / Demos

Overview Analysis:
[https://github.com/siddhi1416-m/Uber-Trip-Insights-End-to-End-Power-BI-Dashboard/blob/main/snapshot%20.png](https://github.com/siddhi1416-m/Uber-Trip-Insights-End-to-End-Power-BI-Dashboard/blob/main/snapshot%20.png)
