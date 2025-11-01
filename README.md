1. Data overview

This dataset can be collected from a company’s Human Resource Management System (HRMS), which stores employee information for performance and workforce analysis.It contains 200 rows and 12 columns. Each row represents a record. Each column represents a variable, including ID, Name, Age, Gender, Department, Salary, Joining date, Performance Score, Experience, Status, Location, Session. It includes data from 199 employees.

The dataset provides insights into employee characteristics and their job performance across different departments. The goal is to identify patterns and relationships between variables such as department, salary, and location. This helps HR managers understand workforce productivity, make fair evaluation decisions, and improve organizational performance strategies.

<img width="530" height="289" alt="Ảnh chụp màn hình 2025-11-01 125554" src="https://github.com/user-attachments/assets/0dfd1ee4-bb10-4416-997f-f2c5c9a117c4" />

   Table 1: Data description

2. Data cleaning
   
   a. Missing value
   
   Performance Score: 105 missing values
   
Do not fill the missing values in the Performance Score column because these scores are based on human evaluation, not measurable data. Imputing or estimating them would create artificial results and reduce the accuracy of the analysis.Therefore, they were left blank to preserve the integrity and authenticity of the dataset. This ensures that all performance-related insights are based only on real observed evaluations.

   b. Duplicate rows

   There are 4 duplicate values found and removed. 199 unique values remain

3.Descriptive Statistics

<img width="556" height="284" alt="Ảnh chụp màn hình 2025-11-01 134733" src="https://github.com/user-attachments/assets/7544cc6a-4ecd-437f-b933-7303629697af" />


Figure 1: The bar chart of number of employees by location

The bar chart shows the distribution of employees across three locations: Chicago, Los Angeles, and New York. Los Angeles has the highest number of employees, followed by Chicago, while New York has the least.

👉 Insight: This suggests that Los Angeles is the company’s main operational hub, possibly hosting larger teams or key business functions. Understanding this distribution helps HR managers plan recruitment, training, and resource allocation more effectively across regions.

<img width="625" height="319" alt="Ảnh chụp màn hình 2025-11-01 133456" src="https://github.com/user-attachments/assets/f0282ea8-11b6-4055-b117-611b0c6d30ad" />

  Figure 2: The bar chart of average salary by employee

  The second bar chart illustrates the average salary across three departments: HR, IT, and Sales. Among them, the IT department has the highest average salary, followed by HR, while Sales has the lowest.

  👉 Insight: This indicates that employees in technical departments like IT are generally better compensated, likely due to higher skill requirements and greater contributions. The variation in salary across departments highlights the organization’s effort to align compensation with job complexity and expertise level.
