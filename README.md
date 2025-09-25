🚗 OLA Mobility: Operations & Insights Dashboard

An interactive and comprehensive data dashboard designed to monitor and analyze key performance indicators for OLA's ride-hailing operations. The dashboard provides a holistic view of bookings, revenue, cancellations, and ratings across various vehicle types.

The OLA Mobility Dashboard is a dynamic Power BI report that gives stakeholders a real-time view of the platform’s performance. Its purpose is to help business leaders, operations managers, and data analysts understand trends in ride bookings, revenue generation, and customer/driver behavior, enabling data-driven decisions to optimize the service.

The dashboard was built using the following tools and technologies:

📊 Power BI Desktop – The primary data visualization platform used to create the interactive report.

📂 Power Query – Utilized for data cleaning, transformation, and preparing the raw operational data.

🧠 DAX (Data Analysis Expressions) – Used to create calculated measures, such as Cancellation Rate, Total Booking Value, and Average Distance Travelled.

📝 Data Modeling – Relationships established among tables to enable seamless cross-filtering and aggregation of data, for example, linking bookings to vehicle types and ratings.

📁 File Format – .pbix for development and .png for dashboard previews.

Source

Sample OLA data extracted from an Excel file provided via a website. The data includes detailed records of every booking, including the date, time, vehicle type, payment method, booking status (Success, Cancelled by Driver/Customer, Driver Not Found), booking value, distance, and associated driver and customer ratings.

Business Problem

In a fast-paced and highly competitive market like ride-hailing, OLA needs a single source of truth to monitor its operational health.
Key questions such as: "What is our current cancellation rate and why are rides being cancelled?", "Which vehicle type generates the most revenue?", and "How are our drivers and customers rating each other?" are difficult to answer without a unified and interactive reporting tool. Without this, it's challenging to identify bottlenecks, optimize fleet allocation, and improve the overall user experience.

Goal of the Dashboard

  i) To provide a centralized, interactive tool for monitoring and managing OLA's business performance.

  ii) To quickly uncover key trends and operational inefficiencies, such as high cancellation rates in specific categories or for certain        reasons.

  iii) To support strategic decisions related to revenue optimization, fleet management, and improving service quality.

Walkthrough of Key Visuals

1. Overall Page:

  a) Key Performance Indicators (KPIs): Displays the total number of bookings (103,024) and the total booking value ($35M), providing a         high-level summary of business activity.

  b) Booking Status Breakdown (Pie Chart): Visually represents the percentage of successful rides (62.09%) versus those that were               cancelled by either the driver or customer, or where a driver was not found.

  c) Ride Volume Over Time (Line Chart): Tracks daily booking count over the selected date range, revealing daily fluctuations and weekly       patterns in demand.

2. Vehicle Type Page:

  Vehicle Performance Table: A detailed table breaks down key metrics by vehicle type (e.g., Prime Sedan, Prime SUV, Auto, Bike). It shows   Total Booking Value, Success Booking Value, Avg. Distance Travelled, and Total Distance Travelled for each category, helping to identify   which vehicle types are most profitable and heavily used.

3. Revenue Page:

  a) Revenue by Payment Method (Bar Chart): Compares revenue generated from different payment methods (e.g., Cash, UPI, Credit Card),           highlighting the most popular and profitable payment options.

  b) Top 5 Customers (Table): A table listing the top 5 customers by their total booking value, which can be useful for loyalty and             marketing programs.

  c) Ride Distance Distribution per Day (Bar Chart): Shows the total ride distance covered each day, providing insights into travel             patterns and demand for long-distance rides.

4. Cancellations Page:

  a) Cancellation KPIs: Presents key metrics like Cancelled Bookings (28,933) and the overall Cancellation Rate (28.08%), a critical            metric for operational health.

  b) Cancelled Rides by Customers (Pie Chart): Breaks down customer-initiated cancellations by reason (e.g., "Wrong Address," "Change of        plans"), helping to identify common user issues.

  c) Cancelled Rides by Drivers (Pie Chart): Shows driver-initiated cancellations by reason (e.g., "Customer related issue," "Personal &        Car related issue"), providing insight into driver-side challenges.

5. Ratings Page

  a) Driver Ratings by Vehicle Type: Displays the average driver rating for each vehicle type, helping to identify potential quality            issues with specific categories.

  b) Customer Ratings by Vehicle Type: Shows the average customer rating for each vehicle type, providing feedback on the overall user          experience.

Business Impact & Insights

i) Operational Efficiency: The dashboard enables operations teams to pinpoint and address the root causes of high cancellation rates, leading to a more reliable service.

ii) Revenue Optimization: By analyzing revenue streams and ride distance, the company can tailor promotional offers and adjust pricing strategies to maximize profitability.

iii) Fleet Management: Insights from the "Vehicle Type" page help with smart fleet allocation and driver incentives for high-demand vehicle categories.

iv) Service Improvement: The ratings and cancellation data provide direct feedback, allowing OLA to improve both the driver and customer experience, which can lead to better retention and brand loyalty.

DashBoard Preview

![DashBoard Preview](https://github.com/ki2345/Ola_Project/blob/main/Snapshots%20of%20the%20DashBoard/Page_1.png)

![DashBoard Preview](https://github.com/ki2345/Ola_Project/blob/main/Snapshots%20of%20the%20DashBoard/Page_2.png)

![DashBoard Preview](https://github.com/ki2345/Ola_Project/blob/main/Snapshots%20of%20the%20DashBoard/Page_3.png)

![DashBoard Preview](https://github.com/ki2345/Ola_Project/blob/main/Snapshots%20of%20the%20DashBoard/Page_4.png)

![DashBoard Preview](https://github.com/ki2345/Ola_Project/blob/main/Snapshots%20of%20the%20DashBoard/Page_5.png)
