# Note: The TDSP is no longer supported.

The TDSP has been superceded by the [DSLP (Data Science Lifecycle Process)](https://github.com/dslp/dslp).

The repo template for the DSLP can be found at https://github.com/dslp/dslp-repo-template/.

## Why switch to DSLP?

The DSLP was designed to reflect modern data science workflows and paradigms.  

Because data science is multidiscplinary, we wanted to make it easier for people to collaborate on data science repos, which meant orienting workflows around using issues, pull requests, and a data science friendly branching strategy.

The DSLP also separates project management from the project content itself. In DSLP, all project management and collaboration moves into Issues and Pull requests, which means your repo contains only your code and documentation, not your project management. This makes it easier to enable opt-in workflows and keeps the project from getting stale with outdated project management documents.

There are also some key changes in the directory structure that make it easier to keep your codebase organized as you move from experimentation to production. This includes adding locations for things like environment definitions, pipeline/orchestration code, etc, cloud configuration, etc. It also separates prototyping code (e.g. notebooks) from code that you'll ship to production.

As the field of data science and machine learning evolved, there was a need to adapt workflows to make things easier for teams to get started and move to production. For more details please read the DSLP docs.


# TDSP Project Structure, and Documents and Artifact Templates

This is a general project directory structure for Team Data Science Process developed by Microsoft. It also contains templates for various documents that are recommended as part of executing a data science project when using TDSP. 

[Team Data Science Process (TDSP)](https://docs.microsoft.com/en-us/azure/machine-learning/team-data-science-process/overview) is an agile, iterative, data science methodology to improve collaboration and team learning. It is supported through a lifecycle definition, standard project structure, artifact templates, and [tools](https://github.com/Azure/Azure-TDSP-Utilities) for productive data science. 


**NOTE:** In this directory structure, the **Sample_Data folder is NOT supposed to contain LARGE raw or processed data**. It is only supposed to contain **small and sample** data sets, which could be used to test the code.

The two documents under Docs/Project, namely the [Charter](./Docs/Project/Charter.md) and [Exit Report](./Docs/Project/Exit%20Report.md) are particularly important to consider. They help to define the project at the start of an engagement, and provide a final report to the customer or client.

**NOTE:** In some projects, e.g. short term proof of principle (PoC) or proof of value (PoV) engagements, it can be relatively time consuming to create and all the recommended documents and artifacts. In that case, at least the Charter and Exit Report should be created and delivered to the customer or client. As necessary, organizations may modify certain sections of the documents. But it is strongly recommended that the content of the documents be maintained, as they provide important information about the project and deliverables.
