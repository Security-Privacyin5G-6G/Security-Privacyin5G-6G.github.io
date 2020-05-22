---
layout: publication
title: "SmartPaste: Learning to Adapt Source Code"
authors: M. Allamanis, M. Brockscmidt
conference: ""
year: 2017
bibkey: allamanis2017smartpaste
additional_links:
   - {name: "ArXiV", url: "https://arxiv.org/abs/1705.07867"}
tags: ["representation", "variable misuse"]
---
Deep Neural Networks have been shown to succeed at a range of natural
language tasks such as machine translation and text summarization.
While tasks on source code (ie, formal languages) have been considered
recently, most work in this area does not attempt to capitalize on the
unique opportunities offered by its known syntax and structure. In this
work, we introduce SmartPaste, a first task that requires to use such
information. The task is a variant of the program repair problem that
requires to adapt a given (pasted) snippet of code to surrounding,
existing source code. As first solutions, we design a set of deep
neural models that learn to represent the context of each variable
location and variable usage in a data flow-sensitive way. Our
evaluation suggests that our models can learn to solve the SmartPaste
task in many cases, achieving 58.6% accuracy, while learning meaningful
representation of variable usages. 
