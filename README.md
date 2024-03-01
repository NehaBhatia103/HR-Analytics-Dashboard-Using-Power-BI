HR Employee Attandance-Dashboard using Power BI and Power Query:
This project showcases the use of Power Query and DAX Query to analyze employee attendance data, add new measures and columns, and create a dashboard using Power BI. The goal is to provide insights into attendance patterns and identify areas for improvement for HR.

About Data Set:
The data we have is the attandance record of a company for the months of April ,May and June.

Tools Used:
Power BI
Power Query
DAX Query
Visualization

Cleaning and Analyzing Using Power Query
Imported the data 
Used Power Query to clean and transform the data
Crated a template for one sheet in Power Query transformations and apply the same transformations to all as we only has data for three months.We made provision for future data for the coming months.
Applied all necessary cleaning steps, such as removing duplicates, renaming columns, and changing data types
Created the parameters to select the desired data based on a specific condition
Loaded and Applied the cleaned data into Power BI

Exploring and manipulating data sing DAX Query
With DAX Query, we manipulated and analyzed the data to provide insights for visualization and identify areas for improvement for HR.
Created Measures and columns Using DAX functions such as Month,Sick Leave Count, Work from home count,Percentage of presence ,Sick Leave and Work From home.

Power BI Dashboard Visualization
Designed the dashboard layout
Created a measure table to aggregate and display the data using Dax functions
Used Visulizations for charts and filters for filter dashboard
Added Title  Employee Attaendance Record
Added  Month column as Slicer


Insights from the report:
Attendance pattern: from the attendance patter we could understand the pesence percentage is hightest on Tuesday and lowest on Friday.
2.Empoyees prefer to work from home on Fridays.

Conclusion:
Since most of the employees are present on Tuesday we can have Project Team meetings, Team Building activities,Team lunches on Tuesday.
Since the least no of employees attend office on Friday ,we can opt that day for maintances and deep cleaning of the office space by declaring friday as Work From Home for all the employees .
By analysing the trend we can call half of the staff on some pre decided days  and can give up the extra space to reduce cost of operation.

Future Prospects:
1. Sending Alerts
After publishing the report to cloud we can send an alert to the employee if his attendance is less by pinning the Percentage card to the dashboard.

2. Automate Data Gathering
We can connect the sheet to Google sheets or sharepoint to automate the data gathering.

3. Setting security level for data.
We can implement either row level
