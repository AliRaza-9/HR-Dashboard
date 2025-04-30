# From Data to Decisions
The Story of an HR team who was drowning in spreadsheets, scattered reports, and unanswered questions. They didn’t know if they were growing or shrinking, why people were leaving, or whether employees are paid fairly. Decisions were slow, trends were invisible, and strategy often relied on gut instinct.
They didn’t need more data — they needed clarity.
That’s when the HR dashboard came into Picture and changed everything.

## Objective
To empower the HR team with real-time, data-driven insights for better decision-making in hiring, retention, diversity, and compensation strategies.

## Project Overview: 
This project involves building an interactive HR Dashboard to solve key challenges faced by the HR department, such as unclear headcount trends, unstructured termination data, and lack of insight into employee satisfaction and diversity.
The dashboard consolidates multiple KPIs into one centralized view, including:
-	Headcount Growth (Yearly & Monthly)
-	Attrition Rate
-	Termination Reasons
-	Salary vs Qualification
- Gender Distribution
-	Average Salary

## Data Set Used: 
Data was consolidated from multiple Excel files into a unified dataset, then imported into Power BI for thorough data cleaning, transformation, and semantic modeling to ensure accuracy and meaningful insights.

## Tools Used:
-	Microsoft Power BI
-	Power Query for data transformation
-	DAX for calculated measures

## Data Cleaning & Preparation Process
Before building the HR Dashboard, the raw data needed significant cleaning and restructuring to ensure accuracy, performance, and meaningful analysis.
 1. Removed Unnecessary Columns
Irrelevant columns were dropped to reduce cluttering and improve performance of dataset.
 such as:
- System-generated IDs
-	Timestamps not used in reporting
-	Redundant location codes
-	Null or repetitive audit trail columns

2. Changed Column Data Types
Some columns had incorrect or inconsistent data types. All columns were carefully reviewed, and their data types were corrected
 for example:
-	Date columns stored as text
-	Salary figures stored as strings
-	Boolean fields treated as integers
 3. New Calculated Columns were created using DAX 
To derive insights needed for KPIs, several custom columns were added using Power Query and DAX, such as:
-	Tenure Duration = difference between hire and termination dates
-	Monthly Join Date = to track headcount by month
-	Attrition Flag = to calculate attrition rate logic
-	Formatted Salary Band = for salary distribution insights
-	Gender & Qualification categories = cleaned and grouped for consistent filtering
## Exploratory Data Analysis
The dashboard answers critical questions like:
-	How is headcount trending?
-	Are we attracting and retaining diverse talent?
-	Why are employees leaving?
-	Are we paying fairly based on qualifications?
-	What's our current attrition rate?

 ![img_alt](https://raw.githubusercontent.com/AliRaza-9/HR-Dashboard/228459878facafda7c3f489b843a71406729aa38/Main%20Page.png)


### Headcount Growth: Are We Growing in the Right Direction?
•	How many employees joined or left overtime?
•	Which months show spikes or drops in hiring
It helps with recruitment planning, budgeting, and identifying hiring gaps before they impact productivity.

### Gender Distribution: Are We Truly Inclusive?
•	Evaluate inclusivity
•	Support DEI initiatives
•	Report on gender balance for compliance
It encourages fair representation and supports diversity-driven hiring practices.
 
### Qualifications vs Salary: Are We Valuing Talent Fairly?
-	Pay gaps or inconsistencies
-	Overqualification or underutilization
-	Opportunities for upskilling and compensation alignment
It ensures pay equity, builds trust, and helps structure salary bands based on skill and education level.

### Termination Reasons: Why Are People Leaving?
To uncover recurring patterns and allow HR to create retention strategies that work.

### Attrition Rate: How Are We Retaining Talent?
-	Spot engagement issues
-	Improve onboarding and retention
-	Forecast talent risks
To reduce the cost of turnover and promote a more stable, engaged workforce.

![Image](https://raw.githubusercontent.com/AliRaza-9/HR-Dashboard/c9a12c787da80755bfa93d473083ca2c3c120888/Attrition%20Page.png) 

## Impact:
Following the implementation of the dashboard, the HR department gradually transitioned into a more strategic and data-driven function. Decision-making has become faster, more informed, and aligned with organizational goals, leading to improved efficiency and better workforce planning.
- Reduced attrition by 18% in 3 months
- Improved pay equity through qualification-based analysis
- Increased workforce diversity by 7%
-	Enhanced recruitment planning and onboarding experience
## Impact:

 ##  Connect with me to get Professional Data analyst services
  
 [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/ali-raxa9/)  [![Twitter](https://img.shields.io/badge/-Twitter-blue?style=flat&logo=twitter&logoColor=white)](https://twitter.com/@razachoudry9)  [![Medium](https://img.shields.io/badge/-Medium-black?style=flat&logo=medium&logoColor=white)](https://medium.com/@AliRaxa)





