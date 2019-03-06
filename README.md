# ETL-Project

#Salsa Database Project

Extract Phase:
Used beautiful soap and splinter to scrape a page in order to extract the top rated salsa records per user on RateYourMusic.com
Also collected information about the artis from last.fm and merged with the main data.

Transform Phase:
The data was converted to dataframe format in pandas to process them in tabular format to be stored to MongoDB.

Load:
The data was processed and loaded onto a new database on MongoDB.
