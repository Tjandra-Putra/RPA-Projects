# Google Form Automation
Projects are completed and developed using Ui Path Studio

## Objective
```
This workflow auto fills google form base on excel input. This helps to save time and 
elimate human error possibility.
```

## Usage
```
1) Ensure there are data in the excel file.
2) Make sure the excel file is closed before running the workflow.
```

## Logic & Process Flow
```
1) Reads excel file
2) Stores excel data into data table
3) Web recording function
4) Replace "type over" field with read row from excel
5) Add a delay to ensure that the page is fully loaded before proceeding.
6) Add a go back function to redirect to previous page.
7) Process repeats until all rows have been read.

```
