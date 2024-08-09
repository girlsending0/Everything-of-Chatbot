# Awesome-of-Chatbot [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) 
> A curated collection of selected technologies for use in chatbots.

## Paper format
```Markdown
**Here is the Paper Name.**<br>
*[Author 1](homepage), Author 2, and Author 3.*<br>
Conference or Journal Year. [[PDF](link)] [[Project](link)] [[Code](link)] [[Data](link)]
- Short description
```

## Table of Contents
- [Prompt engineering](#prompt-engineering)
- [Retrieval Augmented Generation (RAG)](#retrieval-augmented-generation)
- [Parameter Efficient Fine-Tuning (PEFT)](#parameter-efficient-fine-tuning)
- [Agent](#agent)
- [Dataset](#dataset)

## Prompt engineering

**A Survey of Prompt Engineering Methods in Large Language Models for Different NLP Tasks**
*Vatsal, Shubham, Harsh Dubey*
ArXiv, Preprint
[[PDF](https://arxiv.org/pdf/2407.12994)]
- Survey of Prompt engineering techniques
- Analysis of 44 research papers
- Survey of 39 different prompting methods
- Analysis of cases applied to 29 different NLP tasks


## Retrieval Augmented Generation (RAG)

**Searching for Best Practices in Retrieval-Augmented Generation**
*Xiaohua Wang*
ArXiv, Preprint
[[PDF](https://arxiv.org/pdf/2407.01219)]
- Detailed analysis of each RAG overall workflow module
- Present optimal implementation method for each module (search, re-ranking, summarization, etc.)
- RAG performance evaluation results disclosed in various NLP tasks
- Proposal of optimal implementation strategy considering both performance and efficiency
- Exploring possible extensions to multimodal RAG
- Presenting the optimal approach for fine-tuning the generator  


## Agent

**CoD, Towards an Interpretable Medical Agent using Chain of Diagnosis**
*Junying Chen1*
ArXiv, Preprint
[[PDF](https://arxiv.org/pdf/2407.13301)] [[Code](https://github.com/FreedomIntelligence/Chain-of-Diagnosis)] [[Data](https://huggingface.co/datasets/FreedomIntelligence/DxBench)]


## Dataset

**MedTrinity-25M: A Large-scale Multimodal Dataset with Multigranular Annotations for Medicine**
*Yunfei Xie*
ArXiv, Preprint
[[PDF](https://arxiv.org/pdf/2408.02900)]
[[DATA](https://yunfeixie233.github.io/MedTrinity-25M/)]
- This dataset encompasses medical imaging data across 10 modalities, including CT, MRI, X-Ray, histopathology, and microscopy, covering over 65 different diseases.
- An automated pipeline utilizing MLLMs has been applied to generate rich multigranular annotations, resulting in an image-ROI-description triplet format.


**Test of Time: A Benchmark for Evaluating LLMs on Temporal Reasoning**
*Bahare Fatemi*
ArXiv, Preprint
[[PDF](https://arxiv.org/pdf/2406.09170)]
[[DATA](https://huggingface.co/datasets/baharef/ToT)]
- This paper introduces Google's LLM synthetic benchmark for temporal reasoning, Test of Time (ToT).
- It addresses the issue with existing temporal reasoning benchmarks, which are based on knowledge graphs of entities that models are already familiar with, allowing models to rely on prior knowledge rather than performing genuine temporal reasoning.
- The paper identifies two crucial components of temporal reasoning: (1) the ability to understand the semantics and logic of time, and (2) the ability to perform temporal arithmetic. Based on these insights, the benchmark is divided into ToT-Semantic and ToT-Arithmetic.

## Medical LLM

**Adapting Open-Source Large Language Models for Cost-Effective, Expert-Level Clinical Note Generation with On-Policy Reinforcement Learning**
*Hanyin Wang*
ArXiv, Preprint
[[PDF](https://arxiv.org/pdf/2405.00715)]




