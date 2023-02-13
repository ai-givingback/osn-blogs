# How to use OpenSourceNepal (OSN) API?

There're several ways OSN API can be used. We have suggested the most common ways to use OSN API below.

## With Excel

You can import data from the above API into Microsoft Excel using the "From Web" feature of the Power Query Editor. Here's how:

- Open Microsoft Excel and click on the "Data" tab.
- In the "Get & Transform Data" section, click on "Get Data."
- Select "From Web."
- In the "From Web" dialog box, paste the URL of the API endpoint:
For example: 
```sh
https://www.opensourcenepal.com/administrativeUnits/districts
```
In this example, we're pulling data related to districts of a country (Nepal). 
- To pull information from other endpoint, copy and replace the above URL and repeat the above processes.
- Click on "Load" to load the data into the Power Query Editor.
- In the Power Query Editor, click on the "Load" button to load the data into the editor.
- The data will be displayed in a preview grid. You can transform the data as needed by using the tools in the Power Query Editor.
- When you're finished transforming the data, click on the "Close & Load" button to load the data into Microsoft Excel.

You can then work with the imported data in Excel, just as you would with any other data in Excel. Note that the imported data will be linked to the original data source, so any updates to the API data will be reflected in the Excel spreadsheet.
