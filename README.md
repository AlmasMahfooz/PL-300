# PL-300

Visuals
-------
To create a Power BI visual that displays trending data over months, you can use a ribbon chart or an area chart.

Ribbon Chart
------------
Select Ribbon chart from the Visualizations pane.
For the X-axis, select the Month and Day fields under the OpenDate data hierarchy.
For the Y-axis, select the Value from This Year Sales.
For the Legend, select the Category from Item.
The ribbon chart will illustrate the rank for categories over the months.

Area Chart
----------
In the Data pane, select Last Year Sales and This Year Sales.
Convert the chart to an area chart by selecting the Area chart icon from the Visualizations pane.
Add FiscalMonth to the Axis well.
Sort the visualization by selecting More options (...) and choosing Sort by > FiscalMonth.
Both visualizations will effectively show the trends in your data over the months.

![Uploading image.png…](https://github.com/AlmasMahfooz/PL-300/blob/main/Images/trending%20over%20month.png)


scatterplot/Scatter Chart/Scatter Plot
--------------------------------------
A scatterplot is typically used to compare a relationship between two (or more) calculations and their categorical distribution between each other.
Creating a scatter visual is the first step of applying the clustering technique that groups data into clusters.It is particularly suitable for identifying outliers
because it displays them away from the bulk of data.

![Uploading image.png…](https://github.com/AlmasMahfooz/PL-300/blob/main/Images/3-scatter-chart-outlier-ss.png)


Funnel Visualization
--------------------
A funnel visualization is a chart that that has sequential connected stages, where items flow sequentially from one stage to the next.



Python visual 
-------------
To create a Python visual by using Power BI Desktop, 
first need to install Python on computer.
Second need to configure the global Python scripting options in Power BI Desktop.
Enabling the script visuals option in the Visualization pane of Power BI Desktop is done once Python is installed. Creating a custom Python visual by using Power BI Desktop has no dependency on enabling preview features.
---------------------------------------------------------------------------------------------



Q&A feature
-----------
The Q&A feature lets you create a visual by typing in a question about your data. This new visual can then be pinned to the dashboard, without adding it to a report. 

Visualizing trends
------------------
Visualizing trends using a trend line shows overall trends in the data but does not provide insights into the variations in ticket distribution across locations
Common visuals for showing trends are Line,Area, Column and Bar Charts.


Histogram.
----------
A histogram chart is a Power BI visualization that displays the frequency distribution of data. It is a bar chart that groups data points into ranges or bins and then displays the number of data points in each bin. Histograms can be used to identify patterns in data, such as central tendency, outliers, and skewness

Create a Histogram in Power BI to see your product sales distribution.
Exercise:https://www.youtube.com/watch?v=n-_hIc6mj1I
-----------------------------------------------------------------------------------------
https://electroiq.com/stats/power-bi-statistics/

https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-excel-stunning-report

https://www.youtube.com/@droovetech

https://www.youtube.com/@globaltechlearn

https://www.youtube.com/watch?v=HlnpGY9sYH8&list=PLHhRh409SyR7UBoV8n2t_Nu1aSO4nJyQI&index=5

https://www.youtube.com/watch?v=fkEIX_fR9sI&t=545s

-----------------------------------------------------------------------------------------
Passnexam test paper

https://www.passnexam.com/microsoft/pl-300/2

https://www.passnexam.com/microsoft/pl-300/5

-----------------------------------------------------------------------------------------
Pragmatic videos

https://www.youtube.com/watch?v=H2HPicNvz8s&list=PLcwrIWK7WBcSCcdFkFBftOjqli_yi9Zti&index=2

https://www.youtube.com/watch?v=Dk25lwdTKow

--------------------------------------------------------------------------------------------
CASE STUDY

https://www.youtube.com/watch?v=fNuhHByJbS4&list=PLbWtUDmDbHRAAYc1FDinFWk-PFZ77sde2

(https://www.youtube.com/watch?v=SU3f8UK6XEU&t=107s)

--------------------------------------------------------------------------------------------
https://github.com/microsoft/powerbi-desktop-samples

https://learn.microsoft.com/en-us/power-bi/create-reports/insights

https://radacad.com/enhance-the-card-visual-in-power-bi-with-conditional-formatting/


Year     Jan     Feb     Mar

2025      10      20      30

2026      11      12      13     

when we UNPIVOT it  
it will be like below

 
Year      Month      Amount

2025        Jan       10

2025        Feb       20

2025        Mar       30

2026        Jan       11

2026        Feb       12

2026        Mar       13  

and when we PIVOT it it will give the output like the above shown table


