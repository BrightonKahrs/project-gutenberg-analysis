# Objective
This project is created to explore how Microsoft Fabric and Azure OpenAI can be used to analyze textual data. This project goal is to only leverage Fabric + AOAI to see how powerful using only these two architectural components can be for text based analysis. Microsoft Fabric offers the OneLake which means any type of data, including unstructured text, can be stored. The powerful combination of Microsoft Fabric and Azure OpenAI can unlock valuable insights in your text data like never before!

This project explores the following capabilities of Azure OpenAI, using Microsoft Fabric.
1. Entity Extraction
2. Text Summarization
3. Text Classification
4. Text Embeddings and Semantic Similarity

*Note: This project leverages data from Project Gutenberg, the first provider of free eBooks. Please consider donating at https://www.gutenberg.org/donate/*

*This project should take about 1 hour to complete, follow the project steps below to get started*

# Prerequisites
1. An [Azure](https://azure.microsoft.com/en-us/free/) subscription
2. Contributor access to a [Microsoft Fabric workspace](https://learn.microsoft.com/en-us/fabric/get-started/workspaces)
3. Access to a [Microsoft Fabric F64 capacity](https://learn.microsoft.com/en-us/fabric/enterprise/buy-subscription) or higher (The Fabric trial FT1 sku will not work). This capacity should be connected to your workspace.

*Note: an alternative approach is to leverage [Azure OpenAI Service](https://learn.microsoft.com/en-us/azure/ai-services/openai/how-to/create-resource?pivots=web-portal)*

# Architecture
![Project Architecture](./images/project_architecture.png)

# Steps
![Project Steps](./images/project_steps.png)

1. Build Lakehouse

    Go to your workspace, select the 'Data Science' experience, and create your Lakehouse. Feel free to name it whatever you like!
    ![Build Lakehouse](./images/build_lakehouse.gif)

2. Ingest eBook Data onto OneLake

    Download or clone this repo to access the Jupyter Notebooks in the scripts folder, then import the 01_data_ingestion_and_prep notebook
    ![Import Notebook](./images/import_notebook.gif)
    *If you do not see the Import Notebook option, make sure you are on the Data Science or Data Engineering experience*
    
    

3. Enrich eBook Data using Azure OpenAI
4. Analyze Enriched Data using Notebooks and Power BI
