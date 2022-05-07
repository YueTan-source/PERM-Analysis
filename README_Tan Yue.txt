Direcotry: ana_code
A zip file containing source code to clean data for the analytic Clean.class, Clean.jar, CleanMapper.class
Actual code can be found in etl_code directory


Direcotry: data_ingest
Code and commands for data ingestion

data_ingest/Upload.txt
//command to upload the source code and data to HDFS 

data_ingest/Download_result.txt
//command to get the cleaned data from HDFS to local



Direcotry: etl_code
Code for cleaning data
Command to run the code can be found in data_ingest/Upload.txt
INPUT DATA can be found in root directory: perm_input.csv
OUTPUT DATA: perm_output.csv


Direcotry: profiling_code
Data documentation with column information and data type


Direcotry: screenshots
Queries are run on Hive.
Input data is the output of MapReduce cleaned data.


