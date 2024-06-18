# Real-Time-Data-Analysis-Using-Kafka-End-To-End-Data-Engineering-Project

🔍 Project Overview:
- Data Source: Stock Market App Simulation generating real-time data.
- Producer: Python SDK to simulate data production.
- Broker: Apache Kafka hosted on Amazon EC2 for seamless data streaming.
- Consumer: Processed data stored in Amazon S3.
- Data Catalog: AWS Glue to organize and manage metadata.
- Querying: Amazon Athena for running SQL queries on the processed data.
- Visualization: Amazon QuickSight for data visualization and insights extraction.

-Kafkaproducer.ipynb - has the producer code for kafka which streams data onto the Kafka broker onto the EC2 instance
-Kafkaconsumer.ipynb - has the consumer code which receives data from the kafka broker running on EC2 instance
The csv used for this project is indexprocessed.csv, which has example data of stock market
