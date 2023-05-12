# Airplane_ETL
ETL project using aviationstack API.

# Extract
Data is extracted from real time flights using the aviationstack API.
This is done with Python in a Jupyter notebook.
A JSON file of the raw data is also loaded as a backup.

# Transform
The data is then cleaned and transformed into pandas dataframes.
The data is then loaded into a sqlite database for further transformations and queries of specific information.

# Load
The resulting dataframes and queries are finally exported as csv files.
