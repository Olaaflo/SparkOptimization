# SparkOptimization
Master Thesis Title:  
  Spark Optimization: A Column Recommendation System for Data Partitioning and Z-Ordering on ETL Platforms  


This repository contains notebooks utilized in the master thesis.   
The notebooks were developed in the ETL platform Databricks.


<a name="desc"></a>
## Short Description:

Script  | Description
------------- | ------------- 
[EventLogToDelta.ipynb](https://github.com/havardMoe/Twitter_Sentiment/blob/c5bbb9a0e545c8305d869071e505ab6a631d7ca3/scripts/fetch_twitter_data.py)  | Fetches data from the Twitter API with tweepy
[RawDataToOrganized.ipynb](https://github.com/havardMoe/Twitter_Sentiment/blob/c5bbb9a0e545c8305d869071e505ab6a631d7ca3/scripts/load_data_to_hdfs.sh)  | Used to load data from namenode into HDFS.
[RuleBased_count.ipynb](https://github.com/havardMoe/Twitter_Sentiment/blob/c5bbb9a0e545c8305d869071e505ab6a631d7ca3/scripts/spark_set_up_raw_data.py)  | Set up raw data table in Hive and write in data.
[RuleBased_runTimeWeightedCounts.ipynb](https://github.com/havardMoe/Twitter_Sentiment/blob/f9253edb3affe3b40b68b7796c474d6c8e1bea88/scripts/set_up_hiveDB.sql)  | Old file used to set up HiveDB directly in Hive.
[RuleBased_stepWeights.ipynb](https://github.com/havardMoe/Twitter_Sentiment/blob/c5bbb9a0e545c8305d869071e505ab6a631d7ca3/code/preprocessing/preprocessing.py)  | Used to clean the data.
[RuleBased_weightedCount.ipynb](https://github.com/havardMoe/Twitter_Sentiment/blob/c5bbb9a0e545c8305d869071e505ab6a631d7ca3/code/preprocessing/preproc_functions.py)  | Functions used for preprocessing.
[SetupTables.ipynb](https://github.com/havardMoe/Twitter_Sentiment/blob/f9253edb3affe3b40b68b7796c474d6c8e1bea88/code/analysis/daily_wordlist_DF.py)  | Benchmark using MapReduce job on Spark DF.
[StatisticsCalc.ipynb](https://github.com/havardMoe/Twitter_Sentiment/blob/f9253edb3affe3b40b68b7796c474d6c8e1bea88/code/analysis/daily_wordlist_MR.py)  | Benchmark using MapReduce job on Spark RDD.
[Validators.ipynb](https://github.com/havardMoe/Twitter_Sentiment/blob/f9253edb3affe3b40b68b7796c474d6c8e1bea88/code/analysis/analysis.py)  | Contains functions and classes used for analysis.
