## Name



Data Preparation Pipelines for Machine Learning: A Study of Common Issues and Remediation Techniques



## Description



Research in machine learning is based on a set of static, well-known and widely understood benchmark datasets. In real world ML applications however, the training and evaluation data for the ML model must first be created by a data preparation pipeline. Such a pipeline consumes data from several often heterogeneous data sources (e.g., log files, external APIs, tables in a database), combines and cleans the data, and encodes it into feature vectors afterwards.

Even though such end-to-end pipelines, including both data preparation and model training and evaluation, are required for any large-scale ML application, they are not well understood by the research community, due to its focus on static clean benchmark datasets. Problems can occur in different parts of these end-to-end pipelines and include examples like data leakage, lack of proper train/test/validation splits, missing hyperparameter optimization, missing cross-validation, legal restrictions on sensitive demographic features, neglecting to scale numerical features as required, class imbalance, overfitting, underfitting, robustness issues, technical biases, and data quality concerns.

In this thesis, our primary objective is to systematically analyse scientific literature and other sources, such as Stack Overflow posts and blog articles, to compile a comprehensive understanding of common issues and remediation strategies. Furthermore, we aim to assess the effectiveness of existing tools that aim to help data scientists with helping and identifying pipeline issues. This evaluation may involve conducting user studies, where participants are tasked with identifying and resolving typical problems using specific available tools.

The main goal of this thesis is to create a publicly accessible resource that comprehensively outlines common challenges encountered in machine learning pipelines, lists potential solutions, provides practical demonstrations through example pipelines, and offers an empirical analysis of their characteristics. Optionally, we may explore innovative methods to better support data scientists when they encounter such issues.



The thesis undertakes a first step in shining light on this problem by focusing on the following **research questions**:



 * What are the characteristics of common issues in data preparation pipelines for ML? What kind of issues are common, how do data scientists address them, and how difficult are these issues to discover and fix? Do the characteristics differ based on factors like the type of ML task and the model in use?

 * How helpful are existing tools for data scientists encountering these issues?



The following literature is helpful to further understand the topic

 * Data distribution debugging in machine learning pipelines, VLDBJ 2022, https://stefan-grafberger.com/mlinspect-journal.pdf

 * Automating and Optimizing Data-Centric What-If Analyses on Native Machine Learning Pipelines, SIGMOD 2023, https://stefan-grafberger.com/mlwhatif.pdf

* Proactively Screening Machine Learning Pipelines with ArgusEyes, SIGMOD 2023 (demo), https://ssc.io/publication/proactively-screening-machine-learning-pipelines-with-arguseyes-sigmod/

 * Machine Learning Testing: Survey, Landscapes and Horizons, IEEE Transactions on Software Engineering 2020, https://arxiv.org/pdf/1906.10742.pdf

 * Leakage and the reproducibility crisis in ML-based science, ArXiv 2022, https://arxiv.org/pdf/2207.07048

 * Fairprep: Promoting data to a first-class citizen in studies on fairness-enhancing interventions, EDBT 2020, https://ssc.io/pdf/fairprep.pdf

 * Fairness Testing: A Comprehensive Survey and Analysis of Trends, ArXiv 2023, https://arxiv.org/pdf/2207.10223.pdf

 * An Empirical Study on Real Bugs for Machine Learning Programs, APSEC 2017, https://ieeexplore.ieee.org/document/8305957

 * Data pipeline quality: Influencing factors, root causes of data-related issues, and processing problem areas for developers, Journal of Systems and Software 2024, https://doi.org/10.1016/j.jss.2023.111855

 * Slice Finder: Automated Data Slicing for Model Validation, ICDE 2019, https://research.google/pubs/pub47966/


Exemplary blog posts targeted at ML beginners: 

 * https://www.analyticsvidhya.com/blog/2020/07/10-techniques-to-deal-with-class-imbalance-in-machine-learning/

 * https://pratikroy311.medium.com/overfitting-and-underfitting-balancing-model-complexity-fe45e7cc4bac


 ## Work Environment

 

 The thesis will be supervised by [Stefan Grafberger](https://stefan-grafberger.com/), and the student will join the [AI for Retail Lab](https://icai.ai/airlab/), which is a joint research effort between the [Information Retrieval Lab](https://irlab.science.uva.nl/) and the [Intelligent Data Engineering Lab](https://indelab.org) at the UvA.  Our lab includes several PhD students and research engineers with a varied set of interests and expertise revolving around applied machine learning and scalable data management.

 

 ## Expectations

 

This is an ambitious project for a **self-motivated student capable of critical thinking** and willing to take on a research-heavy thesis. The student is expected to develop a written structured work plan, and discuss updates in regular meetings with the supervisor. 



It is strongly encouraged to publish the resulting analysis and software under an open source license. Furthermore, the thesis may result in a publication at a high-quality data engineering or ML conference, which has often happened in the past for student projects supervised within our group.



Required technical skills:

 * Basic understanding of data engineering and machine learning

 * Experience with Python, pandas and git

 * Strong programming skills for working with a variety of potentially dirty datasets



Optional technical skills (can be acquired during the project):

 * Understanding of common data quality issues and data cleaning techniques

 * Ability to work with relational databases





 ## Research Tags

 data preparation for machine learning; data-centric AI; 

 

 

