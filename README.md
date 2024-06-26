# Bank-Customer-Churn-Dashboard

### Dashboard Link : https://app.powerbi.com/groups/me/reports/40f36c32-38fd-442d-9f21-19ad9358dfcb/80bdbf666f3179f2da28?experience=power-bi
Note: For this dashboard specification, it was crucial to represent exited customers as 1 and non-exited customers as 0.

## Problem Statement

This dashboard is designed to help the Bank better understand their customers and assess their satisfaction with the bank's services. By analysing various ratings, the Bank can identify areas needing improvement. Additionally, the dashboard provides insights into the causes of customer churn, allowing the Bank to implement strategies to retain existing customers and prevent further churn. With 20% of customers exiting the bank, it is crucial to predict and prevent churn to enhance the overall performance of the Bank.
Note: For this dashboard specification, it is crucial to represent exited customers as 1 and non-exited customers as 0.
 




### Steps followed 

Developing this dashboard using Power BI involved several steps, from connecting to data sources to creating visualizations and publishing the dashboard. Below is a step-by-step guide:
1.	Open Power BI Desktop: Launch the Power BI Desktop application.
2.	Get Data:
Click on the Home tab and select "Get Data".
Choose the data source type, in this case, Excel. Other options include SQL Server, Web, etc.
If using SQL Server, provide the necessary credentials and connection information to access your data.
Select the data and click "Load".
3.	Data Cleaning and Transformation:
Use the Power Query Editor to clean and transform data.
Remove the irrelevant columns RowNumber, CustomerId and Surname.
4.	Data Modeling:
If you have multiple datasets, define the relationships between different tables in the Model view, but this is not applicable in this case as a single dataset was used.
5.	Create Visualizations:
In the Report view, select a visualization type from the Visualizations pane (e.g., bar chart, line chart, pie chart).
Drag and drop fields from the Fields pane (e.g., Age, Exited, Geography, CreditScore, HasCrCard, IsActiveMember, EstimatedSalary) to the visualization.
Add measures to the Values field and categories to the Axis field.
6.	Customize Visuals:
Use the formatting options available in the Visualizations pane to customize your visuals.
Add multiple visuals to the canvas by repeating the steps above.
Resize and arrange the visuals on the canvas to create a coherent layout.
7.	Add Interactivity:
Use slicers to allow users to filter data on the dashboard.
Use text boxes to add the dashboard title.
8.	Save and Publish:
Save the Power BI report file (.pbix).
Publish the report to Power BI Service.
9.	Share the Dashboard:
Open the Power BI Service in a web browser.
Navigate to the workspace where you published the report.
Share the dashboard with colleagues by clicking the Share button in the Power BI Service.
10.	Scheduled Refresh:
If the data source is dynamic, set up a scheduled refresh in the Power BI Service.
Go to Datasets, select your dataset, and configure the refresh settings to update the data periodically.

This interactive dashboard in PowerBI was created following these steps, it provides valuable insights into customer satisfaction and churn, enabling the Bank to take proactive measures to improve customer retention and overall performance.
