## RideInsights 50K: Decoding Bengaluru’s Ola Patterns with SQL


This project analyzes 50,000 Bengaluru Ola ride bookings using SQL to uncover insights on customer behavior, driver performance, cancellations, revenue trends, and ride patterns. It demonstrates data-driven decision-making and practical SQL-based analysis for large-scale ride-hailing data. The project also highlights key operational challenges and opportunities to optimize service efficiency.

## Project Goals / Objectives (Enhanced & Unique Version)
- Simulated a real-world ride-hailing environment by enforcing realistic constraints (success rate 62%, cancellations under 38%, incomplete <6%).
- Designed a dual-perspective analysis capturing both customer and driver behavior — a rare dimension in most SQL projects.
- Discovered match-day and weekend surge patterns, connecting ride data with city-level events, enhancing demand forecasting.
- Built data integrity rules to reflect operational limits and realistic booking trends, improving dataset authenticity.
- Derived actionable KPIs such as revenue by payment mode, top spenders, and rating correlations to enhance service strategy.
- Structured a scalable SQL pipeline from raw CSV import to final insights, mimicking real industry workflow.



# Dataset
- **Dataset:** Bengaluru_Ola_Booking_Data.csv (50,000 records)  
- **Columns include:** Date, Time, Booking ID, Booking Status, Customer ID, Vehicle Type, Pickup & Drop Location, Ride Distance, Booking Value, Payment Method, Driver Ratings, Customer Ratings, Cancellation Details, etc.


# Dashboards Highlights
The dashboards provide a high-level overview of key business metrics and trends.

📊 Overall Performance
- Total Booking Value: 34M
- Total Bookings: 50K
- Successful Bookings: 33K (a success rate of approximately 67%)
- Total Distance Travelled: 851K km
- Average Customer Trip Arrival Time (CTAT): 10 minutes
- Average Vehicle Trip Arrival Time (VTAT): 7 minutes

<img width="1368" height="774" alt="Overall_Dashboard" src="https://github.com/user-attachments/assets/36ed9d31-f802-4526-be8d-e7ef4f4accad" />


# Technologies Used
- SQL (MySQL Workbench) for data extraction, cleaning, and analysis
- Power BI (optional) for visualization
- GitHub for version control


