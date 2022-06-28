# Internet-Access-at-Home-WI-

Each year, the Wisconsin Department of Instruction (DPI) sends out the "Internet Access at Home" Survey to determine how many of their students have reliable access at home. In this project, I clean and analyze that data to describe the connection between Internet access and factors such as locale (urban vs. suburban vs. rural), population, and per capita/median income). 

---Section 1: Gathering and Aggregating Data (Excel)---
I downloaded the Student Internet Access Messy Data from the DPI's open data portal. I also downloaded data on population, locale, and income by county from the DPI and the US Census Bureau. 
I imported all tables into the same Excel Workbook. I used VLOOKUP to combine all relevant variables into a single Excel sheet. I filtered out and fixed #N/A errors caused by inconsistencies among tables. 
The Student Internet Access data was very messy, so I completed a data cleaning checklist:

Creating descriptive but simple column names, rearranging the columns' order to match the survey,deleting unnecessary columns, changing data types (the percentage columns were in number format), removing duplicates, and trimming cells. 
An original version of the data was saved, and all changes were documented in comments. The data cleaning checklist above is a summary of those comments. 
Unfortunately, this data was not complete enough to draw any meaningful conclusions from analysis. 
