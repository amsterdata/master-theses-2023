## Name

Optimised Materialisation for Low-Latency Within-Basket-Recommendation at Scale


## Description

Users of online shopping platforms typically purchase multiple items at a time in the form of a shopping basket. Personalized within-basket recommendation is the task of recommending items to complete an incomplete basket during a shopping session, given the the shopping history of the users.

Our group recently proposed PerNIR, a neighborhood-based recommendation model that explicitly models the personal history of users for within-basket recommendation in grocery shopping. The main novelty of PerNIR is in modeling the short-term interests of users, which are represented by the current basket, as well as their long-term interest, which is reflected in their purchasing history. In addition to the personal history, user neighbors are used to capture the collaborative purchase behavior. PerNIR provides state-of-the-art prediction quality and a simplified variant of the algorithm is deployed in production by our industry partners in several European countries.

However, there exist interesting challenges in scaling PerNIR to use cases with millions of users and items in the recommendation dataset. In particular, PerNIR requires the computation of an item-to-item cooccurrence matrix to capture the collaborative purchase behavior for each user in the training data. In order to achieve low-latency predictions at inference time, it is desirable to materialise these matrices early (precompute them matrices offline). Doing this for all users requires a huge amount of memory however, which makes the algorithm expensive to deploy. As a consequence, we look for intelligent ways to decide when (and when not) to materialise (precompute) these matrices, ideally according to a given memory budget.  

The thesis should tackle this issue in depths by conducting the following steps:
 * Optimised implementation of PerNIR in Rust/C++ based on an existing Python implementation
 * Formalisation of the problem of materialising the cooccurrence matrices to trade-off memory and prediction latency
 * Implementation and evaluation of optimisation algorithm for different datasets and deployment scenarios


The following literature is required to further understand the topic

 * A Personalized Neighborhood-based Model for Within-basket Recommendation in Grocery Shopping, WSDM'22 https://ssc.io/pdf/pernir.pdf  
 * A Next Basket Recommendation Reality Check, ACM TIS'22 https://dl.acm.org/doi/10.1145/3587153
 * Serenade - Low-Latency Session-Based Recommendation in e-Commerce at Scale, SIGMOD'21 https://ssc.io/pdf/modds003.pdf


## Work Environment

The thesis will be supervised by dr. [Sebastian Schelter](https://ssc.io), and the student will join the [AI for Retail Lab](https://icai.ai/airlab/), which is a joint research effort between the [Information Retrieval Lab](https://irlab.science.uva.nl/) and the [Intelligent Data Engineering Lab](https://indelab.org) at the UvA.  Our lab includes several PhD students and research engineers with a varied set of interests and expertise revolving around scalable data management and applied machine learning.

 

## Expectations

This is an ambitious project for a **self-motivated student capable of critical thinking** and willing to take on a research-heavy thesis. The student is expected to develop a written structured work plan, and discuss updates in regular meetings with the supervisor. 

It is strongly encouraged to publish the resulting analysis and software under an open source license. Furthermore, the thesis may result in a publication at a high-quality data engineering conference, which has often happened in the past for student projects supervised within our group.


Required technical skills:

 * Passion and fundamental background knowledge for data engineering
 * Strong programming skills, ideally in Rust or C++ 
 * Basic understanding of machine learning


Optional technical skills (can be acquired during the project):
 * Experience with recommendation algorithms


 ## Research Tags

 scalable recommender systems

 

 
