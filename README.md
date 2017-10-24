# Custom-Visuals---Microsoft-Power-BI
Data visualization is important for making informed business decisions, which are taken up by the business analyst. But sometimes the way BA want to visualize stuff my not always be provided by the BI tools.
In comes custom visuals there, we have Bar charts, Scatter plots ...etc which are standard charts available, not always each and every information can be best visualized using the standard visuals and hence is the need for custom visuals.
Custom visuals help you visualize the data way you want it to understand and make informed decisions.

# Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
```
Microsoft Power BI Desktop
npm 
```
## Installing
For Power BI follow up Power BI website for downloads.
```
#to update to the latest api
npm install -g powerbi-visuals-tools
```

## Running the tests
Open the `src\visual.ts` file and head towards terminal and enter:
```
pbiviz start
```
A new browser window with localhost server up will be displaying your visual.

To save as Power BI package :
```
pbiviz package
```

## Built With
 - Microsoft Power BI
 - Data Driven Documents(D3)
 - TypeScript
 
## Authors
- Mohammed Khursheed Ali Khan
- Utsav Dave

## Acknowledgement
- MAQ Software Customer Analytics Team
