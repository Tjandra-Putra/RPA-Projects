# Excel Data Migration and Entry
Projects are completed and developed using Ui Path Studio

## Objective
```
This workflow merges two excel files (.xlsl) and filter data based on specified constraints,
create and save into a new specified folder.

For this example, two excel files "Employee Details.xlsx" and "Employee Performance Review.xlsx"
are merged together. The data in the merged file is then filtered based on:

1) Attendance Rate = 100%
2) Social Rating = A
3) Productivity = Excellent

The filtered data is stored into a new excel spread sheet.


```

## Usage
```
1) Specify the files to be merged (.xlsl)
2) Specify foreign key (common column name(s))
3) Specify duplicating column names to be removed (if any)
4) Impose constraints (conditions "if")
5) Specify name of newly created file name
6) Specify the directory path of the newly created file to be saved in
```

## Logic & Process Flow
```
1) Reads excel file
2) Store excel data into data table
3) Merge data tables
4) Remove duplicated columns
5) Filter data table
6) Convert data table into string (output data table)
7) Prompt user for file name
8) Convert file name into .xlsl format using string concatenation : prompt_name + ".xlsl"
9) Save as .xlsl file format
10) Prompt user for directory path
11) Move file from current directory to specified user directory path

```
