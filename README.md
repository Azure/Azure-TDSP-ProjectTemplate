# TDSP Project Structure, and Documents and Artifact Templates

This is a general project directory structure for Team Data Science Process developed by Microsoft. It also contains templates for various documents that are recommended as part of executing a data science project when using TDSP. 

[Team Data Science Process (TDSP)](https://github.com/Azure/Microsoft-TDSP) is an agile, iterative, data science methodology to improve collaboration and team learning. It is supported through a lifecycle definition, standard project structure, artifact templates, and [tools](https://github.com/Azure/Azure-TDSP-Utilities) for productive data science. 


**NOTE:** In this directory structure, the **Data folder is NOT supposed to contain raw or processed data**, which could be big in size. It is only supposed to contain INFORMATION or DOCUMENTATION about the data, such as:
1. Data definitions
2. Why and how raw is converted into processed data
3. Location of the data in storage containers in Azure blobs, Azure Data Lake, SQL server etc.

The two documents under Docs/Project, namely the [Charter](./Docs/Project/Charter.md) and [Exit Report](./Docs/Project/Exit%20Report.md) are particularly important to consider. They help to define the project at the start of an engagement, and provide a final report to the customer or client.

**NOTE:** In some projects, e.g. short term proof of principle (PoC) or proof of value (PoV) engagements, it can be relatively time consuming to create and all the recommended documents and artifacts. In that case, at least the Charter and Exit Report should be created and delivered to the customer or client.
