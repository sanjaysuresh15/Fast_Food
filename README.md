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

Extract: 

![1st_groupby](Resources/groupby.PNG)



```python
population = "Resources/US_population_2018.csv"
population = pd.read_csv(population)
population.head()
Transform

![merge](Resources/merge.PNG)

![merge_raw](Resources/merge_raw.PNG)


Load: 







![chart](Resources/barchart.PNG)




