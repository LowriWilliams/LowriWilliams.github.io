---
title: "Hardening machine learning denial of service (DoS) defences against adversarial attacks in IoT smart home networks"
authors:
- Eirini Anthi
- Lowri Williams
- Amir Javed
- Pete Burnap


date: "2021-09-01"
doi: "https://www.sciencedirect.com/science/article/pii/S0167404821001760"

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: 'Computers and Security'
publication_short: ""

abstract: Machine learning based Intrusion Detection Systems (IDS) allow flexible and efficient automated detection of cyberattacks in Internet of Things (IoT) networks. However, this has also created an additional attack vector; the machine learning models which support the IDS’s decisions may also be subject to cyberattacks known as Adversarial Machine Learning (AML). In the context of IoT, AML can be used to manipulate data and network traffic that traverse through such devices. These perturbations increase the confusion in the decision boundaries of the machine learning classifier, where malicious network packets are often miss-classified as being benign. Consequently, such errors are bypassed by machine learning based detectors, which increases the potential of significantly delaying attack detection and further consequences such as personal information leakage, damaged hardware, and financial loss. Given the impact that these attacks may have, this paper proposes a rule-based approach towards generating AML attack samples and explores how they can be used to target a range of supervised machine learning classifiers used for detecting Denial of Service attacks in an IoT smart home network. The analysis explores which DoS packet features to perturb and how such adversarial samples can support increasing the robustness of supervised models using adversarial training. The results demonstrated that the performance of all the top performing classifiers were affected, decreasing a maximum of 47.2 percentage points when adversarial samples were present. Their performances improved following adversarial training, demonstrating their robustness towards such attacks.

# Summary. An optional shortened abstract.
summary: 

tags:
- Internet of things
- Smart homes
- Networking
- Supervised machine learning
- Adversarial machine learning
- Attack detection
- Intrusion detection systems
featured: true

# links:
# - icon: arxiv
#   icon_pack: ai
#   name: arXiv:1904.04067
#   url: https://arxiv.org/abs/1904.04067
# - icon: inspire
#   icon_pack: ai
#   name: inspire1728738
#   url: https://inspirehep.net/literature/1728738
# - icon: springer
#   icon_pack: ai
#   name: JHEP 07 (2019) 123
#   url: https://doi.org/10.1007/JHEP07(2019)123
  
---