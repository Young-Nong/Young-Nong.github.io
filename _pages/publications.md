---
permalink: /publications/
layout: archive
title: "Publications"
excerpt: "Publications"
author_profile: true
---
{% include base_path %}

**[VulScribeR: Exploring RAG-based Vulnerability Augmentation with LLMs](https://dl.acm.org/doi/abs/10.1145/3760775)** \
Seyed Shayan Daneshvar, **Yu Nong**, Xu Yang, Shaowei Wang, Haipeng Cai. *ACM Transactions on Software Engineering and Methodology, 2025.* \
we propose VulScribeR, a novel LLM-based solution that leverages carefully curated prompt templates to augment vulnerable datasets. We explore three strategies to augment both single and multi-statement vulnerabilities, with LLMs. Our extensive evaluation across four vulnerability datasets and DLVD models show that our approach beats two SOTA methods Vulgen and VGX, and Random Oversampling in generating vulnerable samples.

**[APPATCH: Automated Adaptive Prompting Large Language Models for Real-World Software Vulnerability Patching](https://chapering.github.io/pubs/sec25.pdf)** \
**Yu Nong**, Haoran Yang, Long Cheng, Hongxin Hu, Haipeng Cai. *USENIX Security Symposium (USENIX Security), 2025.* \
We leverage the power and merits of pre-trained language language models (LLMs) to enable automated vulnerability patching using our introduced vulnerability semantics reasoning and adaptive prompting to elicit LLMs to effectively reason about vulnerable code behaviors, which is essential for quality patch generation.

**[Code Speaks Louder: Exploring Security and Privacy Relevant Regional Variations in Mobile Applications](https://www.researchgate.net/profile/Haipeng-Cai/publication/391219288_Code_Speaks_Louder_Exploring_Security_and_Privacy_Relevant_Regional_Variations_in_Mobile_Applications/links/680ef6f4df0e3f544f4bebdd/Code-Speaks-Louder-Exploring-Security-and-Privacy-Relevant-Regional-Variations-in-Mobile-Applications.pdf)** \
Jiawei Guo, **Yu Nong**, Zhiqiang Lin, Haipeng Cai. *IEEE Symposium on Security and Privacy (SP), 2025.* \
We develop FREELENS, a novel framework that overcomes key technical challenges including code obfuscation and analysis scalability to identify and characterize security relevant variations across regions. Our findings reveal that GFDs are widespread, with significant variations in advertising, data handling, and authentication mechanisms. These differences frequently compromise security baselines and introduce disparities in privacy protections across regions, highlighting the urgency for harmonized privacy and security standards.

**[Chain-of-thought prompting of large language models for discovering and fixing software vulnerabilities](https://arxiv.org/pdf/2402.17230)** \
**Yu Nong**, Mohammed Aldeen, Long Cheng, Hongxin Hu, Feng Chen, Haipeng Cai. *Under Review, 2025.* \
We explore how to leverage large lange models and chain-of-thoughts to address three key software vulnerability analysis tasks: identifying a given type of vulnerabilities, discovering vulnerabilities of any type, and patching detected vulnerabilities.

**[VinJ: An Automated Tool for Large-Scale Software Vulnerability Data Generation](https://chapering.github.io/pubs/nong24fsetool.pdf)** \
**Yu Nong**, Haoran Yang, Feng Chen, Haipeng Cai. *ACM Joint Meeting on European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE), 2024.* \
We present VinJ, an efficient automated tool for large-scale diverse vulnerability data generation. VinJ automatically generates vulnerability data by injecting vulnerabilities into given programs, based on knowledge learned from existing vulnerability data.

**[Multi-Language Software Development: Issues, Challenges, and Solutions](https://chapering.github.io/pubs/tse24haoran.pdf)** \
Haoran Yang, **Yu Nong**, Shaowei Wang, Haipeng Cai. *IEEE Transactions on Software Engineering (TSE), 2024.* \
Developing software projects that incorporate multiple languages has been a prevalent practice for many years. In this paper, we provide answers to the issues encountered by developers during the development process, the underlying challenges causing these issues, and the solutions provided to developers. 

**[Learning to Detect and Localize Multilingual Bugs](https://chapering.github.io/pubs/fse24haoran.pdf)** \
Haoran Yang, **Yu Nong**, Tao Zhang, Xiapu Luo, Haipeng Cai. Proceedings of the ACM on Software Engineering (FSE), 2024.* \
Extant static/dynamic analysis and deep learning (DL) based approaches all face major challenges in addressing multilingual bugs which cross different programming languages. In this paper, we present xLoc, a DL-based technique/tool for detecting and localizing multilingual bugs through pre-training and fine-tuning a Transformer model with customized position encoding. 

**[VGX: Large-Scale Sample Generation for Boosting Learning-Based Software Vulnerability Analyses](https://chapering.github.io/pubs/icse24yu.pdf)** \
**Yu Nong**, Richard Fang, Guangbei Yi, Kunsong Zhao, Xiapu Luo, Feng Chen, Haipeng Cai. *IEEE/ACM International Conference on Software Engineering (ICSE), 2024.* 
We propose VGX, a new technique aimed for large-scale generation of high-quality vulnerability datasets. VGX combines semantics-aware contextualization, which identifies the context of vulnerability injection code edits, and human-knowledge-enhanced edit pattern formation, which uses the materialized contextualized code edits, to generate large-scale high-quality vulnerability datasets effectively.

**[VulGen: Realistic Vulnerable Sample Generation via Pattern Mining and Deep Learning](https://www.researchgate.net/publication/368358322_VULGEN_Realistic_Vulnerability_Generation_Via_Pattern_Mining_and_Deep_Learning)** \
**Yu Nong**, Yuzhe Ou, Michael Pradel, Feng Chen, and Haipeng Cai. *IEEE/ACM International Conference on Software Engineering (ICSE), 2023.* \
We present VulGen, the first injection-based vulnerability-generation technique that is not limited to a particular class of vulnerabilities. It combines the
strengths of deterministic (pattern-based) and probabilistic (deep-learning/DL-based) program transformation approaches while mutually overcoming respective weaknesses.

**[Open Science in Software Engineering: A Study on Deep Learning-Based Vulnerability Detection](https://www.researchgate.net/publication/363535723_Open_Science_in_Software_Engineering_A_Study_on_Deep_Learning-Based_Vulnerability_Detection)** \
**Yu Nong**, Rainy Sharma, Abdelwahab Hamou-Lhadj, Xiapu Luo, Haipeng Cai. *IEEE Transactions on Software Engineering (TSE) 2022.* \
An empirical study that exhaustively searches the literature in the area of deep learning-based vulnerability detection and comprehensively investigates the four integral aspects of open science: availability, executability, reproducibility, and replicability.


**[Generating Realistic Vulnerabilities via Neural Code Editing: An Empirical Study](https://www.researchgate.net/publication/361835991_Generating_Realistic_Vulnerabilities_via_Neural_Code_Editing_An_Empirical_Study)** \
**Yu Nong**, Yuzhe Ou, Michael Pradel, Feng Chen, Haipeng Cai. *ACM Joint Meeting on European Software Engineering Conference and Symposium on the Foundations of Software Engineering (ESEC/FSE), 2022* \
A study that explores the feasibility of vulnerability injection through neural code editing. With a synthetic dataset and a real-world one, we investigate the potential and gaps of three state-of-the-art neural code editors for vulnerability injection.

**[Evaluating and comparing memory error vulnerability detectors](https://www.researchgate.net/publication/351374599_Evaluating_and_comparing_memory_error_vulnerability_detectors)** \
**Yu Nong**, Haipeng Cai, Pengfei Ye, Li Li, Feng Chen. *Information and Software Technology (IST), 137, 106614. 2021* \
An empirical study that evaluates and compares state-of-the-art memory error vulnerability detectors against publicly available benchmark datasets of C/C++ programs, with case studies to gain in-depth explanations of successes and failures of individual tools.

**[A Preliminary Study on Open-Source Memory Vulnerability Detectors](https://www.researchgate.net/publication/340402566_A_Preliminary_Study_on_Open-Source_Memory_Vulnerability_Detectors)** \
**Yu Nong**, Haipeng Cai. *IEEE 27th International Conference on Software Analysis, Evolution and Reengineering (SANER) (pp. 557-561). 2020* \
Preliminary results of a study on memory vulnerability detectors based on (static and/or dynamic) program analysis, against a public suite of 520 C/C++ programs as benchmarks which cover 14 different vulnerability categories.
