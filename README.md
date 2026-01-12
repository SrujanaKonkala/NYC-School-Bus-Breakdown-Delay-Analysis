# NYC-School-Bus-Breakdown-Delay-Analysis
## Project Overview
**Client:** New York Division of Transportation  
**Scenario**
I was hired as a Data Analyst to improve the efficiency and reliability of the NYC school bus transportation system. The city has faced significant service disruptions, causing commuter inconvenience and straining public resources. My task was to analyze incident patterns to identify the root causes of delays and identify the least reliable service providers.

## Objectives
The analysis addressed three primary operational questions:
1.  **Common Reasons:** What are the most frequent causes of delays and breakdowns?
2.** Vendor Performance:**How do delay times vary by bus company and borough?
3.  **Temporal Trends:** Is there a correlation between the day of the week and incident frequency?

## Data Dictionary
The analysis utilized the following key fields:
* **Busbreakdown_ID:** Unique identifier for each incident.
* **Reason:** The cause of the delay (e.g., Heavy Traffic, Mechanical).
* **Bus_Company_Name:** The vendor responsible for the route.
* **How_Long_Delayed:** The duration of the service gap.
* **Occurred_On:** Date and time of the incident.
* # NYC School Bus Operational Reliability Analysis

## 🔍 Detailed Analysis & Visualizations

### 1. Root Cause Analysis: Why are buses failing?
I analyzed the data by distinguishing between "Breakdowns" (mechanical) and "Running Late" (external/traffic).
<img width="1723" height="691" alt="image" src="https://github.com/user-attachments/assets/932919e1-e2a2-4fd3-be55-3300124e0ebe" />


#### **Chart 1: Top Reasons for Breakdowns**
* **Finding:** Mechanical problems (10,399) and "Won't Start" (2,970) are the leading causes.
* **Insight:** These are "internal" failures that the city can control through stricter maintenance audits.

#### **Chart 2: Top Reasons for Running Late**
* **Finding:** Heavy Traffic is the overwhelming cause of non-mechanical delays.
* **Recommendation:** Prioritize route optimization for the most congested corridors identified in the dataset.

---

### 2. Geographic & Vendor Performance
This section highlights the variance in delay times across different bus companies and city boroughs.
<img width="977" height="692" alt="image" src="https://github.com/user-attachments/assets/0ba69fe0-7fdd-4938-a0e7-1d9122cc9f88" />

#### **Chart 1: Average Delay Time by Bus Company **

* **Finding:** **Selby Transportation** and **Little Linda Bus Co.** recorded the highest average delays, exceeding **75-85 minutes**.

#### **Chart 2: Average Delay Time by Borough**

* **Finding:** The **Bronx** and **Nassau County** suffer from the longest delay durations, averaging 35-45 minutes.
* **Recommendation:** Review vendor contracts for Selby and Little Linda; implement penalties for delays exceeding 60 minutes.

---

### 3. Temporal Trends: The "Monday Morning" Effect
I analyzed the frequency of incidents across the school week to identify hidden patterns.
<img width="1189" height="618" alt="image" src="https://github.com/user-attachments/assets/2e077456-7cfe-4231-90af-d8e22fa27625" />


#### **Chart 1: Breakdown Frequency by Weekday**
* **Finding:** Breakdowns are at their highest on Monday (4,146) and decrease every day until Friday.
* **Insight:** This suggests that buses sitting idle over the weekend are prone to failure upon restart.

#### **Chart 2: Running Late Frequency by Weekday**
* **Finding:** A massive spike of **54,667 late incidents** occurs on Mondays. 
* **Recommendation:** Schedule "Pre-Trip Inspections" and fleet maintenance on Sunday evenings to ensure a smooth transition into the Monday work week.

---

## 🛠️ Skills & Tools
* **Data Cleaning:** Standardized inconsistent vendor names and handled null values in delay estimates.
* **Pivot Tables:** Aggregated large-scale datasets to identify trends.
* **Advanced Visualization:** Created 6 targeted Pivot Charts to present complex data to non-technical stakeholders.


