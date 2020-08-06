# WALMART Holiday Sales Analysis

NEXGEN Team Members: Tasneem Bhaijee, Hannah Golledge, Yen Tran, Adil Ahmed

## Project Objectives: 
Extract, transform and load data to answer below questions:
* Analyze Walmart sales trends during the course of years 2010 thru 2013
* Analyze sales data for special contributing factors towards sales impact


## EXTRACT

Extract and load information from multiple data sources

* Master file - Data source: https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016?select=master.csv 
* Population by educational attainment level, sex and age (%) - main indicators [edat_lfse_03] - Data source: Eurostat
* Literacy rate, adult total (% of people ages 15 and above) - Data source: https://data.worldbank.org/indicator/SE.ADT.LITR.ZS
* datasets_23752_30346_countries of the world - Data source: Worldbank
* Country rank order - Data source: https://www.cia.gov/library/publications/the-world-factbook/rankorder/rawdata_2127.txt

## TRANSFORM

*  Review CSV files; read them
*  Determine data types definition
*  Cleanup Process
    * Explore data info in every csv file to ensure all data is complete;  if  incomplete, we dropped the data
    * Converted the date
    * Dropped empty fields (Markdowns); drop NA’s
    * Merged data using inner joins based on common columns (i.e., Store, Date, IsHoliday)


## Analysis 
* Used Jupyter Notebook Code for Plotting Average Weekly Sales

* To get the color palette for the bar charts, we imported the seaborn library:
    import seaborn as sns

![alt text](https://github.com/tbhaijee/project_one/blob/master/results/image2.PNG)

![alt text](https://github.com/tbhaijee/project_one/blob/master/results/image1.PNG)

