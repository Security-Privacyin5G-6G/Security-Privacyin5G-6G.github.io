---
layout: publication
title: "Learning Python Code Suggestion with a Sparse Pointer Network"
authors: A. Bhoopchand, T. Rocktäschel, E.T. Barr, S. Riedel
conference: ArXiV 1611.08307
year: 2016
bibkey: bhoopchand2016learning
additional_links:
   - {name: "ArXiV", url: "https://arxiv.org/pdf/1611.08307.pdf"}
tags: ["language model", "autocomplete"]
---
To enhance developer productivity, all modern integrated development environments (IDEs) include code suggestion functionality that proposes likely next tokens at the cursor. While current IDEs work well for statically-typed languages, their reliance on type annotations means that they do not provide the same level of support for dynamic programming languages as for statically-typed languages. Moreover, suggestion engines in modern IDEs do not propose expressions or multi-statement idiomatic code. Recent work has shown that language models can improve code suggestion systems by learning from software repositories. This paper introduces a neural language model with a sparse pointer network aimed at capturing very long-range dependencies. We release a large-scale code suggestion corpus of 41M lines of Python code crawled from GitHub. On this corpus, we found standard neural language models to perform well at suggesting local phenomena, but struggle to refer to identifiers that are introduced many tokens in the past. By augmenting a neural language model with a pointer network specialized in referring to predefined classes of identifiers, we obtain a much lower perplexity and a 5 percentage points increase in accuracy for code suggestion compared to an LSTM baseline. In fact, this increase in code suggestion accuracy is due to a 13 times more accurate prediction of identifiers. Furthermore, a qualitative analysis shows this model indeed captures interesting long-range dependencies, like referring to a class member defined over 60 tokens in the past. 
