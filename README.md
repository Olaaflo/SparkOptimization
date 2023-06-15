# SparkOptimization
Master Thesis Title:  
  Spark Optimization: A Column Recommendation System for Data Partitioning and Z-Ordering on ETL Platforms  


This repository contains notebooks utilized in the master thesis.   
The notebooks were developed in the ETL platform Databricks, so the Workflows binding the notebooks together are not available here.


<a name="desc"></a>
## Short Description:

Script  | Description
------------- | ------------- 
[EventLogToDelta.ipynb](EventLogToDelta.ipynb)  | Loads data from Spark event log files into a table. 
[RawDataToOrganized.ipynb](RawDataToOrganized.ipynb)  | Structures the events into rows and parses and extracts event log information to create a operations and queries table.  
[RuleBased_count.ipynb](RuleBased_count.ipynb)  | Code for 'Simple Count' method. 
[RuleBased_runTimeWeightedCounts.ipynb](RuleBased_runTimeWeightedCounts.ipynb)  | Code for Run Time Weights method.
[RuleBased_stepWeights.ipynb](RuleBased_stepWeights.ipynb)  | Code for Discrete Timestamp Weights method.
[RuleBased_weightedCount.ipynb](RuleBased_weightedCount.ipynb)  | Code for  Timestamp Weights method.
[SetupTables.ipynb](SetupTables.ipynb)  | Sets up tables to be used.
[StatisticsCalc.ipynb](StatisticsCalc.ipynb)  | Notebook for createing statistics.
[Validators.ipynb](https://github.com/havardMoe/Twitter_Sentiment/blob/f9253edb3affe3b40b68b7796c474d6c8e1bea88/code/analysis/analysis.py)  | Contains functions and classes used for analysis.
