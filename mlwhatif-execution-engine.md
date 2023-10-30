## Name



Efficient Data-Centric What-If Analyses on Native Machine Learning Pipelines using DuckDB



## Description



Software systems that learn from data with machine learning (ML) are used in critical decision-making processes. Unfortunately, real-world experience shows that the pipelines for data preparation, feature encoding and model training in ML systems are often brittle with respect to their input data. As a consequence, data scientists have to run different kinds of data centric what-if analyses to evaluate the robustness and reliability of such pipelines, e.g., with respect to data errors or preprocessing techniques. These what-if analyses follow a common pattern: they take an existing ML pipeline, create a pipeline variant by introducing a small change, and execute this pipeline variant to see how the change impacts the pipeline’s output score.

We recently proposed mlwhatif (https://github.com/stefan-grafberger/mlwhatif), a library that enables data scientists to declaratively specify what-if analyses for an ML pipeline, and to automatically generate, optimize and execute the required pipeline variants. Our approach employs ‘pipeline patches’ to specify changes to the data, operators and models of a pipeline. Based on these patches, we define a multi-query optimizer for efficiently executing the resulting pipeline variants jointly.

However, mlwhatif currently has no dedicated runtime, but just relies on non-parallel execution with libraries like pandas and scikit-learn. To improve performance, we want to investigate the usage of alternative runtimes for more efficient what-if analysis execution, e.g., using an in-process database like DuckDB and using parallelisation for independent model training and featurization operators.

DuckDB is an in-process SQL OLAP database management system that seemingly integrates with the Python ecosystem. Thanks to its efficient data transfer and some recently added features (https://github.com/duckdb/duckdb/pull/3700, https://github.com/duckdb/duckdb/pull/5867), it should now be possible to leverage DuckDB as a runtime for mlwhatif and its generated query plans using a mixture of ML and dataframe operations.

As part of this thesis project, you will investigate how to improve the performance of mlwhatif using a dedicated runtime.


The following literature is helpful to further understand the topic

*  Automating and Optimizing Data-Centric What-If Analyses on Native Machine Learning Pipelines, https://stefan-grafberger.com/mlwhatif.pdf

*  Data distribution debugging in machine learning pipelines, https://stefan-grafberger.com/mlinspect-journal.pdf

*  Blue Elephants Inspecting Pandas, https://db.in.tum.de/~schuele/data/mlinspect.pdf?lang=en

*  DuckDB: an Embeddable Analytical Database, https://duckdb.org/pdf/SIGMOD2019-demo-duckdb.pdf

*  Data Management for Data Science Towards Embedded Analytics, https://duckdb.org/pdf/CIDR2020-raasveldt-muehleisen-duckdb.pdf

*  Efficient Data Management and Statistics with Zero-Copy Integration, https://dl.acm.org/doi/pdf/10.1145/2618243.2618265


##### Potential public datasets to explore
* [See example pipelines from ArgusEyes](https://github.com/schelterlabs/arguseyes/tree/master/arguseyes/example_pipelines)
* [See example pipelines from mlinspect](https://github.com/stefan-grafberger/mlinspect/tree/master/example_pipelines)
* [See example pipelines from mlwhatif](https://github.com/stefan-grafberger/mlwhatif/blob/main/experiments/end_to_end)



 

 ## Work Environment

 

 The thesis will be supervised by [Stefan Grafberger](https://stefan-grafberger.com/), and the student will join the [AI for Retail Lab](https://icai.ai/airlab/), which is a joint research effort between the [Information Retrieval Lab](https://irlab.science.uva.nl/) and the [Intelligent Data Engineering Lab](https://indelab.org) at the UvA.  Our lab includes several PhD students and research engineers with a varied set of interests and expertise revolving around applied machine learning and scalable data management.

 

 ## Expectations

 

This is an ambitious project for a **self-motivated student capable of critical thinking** and willing to take on a research-heavy thesis. The student is expected to develop a written structured work plan, and discuss updates in regular meetings with the supervisor. 



It is strongly encouraged to publish the resulting analysis and software under an open source license. Furthermore, the thesis may result in a publication at a high-quality data engineering or ML conference, which has often happened in the past for student projects supervised within our group.



Required technical skills:

 * Basic understanding of data engineering and machine learning

 * Experience with Python, pandas and git

 * Strong programming skills for working with a complex existing code base



Optional technical skills (can be acquired during the project):

 * Understanding of common data quality issues and data cleaning techniques

 * Ability to work with relational databases





 ## Research Tags

 data preparation for machine learning; data-centric AI; 

 

 

