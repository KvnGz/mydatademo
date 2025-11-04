# Consumer Finiancial Complaints

## Overview
This project is focused on improving customer satisfication, it describe how consumer rate certain products.

## Aim & Objectives
- To note the total number of complaints overtime
- Company's response to the complaints
- The complaints per companies sizes

## The steps taken
- Data gathering
- Data cleaning
- Data Modeling
- Analyze
- Visualization

### Data gathering
The data was collected from so and so source [you can get the data here](C:\Users\USER\Downloads\DataDNA-Dataset-Challenge.zip\DataDNA Dataset Challenge - Consumer Financial Complaints Dataset - October)

The tool used in this project is Microsoft PowerBI [You can get it here](https://www.microsoft.com/en-us/download/details.aspx?id=58494)

### Data cleaning
I removed missing valuess. I cleaned with power query.

### Data Modeling
I connected relationship between the tables.

### Analyze
Here is where the majority of the work went down.
- To get the total number of complaints

DAX expression
  ```
  complaints = COUNTROWS(complainttable, column)
  ```
### Visualization
