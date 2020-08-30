---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

  * Thermal and power aware task mapping on 3D Network on Chip
    A. Mosayyebzadeh, M. M. Amiraski, S. Hessabi, Computers & Electrical Engineering 51, 157-167
  * Supporting Security Sensitive Tenants in a Bare-Metal Cloud
    A. Mosayyebzadeh et al., USENIX Annual Technical Conference (ATC '19) [paper](https://www.usenix.org/system/files/atc19-mosayyebzadeh.pdf)

  * A secure cloud with minimal provider trust
    A. Mosayyebzadeh et al., 10th {USENIX} Workshop on Hot Topics in Cloud Computing (HotCloud 18) [paper](https://www.usenix.org/system/files/conference/hotcloud18/hotcloud18-paper-mosayyebzadeh.pdf)
  * Caching in the Multiverse
    M. Abdi, A. Mosayyebzadeh, M. H. Hajkazemi, A. Turk, O. Krieger, P. Desnoyers, 11th {USENIX} Workshop on Hot Topics in Storage and File Systems (HotStorage 19) [paper](https://www.usenix.org/system/files/hotstorage19-paper-abdi.pdf)

You can find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

#{% if author.googlescholar %}
#  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
#{% endif %}

#{% include base_path %}

#{% for post in site.publications reversed %}
#  {% include archive-single.html %}
#{% endfor %}
