# Case study:
  HR analytics in Power BI for Atlas Labs company
## Case study goals:
primary goal: Monitor key HR metrics on employees

Secondary goal: understand what factor impact attrition

---

 __NOTE__ : This case study will imploy the snowflak schema which the  fact table is the central of the schema and the other dimension tables will connected to the central

---

## The steps that are done in this case study:
### 1. Data Modeling and EDA:
- Load CSVs 
- Create Date dimension and relating tables so that to model data as snowflack schema 
- Exploring the data to understand the attrition at the company
- Hiring trends over time to see where they see the biggest growth in new employees and this done by activate the relationship between DimDate and Fact table by USERELATIONSHIP() DAX function.
- Analyzing departments and job roles so that the HR team that work with departments to understand what type of typical roles  that they are hiring into the organization for future hiring plan.
### 2. Analyzing Demographics and Performance using DAX:
* The results of this steps:
  - Majority of employees are between 20-29 years old.
  - Currently, Atlas Labs employ 2.7% more women than men.
* Employees who identify as
  - White have the highest average salary
  - 'Mixed or multiple ethnic groups' have one of the lowest average salaries.
### 3. Attrition factors:
  After analysis it find out that the employees that have been considered frequent travels have the highest attrition rate despite only making up 19% of the total hires and we can suggest to HR to review travel requirements policy and survey employees on feelings around travel frequency .
### 4. Theme formatting and page navigation
