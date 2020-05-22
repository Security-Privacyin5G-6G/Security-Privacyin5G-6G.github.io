---
layout: publication
title: "On Learning Meaningful Code Changes via Neural Machine Translation"
authors: M. Tufano, C. Watson, G. Bavota, M. Di Penta, M. White, D. Poshyvanyk
conference: ICSE
year: 2019
bibkey: tufano2019learning
tags: ["repair", "edit"]
---
Recent years have seen the rise of Deep Learning (DL) techniques applied to source code. Researchers have exploited DL to automate several development and maintenance tasks, such as writing commit messages, generating comments and detecting vulnerabilities among others. One of the long lasting dreams of applying DL to code is the possibility to automate non-trivial coding activities. While some steps in this direction have been taken (e.g., learning how to fix bugs), there is still a lack of empirical evidence on the types of code changes that can be learned and automatically applied by DL. Our goal is to make this first step by quantitatively and qualitatively investigating the ability of a Neural Machine Translation (NMT) model to learn how to automatically apply code changes implemented by developers during pull requests. We train and experiment with the NMT model on a set of 236k pairs of code components before and after the implementation of the changes provided in the pull requests. We show that, when applied in a narrow enough context (i.e., small/medium-sized pairs of methods before/after the pull request changes), NMT can automatically replicate the changes implemented by developers during pull requests in up to 36% of the cases. Moreover, our qualitative analysis shows that the model is capable of learning and replicating a wide variety of meaningful code changes, especially refactorings and bug-fixing activities. Our results pave the way to novel research in the area of DL on code, such as the automatic learning and applications of refactoring.
