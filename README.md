# 📈 Seattle Airbnb Tableau Dashboard Project

This repository contains a Tableau dashboard project built using the **Seattle Airbnb Open Dataset**. The project showcases skills in data preparation, blending, and visualization to answer key business questions around short-term rental profitability, seasonality, and property competition in Seattle.

---

## 🗂 Project Overview

The dataset comprises Airbnb listings, calendar pricing, and reviews data for Seattle. This beginner-friendly project demonstrates:

- Data joins and preparation across multiple sheets (Listings, Calendar, Reviews)
- Building a multi-page Tableau dashboard
- Applying a real-world use case: "Where should I invest in Airbnb properties in Seattle?"
- Filtering, mapping, and calculating KPIs like average price and seasonal trends

---

## 📊 Key Objectives

- Identify profitable neighborhoods based on zip code and pricing
- Visualize seasonal trends in bookings and pricing
- Analyze listing competition by bedroom count
- Map pricing geographically using Tableau
- Create an interactive and visually appealing dashboard

---

## 🚀 Features

- 🔄 Inner joins between Calendar and Listings using `listing_id`
- 🌆 Zip code level price visualizations (bar chart + map)
- ⏰ Revenue over time (time series by week)
- 🏠 Bedroom count vs. price and listing volume
- 🔣 Interactive filters on map for geographical insights

---

## 📂 Repository Contents

- `Seattle_Airbnb_Full_Dataset.xlsx`: Cleaned and merged dataset used in Tableau
- `Seattle_Airbnb_Dashboard.twb`: Tableau workbook with all dashboards and sheets
- `README.md`: Documentation and project guide (you are here)

---

## 📅 Data Sources

- Source: [Seattle Airbnb Open Data](http://insideairbnb.com/get-the-data.html)
- Year: 2016 (historic data)

Note: Data is slightly outdated but useful for demonstration. Feel free to update from the link above.

---

## ⚖️ Use Case

The dashboard answers the question:
> "As an investor, where and when should I buy and list an Airbnb property in Seattle to maximize revenue and minimize competition?"

Insights delivered include:
- Best zip codes for high average price
- High revenue seasons (summer and holidays)
- Relationship between bedrooms and pricing
- Competition distribution across property sizes

---

## 📆 Dashboard Visualizations

1. **Average Price by Zip Code**  
2. **Map of Seattle Zip Codes Colored by Price**  
3. **Revenue by Week**  
4. **Average Price by Bedroom Count**  
5. **Listing Count by Bedroom Count**

---

## 💼 Technologies Used

- Tableau Public / Desktop
- Microsoft Excel (for combining raw CSVs)


