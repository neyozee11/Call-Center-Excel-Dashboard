# October 2021 Call Center Dashboard Report

### Project Overview

This project involves the analysis and creation of a dashboard report showcasing the activities within a Call Center for the month of October 2020. The objective is to provide a graphical representation,offering meaningful insights into the trends and patterns of incoming calls to the Call Center.

### Data Source

The primary data source for this project is the "Call Center.csv" containing detailed information about the incoming calls to the Call Center.

### Tools

- Microsoft Excel [Download here](https://www.microsoft.com/en-gb/microsoft-365/excel)

### Steps

1. Created a new worksheet and renamed it 'Cleaned Sheet' so as to clean the data while also keeping the original data
2. Changed the cell colour of the top row and bold it to distinguish it form the other rows as the header row
3. Froze the header row to keep it visible when scrolling down the file
4. Made sure there are no empty rows in the data
5. Changed the data type of the columns as appropriate
6. Created a new column and extracted the 'day' from the dates in the 'call_timestamp' column because the data is only for October 2020
7. Opened a new worksheet, renamed it 'Pivot Tables' and created pivot tables for different categories
8. Created another worksheet, renamed it 'Dashboard' and created a dashboard report consisting of barcharts, column charts, doughnut charts, map chart and slicers
9. Established connectivity between slicers and the other graphs and charts to facilitate seamless communication and coordination among them
10. Saved the document as an Excel file (.xlsx)

### Important Information from Dashboard

1. The Los Angeles/CA branch has the highest number of calls, followed by Baltimore/MD which received more than twice the number of calls received in the Chicago/IL branch sitting in third while Denver/CO received the least number of calls.
2. The majority of the calls primarily concern billing questions, while the volume of calls related to payment and service outages is roughly equal. This pattern is consistent across individual branches as well.
3. Almost a quarter of the total number of calls are below SLA.

### Recommendation

1. At any point in time, the number of staff in the Los Angeles/CA and Baltimore/MD branch should be at least twice the number of staff at the other branches.
2. Trainers should focus more on billing inquiries when training customer service agents.
3. More customer service agents should be employed in the call center branches so as to further improve the number of calls within and above SLA.

### Limitation

Considering the dataset, I had to assume that calls came through Chatbot, Email as well as Web so as to keep the focus on calls.


