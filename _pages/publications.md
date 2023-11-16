---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

## Conferences
- [ICNC 2023] - Michael Cash, Christopher Morales-Gonzalez, Shan Wang, Xipeng Jin, Alex Parlato, Jason Zhu, Qun Zhou Sun, Xinwen Fu, "On False Data Injection Attack against Building Automation Systems", in Proceedings of International Conference on Computing, Networking and Communications (ICNC), Honolulu, Hawaii, USA, February 20-22, 2023.

- [CNS 2022] - Shan Wang, Ming Yang, Bryan Pearson, Tingjian Ge, Xinwen Fu, Wei Zhao. "On Security of Proof-of-Policy (PoP) in the Execute-Order-Validate Blockchain Paradigm", in Proceedings of IEEE Conference on Communications and Network Security (CNS), 3–5 October 2022 // Austin, TX, USA // Hybrid: In-Person and Virtual Conference. [43 out of 122]

- [ICDCS 2022] - Shan Wang, Zhen Ling, Yue Zhang, Ruizhao Liu, Joshua Kraunelisk, Kang Jia, Bryan Pearson, Xinwen Fu. "Implication of Animation on Android Security", in Proceedings of 42st IEEE International Conference on Distributed Computing Systems (ICDCS), July 10 - July 13, 2022 // Bologna, Italy. [CCF-B][AR 19.9%, 114 out of 573]

- [ICC 2022] - Shan Wang, Ming Yang, Tingjian Ge, Yan Luo, Xinwen Fu, BBS: A Blockchain Big-Data Sharing System, in Proceedings of IEEE International Conference on Communications (ICC), 16–20 May 2022 // Seoul, South Korea // Hybrid: In-Person and Virtual Conferenc. [CCF-C]

- [ICDCS 2021] - Shan Wang, Ming Yang, Yue Zhang, Yan Luo, Tingjian Ge, Xinwen Fu, Wei Zhao. "On Private Data Collection of Hyperledger Fabric", in Proceedings of 41st IEEE International Conference on Distributed Computing Systems (ICDCS), July 7 - July 10, 2021.[CCF-B][AR 19.8%, 97 out of 489]

- [ICC 2021] - Michael Cash, Shan Wang, Bryan Pearson, Qun Zhou, Xinwen Fu, On Automating BACnet Device Discovery and Property Identification, in Proceedings of IEEE International Conference on Communications (ICC), 14-23 June 2021 // Virtual / Montreal. DOI: 10.1109/ICC42927.2021.9500413. [CCF-C]

## Journals
- [CCPE 2017] - Ming Yang, Shan Wang, Zhen Ling, Yaowen Liu, and Zhenyu Ni. "Detection of malicious behavior in android apps through API calls and permission uses analysis." Concurrency and Computation: Practice and Experience 29, no. 19 (2017): e4172. [CCF-C]

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
