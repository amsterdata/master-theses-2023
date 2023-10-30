## Name

Assessing the Fairness and Bias of Entity Matching with Multimodal Data

## Description

Entity matching (EM) is a data integration task with the goal of identifying whether two records from the same or different data sources refer to the same real-world entity. EM is useful in various domains, such as e-commerce (e.g., do two different product names refer to the same real world product?) and healthcare (e.g. do two patient records from different hospitals refer to the same person?). Unfortunately, some recent work has shown that popular methods for automated data cleaning and EM in particular may have undesired consequences with regard to biased outcomes for people impacted by machine learning systems. The goal of this thesis is to uncover and potentially mitigate such bias when applying EM to multimodal datasets, e.g. image data such as CelebA and text data such as Wikipedia.

<!-- - EM frameworks abstract
    
    > Entity matching is a crucial and difficult task for data integration. Entity matching frameworks provide several methods and their combination to effectively solve different match tasks. In this paper, we comparatively analyze 11 proposed frameworks for entity matching. Our study considers both frameworks which do or do not utilize training data to semi-automatically find an entity matching strategy to solve a given match task. Moreover, we consider support for blocking and the combination of different match algorithms. We further study how the different frameworks have been evaluated. The study aims at exploring the current state of the art in research prototypes of entity matching frameworks and their evaluations. The proposed criteria should be helpful to identify promising framework approaches and enable categorizing and comparatively assessing additional entity matching frameworks and their evaluations. -->

<!-- - Fair EM intro
    
    > Entity matching (EM) seeks to match pairs of entity records from (the same or different) data sources that refer to the same real-world entity. EM is very useful in many applications domains, including (a) healthcare, where matching of patient records from different healthcare facilities (e.g., emergency rooms, hospitals, etc.) can be used to determine if they refer to the same real-world person; (b) airline security, where airline passenger records are matched against no-fly list records to identify people who should be prevented from boarding flights or should undergo additional screening; (c) e-commerce, where product records from different retailers’ websites can be matched to identify popular products and fraudulent knockoffs; and so on. -->

<!-- - Example proposal from Sebastian:
    
    > Large Language Models (LLMs) to generate natural language such as GPT-3 belong to the most astonishing and promising technological advances of the recent years. Currently, their potential to improve upon long-standing difficult tasks in various academic fields is explored by many researchers. One exciting such direction is to understand the potential of LLMs for data cleaning for tabular data. Data cleaning consists of various tasks, such as error detection (e.g., is the value in the 'country' column correct, given the value in the 'city' and 'street' columns?), deduplication (e.g., do two different product names refer to the same real world product?) or data imputation (e.g., what is the correct value for an empty 'country' attribute, given a 'city' value)? Unfortunately, language models have also been shown to contain reproduce existing bias in the language data on which they are trained. The goal of this thesis is to uncover and potentially mitigate such bias when applying LLMs for data cleaning tasks. -->

The thesis undertakes a first step in shining light on this problem by focusing on the following **research questions**:

- Can we uncover bias and unfairness issues when using EM on multimodal data? E.g., do they work less well for EM tasks involving images of people with darker skin or text with non-Western names and terms?
- Can we find ways to mitigate such bias, e.g., with data augmentation?

The following literature is helpful to further understand the topic:

- Frameworks for entity matching: A comparison, DKE 2010, [https://www.sciencedirect.com/science/article/pii/S0169023X09001451](https://www.sciencedirect.com/science/article/pii/S0169023X09001451?via%3Dihub)
- Responsible Data Management, CACM 2022, [https://dl.acm.org/doi/pdf/10.1145/3488717](https://dl.acm.org/doi/pdf/10.1145/3488717)
- Automated Data Cleaning Can Hurt Fairness in Machine Learning-based Decision Making, ICDE 2023, [https://ieeexplore.ieee.org/document/10184590](https://ieeexplore.ieee.org/document/10184590)
- Through the Fairness Lens: Experimental Analysis and Evaluation of Entity Matching, VLDB 2023, [https://arxiv.org/pdf/2307.02726.pdf](https://arxiv.org/pdf/2307.02726.pdf)

## Work Environment

The thesis will be supervised by [dr. Sebastian Schelter](https://ssc.io/), and the student will join the [AI for Retail Lab](https://icai.ai/airlab/), which is a joint research effort between the [Information Retrieval Lab](https://irlab.science.uva.nl/) and the [Intelligent Data Engineering Lab](https://indelab.org/) at the UvA.  Our lab includes several PhD students and research engineers with a varied set of interests and expertise revolving around applied machine learning and scalable data management.

## Expectations

This is an ambitious project for a **self-motivated student capable of critical thinking** and willing to take on a research-heavy thesis. The student is expected to develop a written structured work plan, and discuss updates in regular meetings with the supervisor.

It is strongly encouraged to publish the resulting analysis and software under an open source license. Furthermore, the thesis may result in a publication at a high-quality ML or data management conference, which has often happened in the past for student projects supervised within our group.

Required technical skills:

- Basic understanding of machine learning
- Experience with Python, pandas and git
- Strong programming skills for working with a variety of potentially dirty datasets

Optional technical skills (can be acquired during the project):

- Understanding of various notions of fairness for automated decision making
- Understanding of common data quality issues and data cleaning techniques

## Research Tags

fairness in machine learning; responsible data science; data-centric AI; automated decision making; data quality; data cleaning
