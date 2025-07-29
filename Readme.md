# Atliq Hotels – Hospitality Data Analytics Project (End-to-End Power BI Dashboard)

This project focuses on analysing hotel operations data to uncover patterns, identify business inefficiencies, and deliver actionable insights. Using Atliq Hotels' datasets, I developed an interactive Power BI dashboard that reflects the hotel's current performance and provides strategic recommendations to enhance revenue and operational efficiency.

---

## Project Overview

The goal was to build a data-driven decision support system for Atliq Hotels by transforming raw booking data into business insights. This involved cleaning and modelling datasets, designing KPIs, and developing an intuitive dashboard that reveals key operational metrics such as revenue trends, booking patterns, occupancy rates, and customer satisfaction indicators.

---

## Situation (S)

Atliq Hotels faced declining profitability despite steady booking volumes. They lacked visibility into how online reviews, dynamic pricing strategies, and room utilisation impacted their bottom line. They needed a data analytics solution that could track key performance indicators (KPIs) and uncover areas for operational improvement.

---

## Task (T)

As a Data Analyst, my role was to:
1. Clean and transform raw datasets into an analysis-ready format.
2. Model the data using a star schema for efficient querying.
3. Define and implement business-critical KPIs (26 measures derived from client requirements).
4. Design a Power BI dashboard that provides a comprehensive view of the hotel's operational health.

---

## Actions (A)

- **Data Preparation with Power Query**  
  - Loaded five datasets (dim_date, dim_hotels, dim_rooms, fact_aggregated_bookings, fact_bookings).  
  - Performed data type corrections, merged relevant columns, and created calculated fields for metrics like revenue, occupancy, and cancellation rates.

- **Data Modelling (Star Schema)**  
  - Structured the data model by establishing relationships between dimension tables (Hotels, Rooms, Date) and fact tables (Bookings, Aggregated Bookings).  
  - Created a central **Metrics Table** to manage KPI calculations efficiently.

- **KPI Design & DAX Measures**  
  - Developed **26 KPIs** including Monthly Revenue, Occupancy Rate, Cancellation Rate, Booking Conversion Rate, Realised Revenue, No-show Rates, Platform-wise Revenue Distribution, and more.  
  - Applied DAX measures for advanced calculations like dynamic revenue adjustment based on booking status (Cancelled, No-show, Checked Out).

- **Dashboard Development in Power BI**  
  - Built an interactive dashboard with slicers and dynamic visualisations.  
  - Designed reports covering Revenue Trends, Booking Analysis, Room Category Utilisation, Customer Ratings, and Platform-wise Booking Patterns.

- **Business Insight Derivation**  
  - Analysed the impact of static pricing strategies across weekdays, weekends, and peak seasons.  
  - Evaluated online presence metrics, identifying that a lack of updated property photos and poor review management were contributing to a lower booking conversion rate.

---

## Results (R)

### Key Insights:
- **Static Pricing Inefficiencies**: Constant room rates across seasons/weekends caused a 15–20% revenue shortfall.
- **Booking Cancellations**: Identified a 25% increase in cancellations due to outdated property images and low customer ratings.
  
### Business Recommendations:
- Implement **Dynamic Pricing Strategies** across peak periods and weekends.
- Enhance online presence with regular photo updates and active review engagement to boost booking conversions.

### Impact Projection:
- The proposed strategies are estimated to improve profit margins by **30%**.

---

## Technologies Used

- Power BI  
- Power Query  
- DAX (Data Analysis Expressions)  
- Excel (for initial data validation)

---

## Project Structure

```
Atliq_Hotels_Analytics_Project/
├── README.md # Project documentation
├── datasets/
│ ├── dim_date.csv
│ ├── dim_hotels.csv
│ ├── dim_rooms.csv
│ ├── fact_aggregated_bookings.csv
│ └── fact_bookings.csv
├── metrics_list.xlsx # Document detailing 26 KPIs & definitions
├── PowerBI_Dashboard.pbix # Interactive Power BI dashboard file

```
---

## Conclusion

This project highlights how data analytics can transform raw hospitality data into meaningful insights that drive strategic decisions. By streamlining data workflows, creating business-focused KPIs, and delivering a user-friendly dashboard, the solution empowers Atliq Hotels to optimise pricing, improve customer experience, and boost profitability.

---

## Contact

Open to Data Analyst / Business Analyst roles.  
Feel free to connect for collaboration or project discussions:  
- Email: mathanponraj03@gmail.com  
- LinkedIn: [www.linkedin.com/in/mathan03](https://www.linkedin.com/in/mathan03)

---

