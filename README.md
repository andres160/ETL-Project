# ETL-Project

#Salsa Database ETL Project

Extract:
Used beautiful soap and splinter to scrape a page in order to extract the top rated salsa records per user on RateYourMusic.com
Also collected information about the artis from last.fm and merged with the main data.
The script would run through all 4 pages of a pre-set query link (search) that returns "Top singles from all times" from genres "Salsa" as "Rate by all RYM users".

Transform:
Beautiful Soup was used to only keep the "Artist", "Title", and "Rating" (looked within the html tags and looped through all the results). The returned data was converted into a two-dimensional table (pandas dataframe) that could be processed into a collection under a new MongoDB document. 

Load:
The data was processed and loaded onto a new database on MongoDB.
