# 📊 Email-Campaign-Impact-Analysis-On-Drivers-using-A-B-testing:
A data analysis project using Excel to evaluate the impact of an A/B tested email campaign on driver activity. Features end-to-end ETL via Power Query and Exploratory Data Analysis (EDA) to measure performance lift.

🚀 Project Overview

This project evaluates the effectiveness of a driver engagement email campaign using Microsoft Excel. The goal was to determine if sending targeted emails successfully increased the number of rides completed by drivers over a one-week period.

![Email Campaign Drivers Dashboard](Email%20Campaign%20Drivers%20Dashboard.png)

🛠Tech Stack & Tools

📂Dataset Description

The analysis was performed on a dataset of 10,000 drivers, divided into two distinct groups:
Group A (Control): 5,000 drivers who did not receive the email.
Group B (Test): 5,000 drivers who received the email.
Metrics: driver_id, rides_within_week, test_group.

⚙️Technical Skills Applied

🧹 ETL (Extract, Transform, Load): Used Excel Power Query to clean the raw dataset, standardize group naming, and validate data types for 10,000 rows.
🔍 EDA (Exploratory Data Analysis): * Performed Range Analysis (Min/Max) to identify performance boundaries.

Utilized Pivot Tables to calculate averages and frequency distributions.
Analyzed "Zero-Ride" drivers to measure activation rates.

📈Data Visualization: Created a performance dashboard in Excel featuring Clustered Column Charts and Distribution Histograms.

💡Key Insights & Results

📈 Performance Lift: The campaign resulted in a 4.14% increase in average rides for the test group (Group B) compared to the control group (Group A).
🔢 Average Rides: Group B averaged 52.12 rides, while Group A averaged 50.05 rides.
🎯 The "Middle" Shift: While the control group had a higher individual max (120 rides), the email successfully lifted the performance of the entire test group, resulting in a higher overall average.

✅Conclusions:

The email campaign is a statistically successful tool for increasing platform activity. Based on the positive lift in average rides, the recommendation is to scale this campaign to the wider driver base to maximize revenue.
Lower Peak Performance: The "Super Drivers" in the control group (who didn't get an email) actually performed slightly better than the ones in the test group (120 vs. 114).
No Impact on Inactivity: Both groups still have a Min of 0. This tells you that the email failed to "wake up" the drivers who were doing zero rides.
Initial Conclusion: At first glance, the email might have been ineffective or even slightly distracting, as the test group (B) has a lower maximum than the control group (A).
Group A has a higher "Max," Group B have a slightly higher Average. This would mean the email helped the average person even if it didn't help the "superstar" drivers.






