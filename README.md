

📊 LinkedIn Data Analyst Job Market Daily Insight Dashboard

🧩 Project Overview

This project presents an interactive Excel dashboard that provides a daily insight into the Data Analyst job market based on job postings collected from LinkedIn.
The goal of this analysis is to uncover hiring trends, top recruiting companies, and most in-demand job locations for data analysts across different regions.

By analyzing the job posting frequency and employer patterns, this dashboard helps job seekers, career planners, and recruiters make informed decisions about market demand and opportunities.


---

🧹 Data Cleaning and Standardization Process

Before building the dashboard, the dataset underwent a comprehensive data cleaning and transformation process using tools like Excel and Power Query to ensure accuracy and consistency.
Here’s a breakdown of the process:

1. Data Collection

Data was scraped from LinkedIn job postings for the months of April and May.

The dataset included fields such as:
Job Title, Company Name, Location, Date Posted, and Job Description.


2. Data Cleaning

To ensure the dataset was analysis-ready, several cleaning steps were performed:

Removed Duplicates: Eliminated repeated job postings based on job title and company name.

Handled Missing Values: Filled or removed incomplete records (e.g., missing locations or company names).

Standardized Column Headers: Renamed columns to consistent lowercase format (e.g., job_title, company, location, date_posted).

Date Format Standardization: Converted posting dates into a uniform format (YYYY-MM-DD) to enable trend analysis by day.

Trimmed Whitespace and Special Characters: Cleaned unnecessary spaces and non-alphanumeric symbols in text fields.

Filtered Irrelevant Roles: Removed non-Data Analyst related roles (e.g., “Data Engineer”, “Data Scientist”) to keep the focus on analyst positions.


3. Data Transformation

Created Day of Week Column: Extracted the day name from each posting date to visualize daily posting trends.

Grouped and Aggregated Data: Summarized job postings by day, company, and location for easy comparison.

Standardized Company Names: Corrected inconsistencies like “Meta Platforms Inc.” vs “Meta” to avoid duplicates in visualization.



---

📈 Dashboard Insights

The Power BI dashboard provides three major insights sections:

🔹 1. Daily Trend on Job Posting

Displays the number of job postings per day (Sunday–Saturday).

Shows a clear pattern where mid-week (Tuesday & Wednesday) has the highest job postings (133–138), while weekends have the least activity (Sunday: 11, Saturday: 44).

Insight: Recruiters are most active during the workweek — suggesting optimal application timing for job seekers.


🔹 2. Top 10 Companies Hiring

Highlights the top organizations recruiting data analysts.

Leading companies include Meta, Netflix, Amazon, Google, TikTok, Spotify, among others.

Insight: Big tech and digital-driven companies are the major employers in the data analytics job market.


🔹 3. Top 10 Job Locations

Ranks locations with the highest number of data analyst openings.

United States and San Francisco lead with 63 job postings each, followed by London, Gurgaon, Los Angeles, and Washington D.C.

Insight: Data analytics roles are concentrated in tech-centric and metropolitan areas, with strong opportunities in the U.S. and global tech hubs.



---

🧠 Key Insights Summary

Peak posting days: Tuesday and Wednesday

Lowest activity days: Sunday and Saturday

Top hiring companies: Meta, Netflix, Amazon, Google

Most active job markets: United States and San Francisco

Overall trend: Data Analyst hiring is highly weekday-driven, dominated by major tech firms and global hubs.



---

🛠 Tools & Technologies Used

Data Source: LinkedIn Job Postings

Data Cleaning: Microsoft Excel, Power Query

Data Visualization: Power BI

Data Transformation: DAX measures and calculated columns for dynamic insight

---

🚀 Conclusion

This dashboard provides an evidence-based overview of the current Data Analyst job market on LinkedIn.
It can serve as a career guide for job seekers, a recruitment planning tool for HR professionals, and a market insight reference for analysts.

By combining clean, standardized data with an intuitive visualization, the project demonstrates practical data analysis skills — from cleaning and transformation to insight storytelling.


---

👩‍💻 Author

Jessica Nwachukwu
Data Analyst | Excel | Power BI | SQL | Python


