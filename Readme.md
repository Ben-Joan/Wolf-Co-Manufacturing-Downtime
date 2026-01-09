# Wolf Co. Manufacturing Downtime Analysis

## Project Objective 
Wolf Cola is a soft drink company that handles all its manufacturing operations in Philadelphia. The company kicked off a productivity improvement project for the bottling production line focused on understanding production efficiency and downtime. 
The objective of this project is to analyze productivity and downtime data from the production line and identify actionable opportunities for improving operational efficiency.

**GOAL : Identify productivity improvement opportunities in the production Line**

KEY QUESTIONS:
- What is the current line efficiency? (total time/ min time)
	- breakdown by operator

- Are any operators underperforming?

- What are the leading factors for downtime?

- Determine downtime by operator and factor: Do any operators struggle with particular types of operator error?

## Tools & Skills
- Power BI – Data modeling, DAX, interactive dashboards

- Power Query – Data cleaning and transformation

- Operational Analytics – Efficiency analysis, Pareto (80/20) analysis

- Manufacturing KPI Analysis – Downtime, line efficiency, operator performance


## Data Structure 

![ERD](https://github.com/Ben-Joan/Wolf-Co-Manufacturing-Downtime/blob/main/Images/ERD.PNG)


## Insights
From August 29th to September 3rd, Wolf Co. Manufacturing had a total production time of **64hrs 18mins**, with effective production time of **41hrs 10mins** and 
downtime of **23hrs 8mins (1388 mins)**. The production line have a **64% overall line efficiency and 36% downtime rate**. There is a total 0f 38 production batches and **35 batches experienced downtime** at an average of **40 mins per batch**.

![Operators eff](https://github.com/Ben-Joan/Wolf-Co-Manufacturing-Downtime/blob/main/Images/Operator%20eff.PNG)

From the above chart, **Charlie** is the most efficient operator with **66.8% efficiency** and lowest downtime rate **(33.2%)**. While **Mac** recorded the lowest efficiency at **60.9%** though still above 50% average benchmark. Overall, operator efficiency levels are relatively close, indicating no extreme underperformance.


![Factors](https://github.com/Ben-Joan/Wolf-Co-Manufacturing-Downtime/blob/main/Images/Downtime_factors.PNG)

Using Pareto analysis (80/20 principle), the following factors account for approximately 80% of total downtime:

**Machine adjustment (24%), Machine failure (18%), Inventory shortage (16%), Batch change (12%) and Batch coding error (10%).**

These represent the most critical areas requiring operational improvement.


![operator_factor](https://github.com/Ben-Joan/Wolf-Co-Manufacturing-Downtime/blob/main/Images/Operators.PNG)
This chart helps show operators performance across the different downtime factors to determine where operators encounter the most challenge.
From the operator performance chart, **Charlie and Dennis** experienced the highest downtime related to machine adjustment and machine failure. **Dee** recorded most downtime due to inventory shortage and machine adjustment. **Mac** showed higher downtime in inventory shortage and batch change.
**Notably, 3 out of 4 operators struggled with machine adjustment, making it the most widespread operational challenge.**


![product_factor](https://github.com/Ben-Joan/Wolf-Co-Manufacturing-Downtime/blob/main/Images/Products.PNG)
CO-600, CO-2L, and RB-600 accounted for 74% of total downtime across the production period. **CO-600 downtime** was mainly caused by inventory shortages and machine failure while **CO-2L and RB-600 downtime** was primarily driven by machine adjustment issues.

## Dashboard View
![Dashboard](https://github.com/Ben-Joan/Wolf-Co-Manufacturing-Downtime/blob/main/Images/Report.PNG)
[DASHBOARD](https://app.powerbi.com/view?r=eyJrIjoiOTBlNTc5NjMtNmU2ZS00MmY2LTg2ZjQtN2IwN2RkMjk1MzE3IiwidCI6IjczMDc4ZWNkLWYzM2UtNDQxYy05ODYyLWVhZDdjNjFhNGU4MiJ9)

## Recommendations
- Although the production line efficiency of 64% is above average, there is significant room for improvement. A **target efficiency of 75%** is recommended to achieve a more optimal performance level.
- No operator is performing poorly overall, as all efficiency levels exceed 50%. However, focused improvement is needed **particularly for Mac**, who recorded the highest downtime rate (39%).
- **Task reassignment should be considered based on operator strengths:**
	- Machine adjustment tasks should be primarily handled by operators with relatively better performance in this area, as multiple operators struggle with this factor. e.g Mac performed best here, therefore should be assigned this task.
	- Inventory management and batch change tasks should be reassigned away from operators with higher downtime in these categories. e.g Mac has weaker strength here compared to Charlie and Dee with very minimal downtime.
- For product-related downtime:
	- CO-600 requires **improved inventory planning and preventive maintenance** to reduce shortages and failures.
	- CO-2L and RB-600 production lines would benefit from **faster and more standardized** machine adjustment procedures.
- In conclusion: Implementing preventive and predictive maintenance, improved inventory control, and targeted operator training will significantly reduce downtime and improve overall line efficiency.

