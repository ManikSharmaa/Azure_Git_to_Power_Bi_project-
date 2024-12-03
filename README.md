### Azure Git to Power Bi project 

I implemented a Medallion Architecture in this project, creating bronze, silver and gold layer in my Azure Data Lake Gen2 for categorizing the data into Raw, Transformed and Final Product. 

![storage_account](https://github.com/user-attachments/assets/5f1cf7c4-f868-446d-8f2a-d8c6ce4e8346)


- Dynamically ingested 10 files from a GitHub repository into the Bronze Layer of Azure Data Lake using Azure Data Factory. 
![Git hub](https://github.com/user-attachments/assets/82897ea2-62eb-4d96-8838-172466511cc2)

## ---------------------------------------------

![pipeline](https://github.com/user-attachments/assets/08eda633-44ac-4aec-a120-7bfb89cf206f)

## ---------------------------------------------

![bronze Layer](https://github.com/user-attachments/assets/9375c8c9-7e57-4f42-bc97-4bb89345c44b)


- 🔄 Transformed raw data in Azure Databricks and stored clean, structured data in the Silver Layer. 

![Databricks](https://github.com/user-attachments/assets/5d2e7f68-774b-4fd2-88b7-c2de0333f3d8)


- 🎯 Created views and external tables in Azure Synapse Analytics to populate the Gold Layer, acting as the serving layer. 

![Synapse_views](https://github.com/user-attachments/assets/3cc6e4f3-049b-441b-89b9-44ef58b8f42f)

## ----------------------------------------------------------------------------------------

![synapse_extTbales](https://github.com/user-attachments/assets/192fe4ea-7eda-49c1-bd7d-0c25be659d1f)

- 📊 Connected Power BI to Synapse and visualized key insights using the Serverless SQL endpoint. 

![Power BI ](https://github.com/user-attachments/assets/4d22c3a8-f759-4d52-b199-d905581ffa8b)



# Tools: Azure Data Factory, Azure Databricks, ADLS Gen2, Azure Synapse Analytics, Power BI. 

