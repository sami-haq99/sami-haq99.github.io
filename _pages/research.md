---
layout: archive
title: ""
permalink: /research/
author_profile: true
---
*This is not an exhaustive list of my research projects. In this page, I have tried to highlight some of the interesting projects that I have worked on in the past few years.*
# **1. Neural Machine Translation**
At FJWU NLP Lab, I am working on building end-to-end context-aware Neural Machine Translator. I have worked on different NMT toolkits, mainly I implemented my research using FairSeq. The main challenge was to deal with low availability of parallel document-level data which is primary requirement for building context-aware NMT, we use techniques like Domain Adoptation, Transfer Learning and Back-translation to deal with this. We also utilized pre-trained models to like BERT, EMLO and GLOVE in different investigations for performance improvements.
The modified architectue of Transformer model is shown below which incorporates additional encoder model for context-aware NMT.

<img src="/images/DLNMT.png" width="400">

| Year | Paper Title | Venue | PDF |
|-------|--------|---------|---------|
| 2020 |  Improving document-level neural machine translation with domain adaptation | WNGT | [PDF](https://aclanthology.org/2020.ngt-1.27/) |

# **2. Deep Learning for Text Analysis**
Natural Language Process for text analysis, classification and sentiment analysis is also part of my work. I have worked on projects that include text pre-processing (required for variety of different tasks), text visualization (tren analysis, exploratory data analysis) and text classification (using Machine Learning & Deep Learning) techniques. 
# **3. MODAIS**
In my master’ thesis research work, I examined the use of model driven software engineering for design and analysis of physical security systems. In my research, I developed a framework to support the modeling of physical infrastructures in the form of a platform independent model using Unified Modeling Language (UML). Furthermore, the transformation engine was developed to generate quantitative models based on Bayesian Network from UML models to perform validation. 

<img src="/images/MODAIS.png" width="400">

The faramework supports rich modeling concepts for physical infrastructure security with extension of UML.

<img src="/images/AtackUseCase.png" width="400"> 


A real-world casestudy was implemented to evaluate the framework.

<img src="/images/CaseStudy.png" width="400">

| Year | Paper Title | Venue | PDF |
|-------|--------|---------|---------|
| 2017 | A Novel Approach for Modeling Security Aspects of Physical Infrastructures | HPC3 | [PDF](https://dl.acm.org/doi/abs/10.1145/3069593.3069612) |

# **4. Reverse Engineering UML (Static and Dynamic) Models from Java Source Code**
We proposed a novel MDRE framework named as ‘‘Source to Model Framework (Src2MoF)’’ to generate Unified Modeling Language (UML) structural (class) and behavioral (activity) diagrams from the Java source code. Src2MoF is based on the principles of Model Driven Engineering (MDE), which use models as first-class citizens alleviating the complexity of software systems.

<img src="/images/javatouml.JPG" width="450">

Transformation rules were defined to transform the code units of java source code to UML structures.

<img src="/images/javatoactivity.JPG" width="450">

More information can be found at given link below.

| Year | Paper Title | Venue | PDF |
|-------|--------|---------|---------|
| 2019 | A model driven reverse engineering framework for generating high level UML models from Java source code | IEEE Access | [PDF](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8890645) |
