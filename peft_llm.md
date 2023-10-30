## Name
Unveiling the Secrets of Parameter-Efficient Tuning for Large Language Models (LLMs) Across Tasks

## DescriptionLarge Language Models (LLMs), serving as universal knowledge banks, have demonstrated immense potential in solving tasks across various fields. Owing to their extensive parameter volume, there has been a shift in how to adapt the model to specific tasks, as opposed to the traditional approach of fine-tuning the entire model. One emerging solution is prompt engineering [1], aimed at helping the model better understand the task to deliver decent performance. 

Nonetheless, prompt engineering also encounters challenges such as considerable human effort requirement and complexity of automation [1]. To address these issues, researchers have developed diverse strategies aimed at striking a balance. These methods eliminate the need for resource extensive finetuning while also automating the process of guiding model to understand intended task. Two primary branches have emerged in this realm: one focuses on learning additional adaptors to align the model with downstream datasets, exemplified by approaches like LoRA [2]; the other explores the acquisition of soft prompts that can be prepended to the original input, with Prompt tuning [3] serving as a prime example. These strategies collectively fall under the umbrella of Parameter-Efficient Tuning (PEFT [4]) methods.

Despite the promising developments, these methods are typically tailored to specific tasks, and a comprehensive empirical examination of their effectiveness across various tasks under standardized conditions remains lacking. In light of this, we propose a research project to compare different parameter-efficient tuning methods across a range of tasks. These tasks may encompass data-centric challenges as well as natural language understanding tasks. The objective is to provide valuable insights into the suitability and efficacy of these methods for diverse applications. 

The thesis undertakes a first step in shining light on this problem by focusing on the following **research questions**:
 * Is there a parameter-efficient tuning (PEFT) method that can consistently excel across all tasks?
 * Can we distill fundamental insights to guide the design of PEFT methods tailored to specific tasks?

The following literature is helpful to further understand the topic
 * [1] Pre-train, Prompt, and Predict: A Systematic Survey of Prompting Methods in Natural Language Processing [link](https://dl.acm.org/doi/full/10.1145/3560815)
 * [2] LoRA: Low-Rank Adaptation of Large Language Models [link](https://arxiv.org/abs/2106.09685)
 * [3] The Power of Scale for Parameter-Efficient Prompt Tuning [link](https://arxiv.org/abs/2104.08691)
 
 * [4] PEFT library [link](https://huggingface.co/docs/peft/index)
 

 ## Work Environment
The thesis will be supervised by a PhD student [Zeyu Zhang](https://www.linkedin.com/in/zeyu-zhang-8b2416204/) from the [Intelligent Data Engineering Lab](https://indelab.org) at the UvA.  Our lab includes several PhD students and research engineers with a varied set of interests and expertise revolving around applied machine learning and scalable data management.
 
 ## Expectations
 
This is an ambitious project for a **self-motivated student capable of critical thinking** and willing to take on a research-heavy thesis. The student is expected to develop a written structured work plan, and discuss updates in regular meetings with the supervisor. 

It is strongly encouraged to publish the resulting analysis and software under an open source license. Furthermore, the thesis may result in a publication at a high-quality ML or data management conference, which has often happened in the past for student projects supervised within our group.

Required technical skills:
 * Basic understanding of machine learning and NLP
 * Experience with Python, pandas and git
 * Strong programming skills

Optional technical skills (can be acquired during the project):

 * Basic understanding of models structures and learning objectives for nowadays LLMs
 

 ## Research TagsLarge Language Model, Natural Language Understanding, Parameter-Efficient Tuning. 
 
 
