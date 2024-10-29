Here’s an updated README file with your sample dashboard image added:

---

# HR Attendance Analysis Dashboard

### Dashboard Link: [Access the Dashboard](https://app.powerbi.com/groups/me/reports/384d017e-e935-44dc-9e7d-1626c1a36de1/ReportSection)

## Project Overview

The HR Attendance Analysis Dashboard provides insights into employee attendance patterns, focusing on weekly presence, sick leave, and work-from-home (WFH) data. By analyzing these attendance metrics over a three-month period, the dashboard supports the HR department in monitoring attendance, identifying patterns, and making informed decisions to improve employee well-being and productivity.

### Key Insights Provided

- **Weekly Attendance Percentage**: View employees' weekly attendance rates, indicating engagement and consistency.
- **Sick Leave (SL) Percentage**: Track the frequency of sick leave taken by each employee.
- **Work from Home (WFH) Percentage**: Monitor the percentage of time employees work remotely.
- **Individual Employee Analysis**: Tables and matrix views enable drilling down into each employee’s attendance details by week and by day.
- **Monthly Trends**: The bar chart filter allows for the selection and comparison of attendance trends across months.

---

## Sample Dashboard Image

Here is a sample image of the HR Attendance Analysis Dashboard:

!(https://github.com/Sakibyash/HR-Analysis/issues/1#issue-2620638222)

---

## Data Preparation

The following steps were taken to preprocess and structure the data for effective analysis:

1. **Unpivoting Columns**  
   Transformed the dataset by unpivoting specific columns to create a structured format, allowing detailed analysis of various attendance categories (e.g., Present, Sick Leave (SL), and Work from Home (WFH)) across weekly and monthly timeframes.

2. **New Columns Added**  
   - **Month**: Created a month column to categorize and group data for monthly trend analysis.
   - **SL Count**: Added a column to count the number of Sick Leave days per employee.
   - **WFH Count**: Added a column to count the number of Working from Home days.
   - **Week**: Added a week column to enable weekly segmentation of attendance data.

3. **Defined Measures**  
   - **SL Count**: Counts the total Sick Leave days for each employee.
   - **WFH Count**: Counts the total Working from Home days for each employee.
   - **Present %**: Calculates attendance as a percentage of total working days.
   - **WFH %**: Calculates the percentage of WFH days relative to total working days.
   - **SL %**: Calculates the percentage of Sick Leave days relative to total working days.

---

## Report Elements and Visualizations

1. **Weekly Attendance Overview**  
   - A table displays weekly attendance percentages for each employee, giving HR visibility into consistent attendance, irregularities, or patterns requiring attention.

2. **Monthly Filter Bar**  
   - A bar chart provides month-based filtering to view attendance metrics across different months, enabling easy month-over-month comparisons.

3. **Individual Employee Analysis**  
   - An individual table breaks down attendance data by employee, showing each employee’s percentages for Present, Sick Leave, and Work from Home.
   - A matrix view shows detailed attendance data by date, offering a daily look at employee attendance records.

---

## Insights

The dashboard provides key insights to help the HR department make data-driven decisions:

- **Attendance Consistency**: Weekly attendance rates help assess which employees maintain consistent presence.
- **Remote Work Patterns**: WFH percentage trends reveal which employees frequently work remotely, useful for monitoring flexible work policies.
- **Health and Well-being**: By tracking Sick Leave percentages, HR can identify employees with potential health issues requiring follow-up or support.
- **Monthly Trends**: Monthly comparison offers insight into seasonal or periodic attendance fluctuations, supporting strategic workforce planning.

---

## Data Source

- **File Type**: CSV
- **Data Range**: Last 3 months
- **Metrics Included**: Weekly Attendance, Sick Leave, Work from Home

---

## Steps Followed in Power BI

1. **Data Import**  
   Loaded the dataset into Power BI Desktop and checked for quality and completeness using Power Query Editor.

2. **Data Transformation**  
   Used unpivoting and additional calculated columns for month and weekly segmentation. Created measures to compute attendance percentages.

3. **Visualization**  
   Created various charts and tables, including:
   - Slicer bar chart for month selection
   - Weekly attendance tables for quick access to each employee’s data
   - Detailed individual matrices for daily breakdowns

4. **Dashboard Publishing**  
   Published the final report to Power BI Service for online access and sharing with the HR team.

---

## Conclusion

The HR Attendance Analysis Dashboard is a comprehensive tool for monitoring and analyzing employee attendance patterns, providing actionable insights for HR decision-making. By enabling a closer look at individual attendance and overall trends, this dashboard helps HR in workforce planning, promoting employee well-being, and supporting effective remote work policies.

--- 

This README provides a detailed overview of the project and directs readers to a visual sample of the dashboard. Let me know if you'd like any additional sections!
