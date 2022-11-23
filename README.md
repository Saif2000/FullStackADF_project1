# FullStackADF_project1
This project has deployed all the tech stack :
1. Azure Blob Storage
2. Azure Data Lake Gen2 Storage
3. Azure Data Factory
4. Azure Data Bricks
5. SQL Data Warehousing




Azure Blob Storage : Dataset from local machine is being uploaded inside this blob storage.

Azure Data Lake Gen2 Storage: Dataset from blob storage is copied to ADLS gen2 storage account using pipeline created inside Azure Data Factory.

Azure Data Factory : This azure service is used to build pipeline which copied dataset from blob storage to ADLS gen2 storage.
In framing this project , the activities that are included within the pielines are :
    1. MetaData Activity
    2. ForEach Activity
    3. if condition Activity
    4. Copy Activity
    
    
Azure Data Bricks : This azure service is used to transform Data within the Databricks environment. Post that, Dimesnions and Fact Tables are created inside the databricks Notebook using Pyspark, SparkSQL, Magic SQL commands.

Note : The sql datawarehousing is being done in the file named "Project1Saif.dbc" Azure Data Bicks folder using Pyspark, spark sql and sql magic command within the databricks environment.
