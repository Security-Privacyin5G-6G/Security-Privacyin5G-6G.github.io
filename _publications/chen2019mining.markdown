---
layout: publication
title: "Mining Likely Analogical APIs across Third-Party Libraries via Large-Scale Unsupervised API Semantics Embedding"
authors:  C. Chen ; Z. Xing ; Y. Liu, K. L. Xiong Ong 
conference: TSE
year: 2019
bibkey: chen2019mining
tags: ["API", "representation"]
---
Establishing API mappings between third-party libraries is a prerequisite step for library migration tasks. Manually establishing API mappings is tedious due to the large number of APIs to be examined. Having an automatic technique to create a database of likely API mappings can significantly ease the task. Unfortunately, existing techniques either adopt supervised learning mechanism that requires already-ported or functionality similar applications across major programming languages or platforms, which are difficult to come by for an arbitrary pair of third-party libraries, or cannot deal with lexical gap in the API descriptions of different libraries. To overcome these limitations, we present an unsupervised deep learning based approach to embed both API usage semantics and API description (name and document) semantics into vector space for inferring likely analogical API mappings between libraries. Based on deep learning models trained using tens of millions of API call sequences, method names and comments of 2.8 millions of methods from 135,127 GitHub projects, our approach significantly outperforms other deep learning or traditional information retrieval (IR) methods for inferring likely analogical APIs. We implement a proof-of-concept website which can recommend analogical APIs for 583,501 APIs of 111 pairs of analogical Java libraries with diverse functionalities. This scale of third-party analogical-API database has never been achieved before.