# CalendarConnector
Copy the .mez file to the [Documents]\Power BI Desktop\Custom Connectors directory.

Open Power BI Desktop.

Go to File > Options and settings > Options.

Under Security, enable Data Extensions to allow custom connectors.

Restart Power BI Desktop.

In Power BI Desktop, go to Get Data. You should see your custom connector listed.

Select the connector, enter the required parameters, and load the data.

This connector has 5 parameters, they are in this order:
1. startDate - the very first date in the calendar, defaults to 1/1 of current year
2. endDate - the very last date in the calendar, defults to 12/31 of current year
3. lastSaleDate - most recent date in sales table where a sale was made, defaults to current day
4. fiscalYearEndMonth - last month of fiscal year, defaults to June
5. firstDayOfWeek - first day of the week, defaults to Sunday
