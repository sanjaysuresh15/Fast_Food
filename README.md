# Fast_Food - ETL Project

![Mcdonalds](Resources/mcdonalds_logo.jpg)

## Goal of the project: ETL applied to Fast Food and Population Data. 

### Data Source: 

Our first data source is from Wikipedia. We web scraped the table and transformed the data into Pandas Dataframe. 

[Population Table](https://simple.wikipedia.org/wiki/List_of_U.S._states_by_population)

<img src="Resources/wiki_table.PNG" width="800">

Our second data source is from Kaggle. We downloaded the CSV file from the website for the Fast Food Data.  

[Fast Food Data Set](https://www.kaggle.com/datafiniti/fast-food-restaurants)

<img src="Resources/fastfood_excel.PNG" width="500">


### Extract and Transform: 

#### We select the population related data from the wikipedia table and grouped by state. 

<img src="Resources/groupby.PNG" width="500">


#### Then we merged with the Fast Food Data. 


<img src="Resources/merge_raw.PNG" width="800">

<img src="Resources/merge.PNG" width="800">


#### We produced the top ten states with the most fast food restaurants after we merged the data. 

<img src="Resources/Top10s.PNG" width="500">


#### We visualized the data with a bar chart graph. 

<img src="Resources/barchart.PNG" width="500">


### Load:

#### We loaded the tables into a SQL database. 

<img src="Resources/db_tables.png" width="500">
