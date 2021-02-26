CSV files downloaded from the Citi Bike website at https://s3.amazonaws.com/tripdata/index.html were too large 
to upload to git hub without creating push issues. To recreate csv files used in Tableau, prior to running 
the jupyter notebook data_cleanup.ipynb, execute the following steps: 

1. Download the following zip files from https://s3.amazonaws.com/tripdata/index.html
201901-citibike-tripdata.csv.zip
201902-citibike-tripdata.csv.zip
201903-citibike-tripdata.csv.zip
201904-citibike-tripdata.csv.zip
201905-citibike-tripdata.csv.zip
201906-citibike-tripdata.csv.zip
201907-citibike-tripdata.csv.zip
201908-citibike-tripdata.csv.zip
201909-citibike-tripdata.csv.zip
201910-citibike-tripdata.csv.zip
201911-citibike-tripdata.csv.zip
201912-citibike-tripdata.csv.zip

2. Extract the csv files, and save them to the following path relative to the jupyter notebook: 
/citibike_downloads

3. ***NOTE*** Do not open csv file in Excel prior to loading into pandas; doing so will create an error in the date formatting.
If a previous of the fields within the csv files is desired, make a copy.  

4. Run the jupyter notebook