# Wolf Co. Manufacturing Downtime Analysis

## Project Objective 
Wolf Cola is a soft drink company that handles all its manufacturing operations in Philadelphia. The company kicked off a productivity improvement project for the bottling production line. 
The task is to analyze the productivity and downtime data and find ways for the operating staff to improve the line's efficiency.

**GOAL : Identify productivity improvement opportunities in the production Line**

KEY QUESTIONS:
- What is the current line efficiency? (total time/ min time)
	- breakdown by operator

- Are any operators underperforming?

- What are the leading factors for downtime?

- Determine downtime by operator and factor: Do any operators struggle with particular types of operator error?

## Data Structure 
The data was collected, cleaned, formatted and transformed using Power Query

Power BI is used for data visualization and dashboard

![ERD](https://github.com/Ben-Joan/Wolf-Co-Manufacturing-Downtime/blob/main/Images/ERD.PNG)


## Insights
From August 29th to September 3rd, Wolf Co. Manufacturing had a total production time of **64hrs 18mins**, with effective production time of **41hrs 10mins** and 
downtime of **23hrs 8mins (1388 mins)**. The production line have a **64% overall line efficiency and 36% downtime rate**. There is a total 0f 38 production batches and **35 batches experienced downtime** at an average of **40 mins per batch**.

![Operators eff](https://github.com/Ben-Joan/Wolf-Co-Manufacturing-Downtime/blob/main/Images/Operator%20eff.PNG)

From the above chart, Charlie is the most efficient worker at 66.8% and lowest downtime at 33.2%. while Mac had the poorest efficiency at 60.9% though still above 50% average.

![Factors](https://github.com/Ben-Joan/Wolf-Co-Manufacturing-Downtime/blob/main/Images/Downtime_factors.PNG)

From pareto analysis of 80/20 principle: Machine adjustment, Machine failure, Inventory shortage, Batch change and Batch coding error contributed to 80% impact on downtime causes. 

![operator_factor](https://github.com/Ben-Joan/Wolf-Co-Manufacturing-Downtime/blob/main/Images/Operators.PNG)
This chart helps show operators performance across the different downtime factors to determine where operators encounter the most challenge.
From the operator performance chart, Charlie and Dennis expereienced the most downtime under machine adjustments and machine failure. Dee's most downtime is on Inventory shortage and Machine adjustment while is also in Inventory Shortage and Batch Change. This also shows that for the top factor of Machine adjustment, 3 out of 4 operators has difficulty with this. 


![product_factor](https://github.com/Ben-Joan/Wolf-Co-Manufacturing-Downtime/blob/main/Images/Products.PNG)
C0-600, CO-2L and RB-600 product line combined encountered 74% out of the 23hrs of downtime experienced acros the 64hrs production time. CO-600 major downtime factors Inventory Shortage and Machine Failure, while CO-2L and RB-600 major problem was from machine adjustment.


[DASHBOARD](https://app.powerbi.com/view?r=eyJrIjoiOTBlNTc5NjMtNmU2ZS00MmY2LTg2ZjQtN2IwN2RkMjk1MzE3IiwidCI6IjczMDc4ZWNkLWYzM2UtNDQxYy05ODYyLWVhZDdjNjFhNGU4MiJ9)

## Recommendations
- With a Line efficiency of 64% which is above average, Wolf Co. production line so far has a good productivity rate but there is room for improvemen. Therefore, operations should be improved to meet at least 75% effieciency which is a more excellent rate. Overall, no operator is performing so poorly since efficiency is all above 50% average, but there is need for every operator to improve especially Mac who had the highest downtime rate at 39%.
- Looking at the top causes of downtime and operators performance, there is need for revaluation and reassignment of tasks to the operators according to their areas of lesser downtime and higher efficiency in order to minimize downtime. Charlie, Dennis and Dee had high downtime in machine adjustment compared to Mac, signifying high weakness or poor knowledge on this area, therefore this task can be reassigned primarily to Mac to manage. Mac also experienced high downtime with Batch Change and Inventory mangement compared to other operators, making it also area with limited skillset and therefore should be reassigned to operators with stronger efficiency.
- Product performance also shows that CO-600 is always short on inventory and expriences lots of machine failure during production. While CO-2L and RB-600 production lines always requires adjustment. Therefore, proper inventory management, preventive and predictive maintainance should be parcticed and  faster operator for machine adjustment to prevent this errorrs.




