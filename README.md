# INTRODUCTION

### DATA CLEANING AND TRANSFORMATION

Data cleaning , also known as data scrubbing or data cleasing is the process of identifying 
and correcting or removing errors, inconsistences and inaccuracies in a dataset.
It involves transforming raw data into a clean and reliable format for analysis. 

#### THINGS TO NOTE IN DATA CLEANING

-  DATA QUALITY ISSUES
  
This can arise due to various factors , including human error, system limitations,
data entry mistake or technical glitches.

- DATA PROFILING
  
It involves examining the structure, content , and quality of the dataset.

It helps identifying patterns, anomalities , and potential data quality issues that need to
be addressed during the cleaning process.

- HANDLING MISSING VALUES
  
Missing values occurs when data is not available for certain observations or variables.

Strategies for handling for handling missing values include imputation (replacing missing 
values with estimated values), deletion of records or variables or flagging missing 
values as a separate category.

- REMOVING DUPLICATES
  
Duplicates records can distort analyses results and leads to incorrect insights.

Data cleaning involves ,identifying and removing duplicate records based onspecific criteria,
such as matching key fields or combination of fields.

- STANDARDIZING AND FORMATTING DATA
  
Standardizing data involves converting data into consistent format or unit of measurement.

This step ensures that the data is compatible and can be compared or combined across different
sources.

Formatting data includes tasks such as correcting inconsistent data formats, transforming text case,
or normalizing categorical values.


### DATA TRANSFORMATION USING POWER QUERY EDITOR

Power Query Editor is a powerful data transformation tool in Power BI that allows users to shape,
clean, and refine data before loading it into their models. It is a data preparation tool within
Power BI Desktop. It provides a visual interface for data transformation and data cleaning tasks
such as filtering, sorting, grouping, pivoting , splitting columns, merging data from multiple
sources.

### ACCESSING POWER QUERY EDITOR

- In Power BI Desktop, click on 'Transform Data' button in the home tab to launch Power Query Editor.

- Alternatively, right click on a data source in the "Data" pane and select "Edit Query"

--------------

### PROBLEM SOLVING

Extensively clean the Employee CSV Dataset provided under the dirty Datasets folder in the drive.

### SOLUTION

How to connect to a data sources

- Select "Get Data"

Click on the 'Get Data' button in the Home tab of the Power BI Desktop ribbon.

- Choose a Data Source

A dialog box will appear with a list of data sources options. select the desired data source type.
such as database, file, or online services

- Select a connection command.

Depending on the choosen data sources. Power BI offer different connection method.

- Select Transform data

For futher cleaning and transformation of data using Power Query Editor before loading.


#### Some actions in cleaning the Employee csv

TO RENAME A COLUMN :

Double tap on the header to rename

TO MAKE A DUPLICATE:

Select table and right click, click on duplicate

TO REPLACE : 

Highlight the column and right click , click on the replace and insert your values

TO MERGE THE LAST NAME AND FIRST NAME AS FULL NAME :

Click and use control button , select the first name column
and the last name column. right click and click on merge button. insert the separator
and type in the new name and press ok.

DATE OF BIRTH ERROR:

Power BI recognizes date format as y/m/d.

In the case of Date type error ( different seprators in the date column), you standardize
by using replace function to correct the different seperators. And if the error still persists
check the Date format.

To correct the date format, split all the components in Date column into day, month and year. 
by right clicking on the column , select split column by delimeter then click ok

To merge the three column. using the control button, select the year , month, day column accordingly
and right click . select the merge button, indicate the separator and rename it. press ok.

Go back tp Date of birth column header and change the data type to date.


TO REMOVE A COLUMN :

Select the column , right click and click remove


TO TRIM, CAPITALIZE AND LOWER CASE:

Right click on the column , click on Transform and choose the option

------------

Then close and apply , your table will be loaded to Power BI.















  
