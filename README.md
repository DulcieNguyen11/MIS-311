I will use Excel to analysis the data set 2 ( Employee Performance)

**1. Data overview**
---
This dataset can be collected from a company’s Human Resource Management System (HRMS), which stores employee information for performance and workforce analysis.It contains 204 rows and 12 columns. Each row represents a record. Each column represents a variable, including ID, Name, Age, Gender, Department, Salary, Joining date, Performance Score, Experience, Status, Location, Session. It includes data from 203 employees and recorded from 19/12/2014 to 7/12/2024.

The dataset provides insights into employee characteristics and their job performance across different departments. The goal is to identify patterns and relationships between variables such as department, salary, and location. This helps HR managers understand workforce productivity, make fair evaluation decisions, and improve organizational performance strategies.

<img width="578" height="315" alt="Ảnh chụp màn hình 2025-11-05 175813" src="https://github.com/user-attachments/assets/9ac4fe49-cb57-4456-b977-6ea191baa591" />

   Table 1: Data description

**2. Data cleaning**
   ---
**a. Missing value**

I used Countblank() function to count how many missing value
   
   Performance Score: 105 missing values
   
Do not fill the missing values in the Performance Score column because these scores are based on human evaluation, not measurable data. Imputing or estimating them would create artificial results and reduce the accuracy of the analysis. Moreover, since 105 out of 199 values (over 50%) are missing, any imputation would heavily distort the dataset and lead to unreliable conclusions. 

Therefore, they were left blank to preserve the integrity and authenticity of the dataset, ensuring that all performance-related insights are based only on real observed evaluations.

**b. Duplicate rows**

   There are 4 duplicate values found and removed. 199 unique values remain

<img width="694" height="113" alt="Ảnh chụp màn hình 2025-11-04 232418" src="https://github.com/user-attachments/assets/83c41406-5771-497b-a934-64491d154dd3" />


**3.Descriptive Statistics**
---
<img width="566" height="289" alt="Ảnh chụp màn hình 2025-11-01 140459" src="https://github.com/user-attachments/assets/b01dd6bf-e6b9-4eed-9601-c9e3dbe73836" />

Figure 1: The bar chart of number of employees by location

The bar chart shows the distribution of employees across three locations: Chicago, Los Angeles, and New York. Los Angeles has the highest number of employees, followed by Chicago, while New York has the least.

👉 **Insight:** 

**Why do we need this insight?**

Knowing how employees are distributed by location helps the company understand workforce concentration and operational scale in each area.

**Who needs this insight?**

This information is useful for HR managers, regional directors, and operations planners who manage staffing levels and regional resources.

**What decision does this insight support?**

It supports decisions on workforce planning, hiring priorities, and training or relocation strategies to balance staffing across offices.

**What it means to the company?**

The result shows that Los Angeles has the highest number of employees, suggesting it is the company’s main business hub. This helps management allocate budgets, office facilities, and HR resources more efficiently in high-demand regions.

<img width="625" height="319" alt="Ảnh chụp màn hình 2025-11-01 133456" src="https://github.com/user-attachments/assets/f0282ea8-11b6-4055-b117-611b0c6d30ad" />

  Figure 2: The bar chart of average salary by employee

  The second bar chart illustrates the average salary across three departments: HR, IT, and Sales. Among them, the IT department has the highest average salary, followed by HR, while Sales has the lowest.

  👉 **Insight:** 

**Why do we need this insight?**

  Understanding salary differences between departments helps HR managers ensure fairness and consistency in compensation policies.

**Who needs this insight?**

This insight is valuable for the Human Resources department and top management, who are responsible for pay structure and budget allocation.

**What decision does this insight support?**

It supports decisions related to salary adjustments, compensation benchmarking, and reward strategy for different roles.

**What it means to the company?**

The finding shows that the IT department has higher average salaries, reflecting its technical value and skill demands. It helps the company maintain competitive pay for critical positions while identifying departments that may require salary reviews to improve employee satisfaction and retention.
