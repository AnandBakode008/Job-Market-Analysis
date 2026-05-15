📊 Job Market Analysis — Power BI Dashboard & Report

A comprehensive end-to-end Job Market Analysis project featuring data collection, exploratory analysis, an interactive Power BI dashboard, and a paginated SSRS report — covering 2,191 job listings across industries, skills, salaries, and locations from 2020 to 2025.


📁 Project Structure
Job-Market-Analysis/
│
├── 📄 README.md                        ← You are here
├── 📊 Job_Market_Analysis.csv          ← Raw dataset (2,191 records)
├── 📈 Job_Market_Analysis.pbix         ← Power BI Dashboard file
├── 📋 Job_Market_Report.rdl            ← SSRS Paginated Report definition
└── 📑 Job_Market_Report.pdf            ← Exported PDF Report

🗂️ Dataset Overview
File: Job_Market_Analysis.csv
Records: 2,191 job listings
Time Period: January 2020 – December 2025
Sources: 15 platforms (LinkedIn, Naukri.com, Indeed, Glassdoor, Upwork, and more)
Columns / Features
ColumnTypeDescriptionjob_idIntegerUnique identifier for each job listingjob_titleStringTitle of the job rolecompany_nameStringName of the hiring companyindustryStringIndustry sector (e.g., IT Services, Healthcare Technology)job_locationStringCity/location of the jobemployment_typeStringFull-time, Part-time, Contract, Freelance, Internshipexperience_required_yearsIntegerMinimum years of experience required (1–12)salary_minIntegerMinimum salary (in USD/annual)salary_maxIntegerMaximum salary (in USD/annual)skills_requiredStringKey skills listed in the job postingeducation_requiredStringMinimum education qualificationposted_dateDateDate the job was originally postedscrape_dateDateDate the listing was scraped/collectedjob_sourceStringPlatform from which the listing was scraced
Key Statistics
MetricValueTotal Job Listings2,191Average Salary (Min)$36,016Average Salary (Max)$83,405Salary Range$15,000 – $120,000Avg. Experience Required~3.7 yearsIndustries Covered20+Cities Covered50+Job Platforms Covered15

📊 Power BI Dashboard
File: Job_Market_Analysis.pbix
Dashboard Highlights

📌 Top Job Roles — Most in-demand roles (Data Analyst #1 with 148 listings, Prompt Engineer, Data Scientist, Power BI Developer…)
🏭 Industry Breakdown — IT Services, HR Services, Product & SaaS, Telecom, Cybersecurity, and 15+ more
💰 Salary Analysis — Min/Max salary distributions by role, industry, and experience
🗺️ Location Heatmap — Job concentration by city (Gurgaon, Pune, Toronto, Delhi, Singapore…)
📅 Trend Over Time — Job posting trends from 2020 to 2025
🎓 Education & Skills — Education requirements and skills demand analysis
🧑‍💼 Employment Type Split — Full-time vs Part-time vs Contract vs Freelance vs Internship
🔗 Source Distribution — Which platforms list the most jobs

How to Open

Download and install Power BI Desktop (free)
Open Job_Market_Analysis.pbix
Explore all interactive pages and slicers


📋 SSRS Paginated Report
File: Job_Market_Report.rdl
Export: Job_Market_Report.pdf
The .rdl file is a SQL Server Reporting Services (SSRS) paginated report definition that produces a structured, print-ready report with:

Summary statistics table
Job listings breakdown by industry and role
Salary comparison tables
Location and source analysis

How to Use the RDL

Open Visual Studio with SSRS Report Designer or SQL Server Data Tools (SSDT)
Load Job_Market_Report.rdl
Connect to your data source (or point it at the CSV via an OLE DB connection)
Preview / Export as PDF


💡 Quick view: Open Job_Market_Report.pdf directly — no tools needed.


🔍 Key Insights

Data Analyst is the most demanded role (148 listings), followed by Prompt Engineer (59) and Data Scientist (57) — confirming the rise of AI/data roles.
IT Services and Human Resources Services dominate industry hiring.
Salary spread is wide — entry-level starts at ~$15K, senior roles can reach $120K.
Indeed and Referral are tied as top job sources (163 each), closely followed by Freelancer and TimesJobs.
Part-time and Freelance roles are nearly as common as Full-time, reflecting the gig economy trend.
Most roles require a Bachelor's in CS/IT/Statistics, reinforcing demand for technical graduates.
Gurgaon, Pune, and Toronto are top hiring hubs in the dataset.


🛠️ Tools & Technologies
ToolPurposeMicrosoft Power BI DesktopInteractive dashboard & data visualizationsSSRS / RDLPaginated, print-ready reportingPython / PandasData exploration & preprocessingCSVRaw data storage

🚀 Getting Started
Prerequisites

Power BI Desktop (free) — Download here
Optional: SQL Server Data Tools for .rdl editing

Steps
bash# 1. Clone the repository
git clone https://github.com/AnandBakode008/Job-Market-Analysis.git

# 2. Navigate to the project folder
cd Job-Market-Analysis

# 3. Open the dashboard
# Double-click Job_Market_Analysis.pbix in Power BI Desktop

# 4. Or explore the data with Python
python3 -c "import pandas as pd; df=pd.read_csv('Job_Market_Analysis.csv'); print(df.describe())"

📌 Use Cases

🎓 Students & Job Seekers — Understand which skills, roles, and locations are most in-demand
📈 HR & Recruiters — Benchmark salaries and track hiring trends
🧑‍💻 Data Analysts / Scientists — Use as a real-world practice dataset
🏢 Business Stakeholders — Use the Power BI dashboard for workforce planning decisions


📃 License
This project is open for educational and portfolio use. Dataset is synthetic/scraped for analysis purposes.

🙋 Author
Anand Bakode
Data Analyst | Aspiring Data Scientist
📧 aanandbakode807@gmail.com
🔗 https://www.linkedin.com/in/anand-bakode/
