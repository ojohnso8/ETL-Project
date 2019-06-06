# ETL-Project
ETL Project

Final Report:

Extract: Original data sources were CSV files from data.world and the Guttmacher Institute. 

Transform: We transformed the data using Pandas. We renamed the ‘U.S. State’ column from the data.csv to ‘state’ to match formatting in the cities.csv file and removed the ‘id’ column from the cities.csv. We then merged the two dataframes into one on “state”.

Load: We loaded the merged data into a SQL database using Postgres because our data was already structured in table format. 
