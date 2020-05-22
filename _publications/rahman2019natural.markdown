---
layout: publication
title: "Natural Software Revisited"
authors: M. Rahman, D. Palani, P. Rigby
conference: ICSE
year: 2019
bibkey: rahman2019natural
---
Recent works have concluded that software is more repetitive and predictable, i.e. more natural, than English texts. These works included “simple/artificial” syntax rules in their language models. When we remove SyntaxTokens we find that code is still repetitive and predictable but only at levels slightly above English. Furthermore, previous works have compared individual Java programs to general English corpora, such as Gutenberg, which contains a historically large range of styles and subjects (e.g. Saint Augustine to Oscar Wilde). We perform an additional comparison of technical StackOverflow English discussions with source code and find that this restricted English is similarly repetitive to code. Although we find that code is less repetitive than previously thought, we suspect that API code element usage will be repetitive across software projects. For example a file is opened and closed in the same manner irrespective of domain. When we restrict our n-grams to those contained in the Java API we find that the entropy is significantly lower than the English corpora. Previous works have focused on sequential sequences of tokens. When we extract program graphs of size 2, 3, and 4 nodes we see that the abstract graph representation is much more concise and repetitive than the sequential representations of the same code. This suggests that future work should focus on statistical graph models that go beyond linear sequences of tokens. Our anonymous replication package makes our scripts and data available to future researchers and reviewers.
