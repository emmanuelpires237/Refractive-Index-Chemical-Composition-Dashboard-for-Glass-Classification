# Refractive Index Chemical Composition Dashboard for Glass Classification
**1. Project Overview**

This project focuses on developing an interactive analytical dashboard to explore the relationship between glass type, refractive index, and chemical composition. The dashboard enables users to:
* monitor glass properties,
* understand compositional variations,
* identify high-risk/rare compositions,
* support forensic or manufacturing classification tasks.
The central goal was to provide data-driven insight into how chemical composition influences physical properties, particularly Refractive Index (RI) across different glass types.

**2. Project Scope**

**The project covers:**
* ✔ Data cleaning and preparation
* ✔ Exploratory data analysis (EDA)
* ✔ KPI development and metric definition
* ✔ Visualization and dashboard development
* ✔ Pattern identification and interpretation
* ✔ Insight generation for decision-making
  
The dashboard specifically analyses:
* Refractive Index by glass type
* Presence and levels of major oxides
* Trends in silica and barium content
* Chemical consistency across glass classes
* Sample distribution by glass type

**3. Methodology**

A structured analytical approach was used:

**➤ Step 1: Data Understanding**
* Reviewed schema and variable descriptions
* Identified target features and contaminants

**➤ Step 2: Data Cleaning**
* Removed missing / duplicate records
* Validated chemical percentage totals
* Normalized type labels
  
**➤ Step 3: Exploratory Data Analysis**
* Univariate distribution of oxides
* Chemical clustering by type
* Outlier detection
  
**➤ Step 4: KPI Development**
Metrics aligned to analytical goals:
* Total Samples
* Average Refractive Index
* Average Silica (Si) Content
* % High Barium Samples
* Number of Distinct Glass Types
  
**➤ Step 5: Dashboard Design**
* Created interactive slicers
* Drill-through capabilities
* Multi-chart comparative view
  
**➤ Step 6: Result Interpretation**
* Derived business and scientific insights
* Prepared recommendations

**4.Data Source**

* UCI Machine Learning Repository Glass Identification Dataset
* Contains:
  
- Refractive index values
- Oxide chemical composition (% weight)
- Categorical glass type labels

**5. Tools Used**

* Power BI — dashboard & data modeling
* Microsoft Excel — initial analysis and preprocessing
* DAX — KPI and measure creation
* Statistics & EDA techniques — interpretation
* Data visualization best practices

**6. Results & Key Findings**

**📌 Key Performance Indicators (KPIs)**

| **KPI	     |                                         |   Value** |

Total Samples               	214
Average Refractive Index    	1.52
Number of Distinct Glass Types	6
Average Silica Content	      72.65%
High-Barium Sample Percentage	  0.18%

