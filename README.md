# Hexaware-Project-2-Hybrid-Cloud-Data-Movement-

This project demonstrates data ingestion, transformation, and analysis using Azure Databricks and PySpark. The source data contains student details, and the goal is to process this data to extract meaningful insights.

**Project Overview**
The project involves:

    1, Data Ingestion: Importing employee data stored in Azure Blob Storage.
    2. Data Processing: Filtering and transforming data using PySpark.
    3. Data Analysis: Performing operations such as filtering employees based on salary and extracting specific information.
    4. Output: Saving the transformed data back to Azure Blob Storage.

**Tech Stack**

    1. Azure Blob Storage: For storing input and output data.
    2. Azure Databricks: For running the PySpark scripts.
    3. PySpark: To perform filtering and transformations.
    4. Python: Core language used for coding.

**Execution Steps**

    1. Prerequisites
           1. Azure Subscription with Blob Storage and Databricks.
           2. Python environment set up.
          

    2. Steps to Run
    
        1. Upload the Data:
        
            Upload dbo.Student.txt to Azure Blob Storage under a container, e.g., target.
        
        2. Run the Notebook:
        
            1. Open the Databricks notebook (student_analysis.ipynb).
            2. Connect to Azure Blob Storage using Spark configurations.
            3. Execute the filtering and transformation logic.
        
        3. Verify the Output:
        
            1. The processed data will be saved back to Blob Storage.
                Example: Filtering studnets with marks > 55.
        
        4. Architecture Diagram:
        
            1. Refer to architecture/architecture_diagram.png for the workflow.
        
        
**Tasks Performed**

        1. Data ingestion from Azure Blob Storage.
        2. Filtering students based on conditions (e.g., marks threshold).
        3. Adding new columns using transformations in PySpark.
        4. Writing the transformed data back to storage.

**Results**

        1. Processed data outputs were validated and stored in Azure Blob Storage.
        2. Key observations can be summarized in the Analysis section.
