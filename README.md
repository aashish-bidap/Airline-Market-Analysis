
# Title : US Airline Market Analysis <br>

## Description
-	Objective of the project is to analyse flight data for US for a period of 20 years(~128 million rows) to find patterns to gauge different choices of travel.
-   Identifying trends and patterns over the period of time.<br>
-	Using Spark Dataframe and Spark SQL for handling large data efficiently and Amazon S3 as the data lake.<br>

## Technology Used
-   Big Data Analysis using Spark
-   Amazon Web Services

## Environment
Python(PySpark), Spark SQL, Databricks, Amazon S3,Apache Parquet

Analysis: <a href="https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/8891199222519419/1251010126247737/720247590727539/latest.html"> Notebook </a>

**Architecture**:
<br>
![Architecture](https://github.com/aashish-bidap/Flight-Data-Analysis---BigData/blob/master/Architecture.png)

<br>

**Analysis 1 : Exploratory Data Analysis of Data:** <br>
![analysis1](https://github.com/aashish-bidap/Flight-Data-Analysis---BigData/blob/master/analysis-1.png)

**Analysis 2 : Impact of Global Recession:** <br>
![analysis2](https://github.com/aashish-bidap/Flight-Data-Analysis---BigData/blob/master/analysis-2.png)

**Analysis 3 : Fraud Data Analysis:** <br>
![analysis3](https://github.com/aashish-bidap/Flight-Data-Analysis---BigData/blob/master/analysis-3.png)

## Performance Optmization
    - 1. Repartitioning of the dataframe with optimized number of partitions & Speeding up Shuffle.partitions.<br>
    - 2. Pulling data sets into a cluster-wide in-memory cache.<br>
    - 3. Using Apache Parquet,columnar storage format which support flexible compression options and also provides an efficient encoding system.<br>
