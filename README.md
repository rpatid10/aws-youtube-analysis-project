# aws-youtube-analysis-project

Project Name : YouTube Analysis using AWS Cloud
1.  Data Acquisition: Downloaded data from Kaggle and stored it in the landing zone on Amazon S3 (raw data in JSON and CSV formats).
2.  Data Processing: Utilized AWS Lambda and AWS Glue for data processing, cleaning, and uploading to the cleaned layer on S3 (in Parquet format).
3.  ETL & Querying: Performed ETL operations, including data joins, using AWS Glue Studio, and ran queries using Amazon Athena to analyze the data.
4.  Reporting & Visualization: Developed an analytics layer and created an interactive dashboard using Amazon Quick Sight to visualize key insights.

Services Used: S3, Lambda, Glue, Athena, Quick Sight, CloudWatch.

Original dataSet Link : https://www.kaggle.com/datasets/datasnaek/youtube-new
