# AirBNB-Dashboard- Analysis in Power Bi

This repository contains a Power BI dashboard built to analyze Airbnb listings data. The project leverages data from **Inside Airbnb** to explore key trends, pricing strategies, and host activity within a specific market.

The primary goal of this dashboard is to provide a comprehensive analytical tool for stakeholders (such as new hosts, market analysts, or data analysts) to understand the Airbnb landscape.

## 🎯 Problem Statement & Key Questions

This dashboard was designed to answer several core business questions based on the provided project brief. The primary objectives are:

> 1. Which are the popular neighbourhoods, their average prices and no. of listings?
> 2. What is the percent share of different property types and room types?
> 3. How the pricing is varying with location, property type, and reviews?
> 4. What are the different correlations between type of hosts and factors like- reviews & price?

 ## 📊 Data Source

* **Dataset:** [Inside Airbnb](https://insideairbnb.com/get-the-data/)
* **Provider:** [https://docs.google.com/presentation/d/12pA8u63PdpEPgurLP1Kyq0W_jy9HaNNqD6zxYaZ1Mwk/edit?slide=id.p#slide=id.p]

The data was sourced from Inside Airbnb and includes detailed listings data, such as pricing, availability, location (neighborhood), property type, room type, host information, and review metrics.

## 🛠️ Tools Used

* **Data Extraction:** Data downloaded from Inside Airbnb (`.csv` files).
* **Data Transformation (ETL):** **Power Query** (within Power BI) was used to clean, transform, and model the data.
* **Data Modeling & Analysis:** **Power BI Desktop**
    * Relationships were established between listings, reviews, and calendar data.
    * **DAX (Data Analysis Expressions)** was used to create custom measures for key metrics (e.g., Average Price, Occupancy Rate, YTD Bookings).
* **Data Visualization:** **Power BI**

## ✨ Key Features & Insights

The dashboard is organized into several pages, each focusing on a specific area of analysis:

* **Overview:** A high-level summary of key performance indicators (KPIs) such as **Total Listings**, **Average Price**, **Average Occupancy Rate**, and **Total Hosts**.
* **Price Analysis:**
    * An interactive map visualizing average listing prices by neighborhood.
    * Charts breaking down price distribution by room type and property type.
    * Analysis of how factors like ` accommodates`, `bedrooms`, and `bathrooms` impact pricing.
* **Host Insights:**
    * Analysis of host activity, including the distribution of listings per host.
    * Metrics on **Superhost** status, **Host Response Rate**, and **Host Response Time**.
* **Review Analysis:**
    * Visuals correlating the number of reviews and average review scores with listing popularity and price.

## 🚀 How to View the Dashboard

**Option 1: Power BI Service (Recommended)**

[**If you have published this to Power BI Service, paste the public web link here for easy viewing.**]

**Option 2: Using the .pbix File**

1.  Download and install [**Power BI Desktop**](https://powerbi.microsoft.com/en-us/desktop/) (it's free).
2.  Download the `AirBNB Dashboard.1.pbix` file from this repository.
3.  Open the file with Power BI Desktop to interact with the full dashboard.
