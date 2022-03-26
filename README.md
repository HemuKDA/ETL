# Goal of the ETL
Goal is to take the [World Bank Project data set](https://datacatalog.worldbank.org/dataset/world-bank-projects-operations) and merge this data with the [World Bank indicator data](https://data.worldbank.org/indicator/SP.POP.TOTL). Then load the merged data into a database.

The process is to transform these data sets in different ways. And finally, writing a single Python module that reads in these date sets, transforms them, and loads the results into the database all in one step.

# Extracting data from a file

The first step in an ETL pipeline is extraction. Data comes in all types of different formats, and extracting data from csv files, json files, xml files, SQL databases, and the web.
