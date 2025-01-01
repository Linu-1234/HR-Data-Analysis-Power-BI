# HR-Data-Analysis-Power-BI

## Project Objective
To analyze and visualize employee presence data to determine working preferences (Work from Home vs. Work from Office) and Sick Leave percentages, providing actionable insights for HR decision-making.

## Project Description
- The HR Data Analysis project leverages Power BI to analyze three months (April, May, and June) of employee presence data for a company.
- The dataset contains employee IDs and names in rows, with columns representing dates.
- The goal is to provide HR insights into working preferences and sick leave patterns through interactive dashboards.

## Tools Used
1. Power BI: For data transformation, DAX measures, and visualization.
2. Excel: To store raw data.
3. DAX (Data Analysis Expressions): For creating calculated measures and metrics.
4. External Resources: Referenced a blog post for combining data from multiple Excel worksheets in Power BI.

## Processes Involved
1. Data Gathering and Transformation:
- Combined data from multiple Excel sheets using Power BI.
- Addressed data integration issues using external references (<a href="https://blog.crossjoin.co.uk/2018/07/09/power-bi-combine-multiple-excel-worksheets/"></a>).
2. Creating Measures Using DAX:
- Calculated Present %, Total Working Days, Work from Home %, Sick Leave %, and counts for each metric.
- Built metrics for individual employees and overall trends.
3. Dashboarding:
- Designed interactive visualizations for key metrics.
- Made insights easy to interpret for HR and management.

## Dashboard Interaction
![HR Analytics Dashboard](https://github.com/user-attachments/assets/ddc94c02-9eb4-4524-8ced-f10f55d08449)


## Insights
1. Present %:
- Overall presence rate: 91.83%.
- Highest presence rate: 97.44%.
- Variations in presence rate across days of the week, with Monday showing the highest presence (93.21%).
2. Work From Home (WFH) %:
- WFH rate: 10.00%.
- Peaks in WFH observed in May (23.44%).
- Fridays showed the highest WFH percentage (13.01%).
3. Sick Leave (SL) %:
- Sick Leave rate: 1.10%.
- SL% peaked on specific dates in May and June, reaching up to 5.42%.
- Mondays recorded the highest Sick Leave percentage (1.62%).
4. Individual Employee Insights:
- 22 Employees have 100% present rate among whom 5 Employees have 100% WFH rate.
- Employee with the highest Sick Leave: Ayanna Atkins (10.71%).
5. Daily and Weekly Trends:
- Consistent patterns in presence and WFH rates across weekdays.
- Seasonal trends indicating higher absence during mid-May.

## Scoping for Future Requirements
1. Sending Alerts:
- Publish the dashboard to the cloud.
- Pin critical visualizations and set alerts for specific conditions.
- Notifications can be sent via email when predefined thresholds are met.
2. Automatic Data Refresh:
- Link the dashboard to a Google Sheet for dynamic updates.
- Alternatively, connect the dashboard to a shared SharePoint folder for real-time data synchronization.
3. Setting Security Levels:
- Implement role-based access control.
- Publish separate dashboards for management and employees.
- Restrict employee-level dashboards to trend insights while keeping detailed data confidential.

## Conclusion
- The HR Data Analysis project provides HR professionals with a powerful and intuitive tool to track employee attendance, analyze working preferences, and monitor sick leave patterns.
- By leveraging interactive visualizations, it simplifies complex data into actionable insights, enabling HR to make data-driven decisions efficiently.
- With future enhancements like dynamic data updates, automated notifications, and role-based security, this dashboard has the potential to become an indispensable asset for HR management, ensuring operational excellence and informed workforce strategies.
