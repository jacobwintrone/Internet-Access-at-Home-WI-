# Internet-Access-at-Home-WI-

Each year, the Wisconsin Department of Instruction (DPI) sends out the "Internet Access at Home" Survey to determine how many of their students have reliable access at home. In this project, I clean and analyze that data to describe the connection between Internet access and factors such as locale (urban vs. suburban vs. rural), population, and per capita/median income). 

Section 1: Gathering, Aggregating, and Cleaning Data (Excel):
First, I downloaded the Student Internet Access Messy Data from the DPI's open data portal. I also downloaded data on population, locale, and income by county from the DPI and from Wikipedia. 

Aggregation:
After importing all relevant tables, I used VLOOKUP to combine all relevant variables into a single Excel sheet. I then filtered for and fixed #N/A errors which resulted from different datasets naming school districts slightly differently. 

Cleaning:
The Student Internet Access Messy Data file was very raw, so I went through a complete data cleaning checklist:

Creating descriptive column names, rearranging the columns' order to match the survey, adding the survey questions to the Excel sheet to give context to the column names, deleting unnecessary columns, changing data types (the percentage columns were in number format), removing duplicates, and trimming cells. 

An original version of the data was saved, and all changes were documented in comments. The data cleaning checklist above is a summary of those comments. 
After cleaning the data, I calculated a few descriptive statistics across the state of Wisconsin, as well as a few simple visualizations to explore the data. 

Section 2: Data Analysis and Visualization with R. 
