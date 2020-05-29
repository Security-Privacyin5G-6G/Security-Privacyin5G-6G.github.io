---
layout: publication
title: "Communication-efficient learning of deep networks from decentralized data"
authors: HB. McMahan, E. Moore, D. Ramage
conference: arXiv preprint
year: 2016
bibkey: mcmahan2016communication
additional_links:
   - {name: "Arxiv", url: "https://arxiv.org/abs/1602.05629"}
tags: ["Key Areas", "Distributed Artificial Intelligence"]
---
Modern mobile devices have access to a wealth of data suitable for learning models, which in turn
can greatly improve the user experience on the
device. For example, language models can improve speech recognition and text entry, and image models can automatically select good photos.
However, this rich data is often privacy sensitive,
large in quantity, or both, which may preclude
logging to the data center and training there using
conventional approaches. We advocate an alternative that leaves the training data distributed on
the mobile devices, and learns a shared model by
aggregating locally-computed updates. We term
this decentralized approach Federated Learning.
We present a practical method for the federated
learning of deep networks based on iterative
model averaging, and conduct an extensive empirical evaluation, considering five different model architectures and four datasets. These experiments
demonstrate the approach is robust to the unbalanced and non-IID data distributions that are a
defining characteristic of this setting. Communication costs are the principal constraint, and
we show a reduction in required communication
rounds by 10–100× as compared to synchronized
stochastic gradient descent.