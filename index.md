---
layout: default
title:The Security and Privacy in 5G and 6G networks: new areas and new challenges
---
### The Security and Privacy in 5G and 6G networks

The 5G network is under the deploying progress. However, the limitations of the 5G network are gradually being exposed. These limitations drive research on the 6G network. In order to meet the demands of the future internet, the 6G network needs to emerge from the traditional network architecture. Although there is already some research about the 6G network, the fundamental security and privacy problem of the 6G network still need further discussion. In this paper, we first review the previous network to find the trend of the 6G network. Then, we identify four key areas in the 6G network, then present some promising key technologies which may be used in the 6G network and the security and privacy issues inside theses technology. The applications of the 6G network are shown in the following. The intention of this article is to survey the new areas with their security and privacy challenges in the 6G network. This can lay the foundation for future security and privacy research in the 6G network.

<!--This website and the accompanying [article](https://arxiv.org/abs/1709.06182) surveys the work in this emerging area.-->

<!--Like writing and speaking, software development is an act of human communication.
At its core,
the naturalness of software employs statistical modeling over big code to
reason about rich variety of programs developers write.  This new line of
research is inherently interdisciplinary, uniting the machine learning and
natural language processing communities with software engineering
and programming language communities.
-->
#### Browse Papers by Tag
{% assign rawtags = Array.new %}
{% for publication in site.publications %}
  {% assign ttags = publication.tags  %}  
  {% assign rawtags = rawtags | concat: ttags %}  
{% endfor %}
{% assign rawtags = rawtags | uniq | sort %}
{% for tag in rawtags %}<tag><a href="/tags.html#{{ tag }}">{{ tag }}</a></tag> {% endfor %}

### About This Site

<!--This site is an experiment: a [living literature review](https://en.wikipedia.org/wiki/Living_review) that allows
you explore, [search and navigate]({% link papers.html %}) the literature in this area, by
following a [taxonomy]({% link base-taxonomy/index.md %})
based on the underlying design principles of each model.
The full survey is available [as a research paper](https://arxiv.org/abs/1709.06182).
Please cite as
<pre>
@article{allamanis2018survey,
  title={A survey of machine learning for big code and naturalness},
  author={Allamanis, Miltiadis and Barr, Earl T and Devanbu, Premkumar and Sutton, Charles},
  journal={ACM Computing Surveys (CSUR)},
  volume={51},
  number={4},
  pages={81},
  year={2018},
  publisher={ACM}
}
</pre>
-->
### Contributing
1. The security and privacy issues in the key ares of the 6G network are surveyed and presented.
2. The promising key technologies of the 6G network have been presented, and security and privacy issues which are related to these technologies are detailed.
3. We presented an overview new security and privacy issues in the 6G network. 
<!--This research area is evolving so fast that a static review cannot keep up.
But a website can! We hope to make this site a living document.
Anyone can add a paper to this web site, essentially by creating one Markdown file.
 To contribute, open a pull request in GitHub, by following [these instructions 
for contributing](contributing.html).-->
