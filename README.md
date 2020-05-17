
Bigdata Project : Airline Market Analysis:<br>
•	Analysis of flight data for US for a period of 20 years.<br>
•	Identifying trends and patterns over the period of time.<br>
•	Using Spark Dataframe and Spark SQL for handling large data efficiently and Amazon S3 as the data lake.<br>
• Performance Optmization:<br>
    - 1. Repartitioning of the dataframe with optimized number of partitions & Speeding up Shuffle.partitions.<br>
    - 2. Pulling data sets into a cluster-wide in-memory cache.<br>
    - 3. Using Apache Parquet,columnar storage format which support flexible compression options and also provides an efficient encoding system.<br>

Analysis: <a href="https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/8891199222519419/1251010126247737/720247590727539/latest.html"> Notebook </a>

**Architecture**:
<br>
![Architecture](https://github.com/aashish-bidap/Flight-Data-Analysis---BigData/blob/master/Architecture.png)
