# ETL-Pipleline
ETL pipeline for accessing data from a website and processing it to meet the requirements,
creating an automated script that can extract the list of all countries in order of their GDPs in billion USDs (rounded to 2 decimal places), as logged by the International Monetary Fund (IMF). Since IMF releases this evaluation twice a year, this code will be used by the organization to extract the information as it is updated.

# The libraries needed for the code are as follows:

requests - The library used for accessing the information from the URL.

bs4 - The library containing the BeautifulSoup function used for webscraping.

pandas - The library used for processing the extracted data, storing it to required formats and communicating with the databases.

sqlite3 - The library required to create a database server connection.

numpy - The library required for the mathematical rounding operation as required in the objectives.

datetime - The library containing the function datetime used for extracting the timestamp for logging purposes.
