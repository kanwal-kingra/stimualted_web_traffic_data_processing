# stimualted_web_traffic_data_processing
This repository contains a scalable data processing pipeline built with Apache Spark (PySpark) for analyzing simulated web traffic data. 
It demonstrates how to ingest, process, and analyze large-scale log data using distributed computing.
### Tools Used
1. Python
2. PySpark
3. Jupyter (for exploration)
4. Pandas & Matplotlib (for visualizations)

### What It Does
1. Cleans and preprocesses log data
2. Groups user actions into sessions
3. Calculates traffic stats like:
  - Top pages
  - Session length
  - Traffic sources
  - Last active user
4. Converts to Global Temporary Views to analyse using SQL in pyspark
5. Converted pyspark DataFrame to Pandas DataFrame
6. Plotted various insights from data using Matplotlib (Web Page Visits, users per device)


### Data is simulated for testing purposes, Can be extended for real-time or cloud-based processing.
