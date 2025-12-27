# Product Preferences Dashboard – Data Analysis Project
Author: Omotoso Oluwole Folorunso
Track: Data Analysis
Tool Used: Microsoft Excel
Project Type: Christmas Break Practical Project
GitHub: @OmotosoOluwoleF


# Project Overview
This project aims to develop a Product Preferences Dashboard that offers a clear, centralized view of customer preferences across various car models, body types, transmission types, colors, and regions.
The goal was to move beyond raw sales figures and instead express insights in percentages and trends, making it easier for stakeholders to quickly compare products and understand customer demand at a glance.

![Product Preferences Dashboard](Project-DASHBOARD.png)

# Objective of the Dashboard
The dashboard was designed to help stakeholders:
Track key performance indicators such as Total Cars Sold, Total Revenue, Average Order Value (AOV), and Year-on-Year (YoY) Growth
Identify market trends by highlighting the most preferred car models, body types, colors, and transmission options
Understand regional customer behavior and dealer-level performance
Enable faster, data-driven sales and marketing decisions

# Data Preparation (Power Query)
# 1. Dataset Loading
Imported the raw dataset into Excel
Verified column data types to ensure numerical and date fields were correctly formatted

# 2. Data Cleaning
Using Power Query, I performed the following cleaning steps:
Removed duplicates
Handled missing and null values
Standardized categorical fields (e.g., body type, transmission, color)
Ensured date fields were consistent for time-based analysis
Renamed columns for clarity and readability
This ensured the dataset was clean, reliable, and analysis-ready.


📊Key Calculations & Measures
All calculations were created using DAX to ensure accuracy and scalability.
🔹 Total Cars Sold
Calculated as the total count of cars sold across all transactions.

🔹 Total Revenue
Computed by summing the total sales value generated from car purchases.

🔹 Average Order Value (AOV)
Calculated as:
Average Order Value = Total Revenue / Total Cars Sold
This metric helps understand customer spending behavior.

🔹 Year-on-Year (YoY) Growth
YoY Growth was calculated by comparing the current year's revenue against the previous year, expressed as a percentage.
This provides insights into sales performance trends over time.

# Breakdown Analysis
The analysis was broken down across:
Car Models
Body Types
Transmission Types
Colors
Regions and Dealer Locations

To maintain clarity, any category with more than five labels was filtered to show only the Top 5, ensuring the visuals remained readable and actionable.

# Slicer Design Decision
Why BODY TYPE and not Company?
The final slicer was built using Body Type instead of Company because:
The dataset contains approximately 30 different companies
Using the company as a slicer would clutter the dashboard and reduce usability
Body Type provides a more intuitive and business-friendly segmentation that users can quickly relate to
This design choice improved user experience, performance, and insight clarity.

# Dashboard Development
After completing all calculations and breakdowns:
Clean, minimal visuals were selected
KPIs were positioned for quick executive visibility
Charts were aligned to support storytelling and comparison
Percentages were prioritized over raw figures to enhance interpretability

🔐 File Access & Security
The Excel file attached to this repository is encrypted to protect data integrity.
[View Dashboard](Project-DASHBOARD.png)
[Dataset](SecondDashboard.xlsx) 


🔑 Access Request

To request access to the file password, kindly send an email to:
holuworlex@gmail.com
Your request will be reviewed and access granted accordingly.

# Conclusion
This project strengthened my hands-on understanding of:
Data cleaning with Power Query
Writing meaningful DAX measures
Designing stakeholder-friendly dashboards
Making informed, analytical, and UX decisions
It reflects my growth as a young data analyst and my ability to translate raw data into actionable business insights.

Feedback, collaboration, and suggestions for improvement are welcome. [Meet me on LinkedIn](https://www.linkedin.com/in/omotosooluwole/)


