# How to use OpenSourceNepal (OSN) API?

There're several ways OSN API can be used. We have suggested the most common ways to use OSN API below.

## Accessing via OSN UI
- Step 1: Visit [www.opensourcenepal.com](www.opensourcenepal.com)

![image](https://user-images.githubusercontent.com/43303294/224905301-8bfbf985-6252-4910-aedf-a3d159f73d6a.png)

- Step 2: Pick an API service. For this example, we are choosing `/imports` endpoint. Hit `Try it Out`.

![image](https://user-images.githubusercontent.com/43303294/224906338-bdf2c1d2-ef1f-4831-8137-17dc8b931625.png)

- Step 3: Know the details about the `request` and `response` data (metadata).

![image](https://user-images.githubusercontent.com/43303294/224906698-6847ade9-dd26-43e9-b2f4-91fc8a4f07b7.png)

- Step 4: Enter `limit` and `offset` values depending upon the range of data you'd like to get, and Hit `Execute`

![image](https://user-images.githubusercontent.com/43303294/224906934-ec0be550-b521-44b1-a137-c7afdf1721f2.png)

- Step 5: You should see the following if everything went well. The `Request URL` is where this API is available. You can use this `endpoint` to your target application.

![image](https://user-images.githubusercontent.com/43303294/224907185-e9b6ba55-7b2f-4867-ac15-9897494b3c44.png)


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
