## Name

Automatic Data Quality Validation for Hugging Face Datasets


## Description

Lots of effort is being spent on designing powerful ML models in the last decades. Besides an elaborate model architecture, high quality training data is becoming more crucial for modern ML-powered applications. In recent years, more and more problems with data quality are uncovered, such as label errors in commmon ML benchmark datasets ( https://labelerrors.com ), reproducibility issues due to data leakage https://reproducible.cs.princeton.edu/ or discriminatory contents in image data ( https://arxiv.org/pdf/2110.01963.pdf ). A large portion of the commonly used training datasets for recent ML models is available on platforms like huggingface ( https://huggingface.co/datasets ), but it is unclear what quality these have. For example, recent findings such as the debunking of the hyped "gzip+knn" appear indicate that the surprising results are at least partially caused by data leakage ( https://kenschutte.com/gzip-knn-paper2/ ).

The thesis undertakes a first step in shining light on this problem by focusing on the following **research questions**:

 * What fraction of datasets on Huggingface suffers from data quality problems like data leakage, label errors or distribution shift?
 * Can we design automated cleaning methods to detect, quantify and mitigate these issues?

The first research question should be addressed with an experimental study leveraging a suitable subset of datasets from huggingface and common data quality validation techniques and libraries. The second research question is more open and requires the student to research and develop appropriate cleaning techniques as well as their evaluation. 

The following literature is helpful to further understand the topic
 *  Special Issue on Data Validation for Machine Learning Models and Applications, IEEE Data Engineering Bulletin - http://sites.computer.org/debull/A21mar/issue1.htm
 * The Data Linter: Lightweight Automated Sanity Checking for ML Data Sets, MLSystems workshop at NeurIPS'17 - https://research.google/pubs/pub47352/
 * Data Validation for Machine Learning, MLSys'19 - https://research.google/pubs/pub47967/
 * Pervasive Label Errors in Test Sets Destabilize Machine Learning Benchmarks, NeurIPS'21 - https://arxiv.org/abs/2103.14749
 * Failing Loudly: An Empirical Study of Methods for Detecting Dataset Shift, NeurIPS'19 - https://proceedings.neurips.cc/paper_files/paper/2019/hash/846c260d715e5b854ffad5f70a516c88-Abstract.html
 * "Gzip beats BERT?" Part 2: dataset issues, improved speed, and results - https://kenschutte.com/gzip-knn-paper2/

 ## Work Environment
 
 The thesis will be supervised by [dr. Sebastian Schelter](https://ssc.io) and [Zeyu Zhang](http://linkedin.com/in/zeyu-zhang-8b2416204) from the [Intelligent Data Engineering Lab](https://indelab.org) at the UvA.  Our lab includes several PhD students and research engineers with a varied set of interests and expertise revolving around applied machine learning and scalable data management.
 
 ## Expectations
 
This is an ambitious project for a **self-motivated student capable of critical thinking** and willing to take on a research-heavy and engineering-heavy thesis. The student is expected to develop a written structured work plan, and discuss updates in regular meetings with the supervisor. 

It is strongly encouraged to publish the resulting analysis and software under an open source license. Furthermore, the thesis may result in a publication at a high-quality ML or data management conference, which has often happened in the past for student projects supervised within our group.

Required technical skills:
 * Strong programming skills for working with a variety of potentially dirty datasets
 * Experience with Python, pandas and git 
 * Basic understanding of machine learning and NLP

Optional technical skills (can be acquired during the project):
 * Understanding of common data quality issues and data cleaning techniques
 

 ## Research Tags
data quality; data cleaning; data-centric AI;
