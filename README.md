# Fast_Food - ETL Project

![Mcdonalds](Resources/mcdonalds_logo.jpg)

## Goal of the project: ETL applied to Fast Food and Population Data. 

* Data Source: 

Our first data source is from Wikipedia. We web scraped the table and transformed the data into Pandas Dataframe. 

[Population Table](https://simple.wikipedia.org/wiki/List_of_U.S._states_by_population)

Our second data source is from Kaggle. We downloaded the CSV file from the website for the Fast Food Data.  

[Fast Food Data Set](https://www.kaggle.com/datafiniti/fast-food-restaurants)

### Example of Data:

![Wiki_table](Resources/wiki_table.PNG)

![fastfoodexcel](Resources/fastfood_excel.PNG)

#### Extract and Transform: We select the population related data from wikipedia table and grouped by state. 



![1st_groupby](Resources/groupby.PNG)

##### Then we merged with the Fast Food Data. 

![merge_raw](Resources/merge_raw.PNG)

![merge](Resources/merge.PNG)

##### We produced the top ten states with the most fast food restaurants after we merged the data. 

![merge](Resources/Top10.PNG)

We visualized the data with a bar chart graph. 

![merge](Resources/barchart.PNG)


Load: 
