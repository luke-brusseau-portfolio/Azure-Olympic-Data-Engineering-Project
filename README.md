# Azure-Olympic-Data-Engineering-Project
Azure Data Engineering Project using Olympic data from the 2021 Olympics

Olympic Data Analytics | Azure End-To-End Data Engineering

Intro

This project dives into analyzing Olympic data using the full power of Azure Cloud Computing. By leveraging tools like Azure Data Factory, Data Lake Gen 2, Azure Databricks, and Azure Synapse Analytics, I transformed raw data into meaningful insights. From data extraction to final analysis, each step showcases how cloud technology can streamline and enhance the process of working with large datasets.


Skills

Data Integration: Orchestrating and managing data pipelines.
Data Transformation: Cleaning and refining raw data for analysis.
Data Storage Management: Efficiently storing and organizing large datasets.
Data Analytics: Crafting and executing SQL queries to extract insights.
Cloud Computing: Leveraging cloud platforms for scalable data processing.


Tools

Azure Data Factory: For data extraction and pipeline management.
Azure Data Lake Gen 2: For scalable and secure data storage.
Azure Databricks: For data transformation using Apache Spark.
Azure Synapse Analytics: For data analysis using SQL queries.
Apache Spark: For processing and transforming large datasets.


Step-by-Step Breakdown

Data Extraction with Azure Data Factory
- The journey begins by tapping into a 2021 Tokyo Olympics dataset from Kaggle with HTTP Requests. Using Azure Data Factory, a powerful data integration service, I designed and managed a pipeline to seamlessly extract this raw data. Data Factory's ability to orchestrate data movement from various sources proved invaluable in efficiently gathering large volumes of Olympic statistics.
- The raw data can be found in the Github Repository under olympic_data

Data Storage in Azure Data Lake Gen 2
- Once extracted, the raw data found its home in Azure Data Lake Gen 2, a scalable and secure data storage solution. This data lake acts as a centralized repository, ensuring that the data is safely stored and readily accessible for the next stages of processing. The structure and management capabilities of Data Lake Gen 2 made it the ideal choice for storing the datasets involved in this project.

Data Transformation with Azure Databricks
- With the data securely stored, the next step was to transform it into a more usable format. Enter Azure Databricks, where I employed Apache Spark to clean, refine, and transform the raw data. This step was crucial in preparing the data for analysis, as it involved filtering out noise, normalizing values, and making sure all of the schema was correct for data usability. The transformed data was then loaded back into Azure Data Lake Gen 2, ready for analysis. 
- The IPython Notebook containing the Apache Spark Transformation Code is included in the Github Repository under Tokyo Olympic Transformation.ipynb

Data Analytics with Azure Synapse Analytics
- The final stage of the project focused on uncovering insights from the transformed data using Azure Synapse Analytics. By crafting and executing SQL queries, I was able to extract meaningful information from the Olympic data. I was then able to take that data and create basic visuals using the Azure Synapse chart tools
-  The SQL Queries used can be found in the Github Repository under sqlQueries


Summary

This project has significantly contributed to both my personal and professional development. It marked my first successful completion of a project entirely within an Azure cloud environment. Although the coding tasks were not the most complex, the experience allowed me to gain a comprehensive understanding of the diverse services Azure provides. Furthermore, I acquired important knowledge on how to leverage these services effectively to meet the objectives set for this project.
