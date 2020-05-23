---
layout: publication
title: "A Neural Model for Method Name Generation from Functional Description"
authors: S. Gao, C. Chen, Z. Xing, Y. Ma, W. Song, S.W. Lin
conference: SANER
year: 2019
bibkey: gao2019neural
tags: ["naming", "summarization"]
---
The names of software artifacts, e.g., method names, are important for software understanding and maintenance, as good names can help developers easily understand others' code. However, the existing naming guidelines are difficult for developers, especially novices, to come up with meaningful, concise and compact names for the variables, methods, classes and files. With the popularity of open source, an enormous amount of project source code can be accessed, and the exhaustiveness and instability of manually naming methods could now be relieved by automatically learning a naming model from a large code repository. Nevertheless, building a comprehensive naming system is still challenging, due to the gap between natural language functional descriptions and method names. Specifically, there are three challenges: how to model the relationship between the functional descriptions and formal method names, how to handle the explosion of vocabulary when dealing with large repositories, and how to leverage the knowledge learned from large repositories to a specific project. To answer these questions, we propose a neural network to directly generate readable method names from natural language description. The proposed method is built upon the encoder-decoder framework with the attention and copying mechanisms. Our experiments show that our method can generate meaningful and accurate method names and achieve significant improvement over the state-of-the-art baseline models. We also address the cold-start problem using a training trick to utilize big data in GitHub for specific projects.
