# Data-Pipeline-Retrieving-Storing-Data-PublicAPIs-Hive

## Objective :
To retrieve data from a public API selected from the list provided in https://github.com/public-apis/public-apis and store the data in Hive through HDFS. Additionally, you need to create an option for users to download the data as a CSV file from Hive.

## Technologies : 
Python, API, HDFS, Hive

### Deliverables :
+ Code that retrieves data from the chosen public API and stores it in Hive through HDFS
+ An option for users to download the data from Hive as a CSV file

### Approach:
1. Choose a public API from the list provided in API. Make sure to read the documentation and ensure that you understand the terms of use for the API.
2. Set up a development environment for the programming language you will be using (e.g. Python). Install any necessary libraries or dependencies.
3. Make a request to the API using a library such as requests and retrieve the data.
4. Parse the response from the API to extract the data you are interested in. Depending on the structure of the response, you may need to use a library such as json to parse the data.
5. Use the Hadoop File System (HDFS) API to store the data in Hive. You can use a library such as pyhive to connect to Hive and write the data.
6. Use a library such as pandas to convert the data to a CSV format.
7. Use the HDFS API to write the CSV file to a location that is accessible to users.
8. Test your solution to ensure that it is working as expected.
