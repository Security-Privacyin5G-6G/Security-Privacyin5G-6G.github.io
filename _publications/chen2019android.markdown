---
layout: publication
title: "Android HIV: A study of repackaging malware for evading machine-learning detection"
authors: X. Chen, C. Li, D. Wang, S. Wen, J. Zhang
conference: IEEE Communications Magazine
year: 2019
bibkey: chen2019android
additional_links:
   - {name: "IEEE Link", url: "https://ieeexplore.ieee.org/abstract/document/8782574/"}
   - {name: "Arxiv", url: "https://arxiv.org/pdf/1808.04218.pdf"}
tags: ["Key Areas", "3D Intercom"]
---
Machine learning-based solutions have been successfully employed for the automatic detection of malware on Android. However, machine learning models lack robustness to adversarial examples, which are crafted by adding carefully chosen perturbations to the normal inputs. So far, the adversarial examples can only deceive detectors that rely on syntactic features (e.g., requested permissions, API calls, etc.), and the perturbations can only be implemented by simply modifying application's manifest. While recent Android malware detectors rely more on semantic features from Dalvik bytecode rather than manifest, existing attacking/defending methods are no longer effective. In this paper, we introduce a new attacking method that generates adversarial examples of Android malware and evades being detected by the current models. To this end, we propose a method of applying optimal perturbations onto Android APK that can successfully deceive the machine learning detectors. We develop an automated tool to generate the adversarial examples without human intervention. In contrast to existing works, the adversarial examples crafted by our method can also deceive recent machine learning-based detectors that rely on semantic features such as control-flow-graph. The perturbations can also be implemented directly onto APK's Dalvik bytecode rather than Android manifest to evade from recent detectors. We demonstrate our attack on two state-of-the-art Android malware detection schemes, MaMaDroid and Drebin. Our results show that the malware detection rates decreased from 96% to 0% in MaMaDroid, and from 97% to 0% in Drebin, with just a small number of codes to be inserted into the APK.