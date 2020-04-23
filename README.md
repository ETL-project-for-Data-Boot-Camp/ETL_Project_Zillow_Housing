ETL Project
Zack Snyder, Yin Cai, Tricia Palomino



Data Cleanup & Analysis
•	The sources of data:
o	Zillow Housing Price 
o	US Zip Code Latitude and Longitude

•	The type of transformation needed for this data (cleaning, joining, filtering, aggregating, etc):
o	Cleaning: Text to columns
o	Filters: Most recent year (2003), Exclude Time Zone, 
o	Joins: Zillow (base) with left join of Lat/Long dataset
o	Aggregate: 12 mo. Average by zip

•	The type of final production database to load the data into (relational or non-relational).
o	SQL: zip = zit

•	The final tables or collections that will be used in the production database.

