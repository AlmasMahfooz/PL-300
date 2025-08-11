# PL-300

Visuals
-------
To create a Power BI visual that displays trending data over months, you can use a ribbon chart or an area chart.

Ribbon Chart
Select Ribbon chart from the Visualizations pane.
For the X-axis, select the Month and Day fields under the OpenDate data hierarchy.
For the Y-axis, select the Value from This Year Sales.
For the Legend, select the Category from Item.
The ribbon chart will illustrate the rank for categories over the months.

Area Chart
In the Data pane, select Last Year Sales and This Year Sales.
Convert the chart to an area chart by selecting the Area chart icon from the Visualizations pane.
Add FiscalMonth to the Axis well.
Sort the visualization by selecting More options (...) and choosing Sort by > FiscalMonth.
Both visualizations will effectively show the trends in your data over the months.

![Uploading image.png…](https://github.com/AlmasMahfooz/PL-300/blob/main/Images/trending%20over%20month.png)


































https://electroiq.com/stats/power-bi-statistics/
https://learn.microsoft.com/en-us/power-bi/create-reports/desktop-excel-stunning-report
https://www.youtube.com/@droovetech
https://www.youtube.com/@globaltechlearn
https://www.youtube.com/watch?v=HlnpGY9sYH8&list=PLHhRh409SyR7UBoV8n2t_Nu1aSO4nJyQI&index=5
https://www.passnexam.com/microsoft/pl-300/2
https://www.youtube.com/watch?v=fkEIX_fR9sI&t=545s


working on these test paper
https://www.passnexam.com/microsoft/pl-300/5


Pragmatic videos
https://www.youtube.com/watch?v=H2HPicNvz8s&list=PLcwrIWK7WBcSCcdFkFBftOjqli_yi9Zti&index=2
https://www.youtube.com/watch?v=Dk25lwdTKow

CASE STUDY
https://www.youtube.com/watch?v=fNuhHByJbS4&list=PLbWtUDmDbHRAAYc1FDinFWk-PFZ77sde2
(https://www.youtube.com/watch?v=SU3f8UK6XEU&t=107s)




https://github.com/microsoft/powerbi-desktop-samples

https://learn.microsoft.com/en-us/power-bi/create-reports/insights

https://radacad.com/enhance-the-card-visual-in-power-bi-with-conditional-formatting/


StartDate = 
var __Weeknum = Weekly_Returns[week_id]
return
CALCULATE(FORMAT(MIN('Date'[date]),"yyyymmdd" ),  'Date'[week] = __Weeknum)
