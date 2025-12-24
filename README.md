
**1. Project Title / Headline**

Patient Wait List Analytics Dashboard
An interactive Power BI dashboard designed to monitor, analyze, and compare patient waiting list trends across specialties, case types, age groups, and time periods—supporting data-driven healthcare planning and performance monitoring.

**2. Short Description / Purpose**

The Patient Wait List Analytics Dashboard provides a comprehensive view of patient wait list volumes and trends over time. It enables healthcare analysts and decision-makers to track changes in waiting lists by specialty, case type, age profile, and time band, while comparing current performance against previous periods to support operational planning and resource allocation.

**3. Tech Stack**
The dashboard was built using the following tools and technologies:

• 📊 Power BI Desktop – Primary data visualization and reporting platform
• 📂 Power Query – Data ingestion, cleansing, and transformation of patient records
• 🧠 DAX (Data Analysis Expressions) – Used for time intelligence, comparisons (PY vs current), KPIs, averages/medians, and dynamic calculations
• 🧩 Data Modeling – Star-schema style relationships between fact tables (wait list data) and dimension tables (specialty, specialty group, case type, age profile, date)
• 📁 File Format – .pbix for development and .png for dashboard previews

**4. Data Source**

Source: Healthcare patient wait list records (Excel-based source files)

The dataset contains longitudinal patient wait list data, including:Specialty and specialty group mappings,Case type (Outpatient, Day Case, Inpatient),Patient age bands,Time bands for waiting duration,Archive dates for trend and year-over-year analysis

Data is structured into a main fact table (all_data) supported by mapping/dimension tables, enabling accurate aggregation, and cross-filtering.

**5. Features / Highlights**
**• Business Problem**

Healthcare systems must manage patient wait lists efficiently while balancing capacity, demand, and clinical priority. Raw wait list data alone makes it difficult to answer key operational questions such as:

Are waiting lists improving or worsening over time?

Which specialties contribute most to long waits?

How do inpatient, day case, and outpatient volumes differ?

Which age groups and time bands are most affected?

Without a centralized analytical view, identifying trends and pressure points is slow and reactive.

**• Goal of the Dashboard**

To deliver a clear, interactive, analytical tool that:

Tracks patient wait list volumes and trends over time

Compares current performance against previous periods

Highlights high-pressure specialties and case types

Supports data-driven planning, prioritization, and performance reporting

**• Walkthrough of Key Visuals**

**Key KPIs – Total Wait List Comparison (Top Left)**

Latest Month Wait List

Previous Year (PY) Latest Month Wait List
Provides an immediate snapshot of current demand versus historical performance.

**Global Filters (Top Panel)**

Archive Date range slider

Case Type slicer (Outpatient, Day Case, Inpatient)

Specialty Name slicer
Enables flexible, report-wide filtering for focused analysis.

**Case Type Split (Donut Chart)**
Displays the proportion of patients by:

Outpatient

Day Case

Inpatient
Helps understand demand distribution across care settings.

**Time Band vs. Age Profile (Stacked Column Chart)**
Analyzes patient volumes across:

Waiting time bands (e.g., 0–3 months, 6–9 months, 18+ months)

Age profiles (0–15, 16–64, 65+)
Highlights where extended waits disproportionately affect specific age groups.

**Monthly Trend Analysis (Line Charts)**

Day Case & Inpatient vs Outpatient trends over time

Archive-date-based trend comparison
Helps identify seasonal patterns, spikes, and long-term changes in demand.

**Top 5 Specialties Panel (Right Sidebar)**
Ranks specialties by:

Average or Median wait list size (toggle-enabled)
Quickly surfaces specialties under the highest pressure.


**• Business Impact & Insights**

**Operational Planning:**
Healthcare managers can identify growing wait list trends early and allocate staff or capacity accordingly.

**Performance Monitoring:**
Comparing the latest figures against prior periods enables a quick assessment of improvement or deterioration.

**Specialty-Level Focus:**
Highlights specialties requiring urgent intervention or resource rebalancing.

**Patient-Centric Analysis:**
Age profile and waiting time band insights help assess equity of access and patient risk exposure.

**Executive Reporting:**
The dashboard provides a concise, visually compelling summary suitable for leadership and stakeholder reviews.

**6. Screenshots / Demos**

<img width="665" height="377" alt="image" src="https://github.com/user-attachments/assets/1fecef27-3979-4c80-8858-0cc49b1a6782" />

Alt text: A dark-themed Power BI dashboard displaying KPIs for total wait list comparison, case type distribution, time band vs. age profile analysis, monthly trends, and a ranked list of top five specialties by average or median wait list size.
