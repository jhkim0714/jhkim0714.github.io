---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
<div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
  
{% endif %}

<h2 class="page__content-title2" itemprop="headline">
  Peer-Reviewed Articles
</h2>

<div class="wordwrap"><sup>1</sup> denotes that authors contributed equally to the work.</div>

{% include base_path %}

{% for post in site.publications reversed %}
    {% include archive-single.html %}
{% endfor %}


<h2 class="page__content-title2" itemprop="headline">
  Book Chapters
</h2>

<h2 class="page__content" itemprop="headline">
  Exploring the Hidden Realms: New Frontiers for Raman Spectroscopy in Life Sciences
</h2>
<p class="page__item-excerpt" itemprop="description">
<b><ins>Jeong Hee Kim</ins></b>, Swati Tanwar, Zhenhui Liu, Ishan Barman
</p>
<p class="page__title2">
Published in <i>Raman Spectroscopy in Human Health and Biomedicine</i>, 2024 | DOI: <a href=" https://doi.org/10.1142/9789811264610_0013 "> https://doi.org/10.1142/9789811264610_0013 </a>
</p>

<h2 class="page__content-title2" itemprop="headline">
  Patents
</h2>

<h2 class="page__content" itemprop="headline">
Improved Raman Spectroscopy with the Addition of Aromatic Compounds
</h2>
<p class="page__item-excerpt" itemprop="description">
Ethan Yang, <b><ins>Jeong Hee Kim</ins></b>, Kristine Glunde, Ishan Barman, Caitlin Tressler 
</p>
<p class="page__title2">
<a href="https://patentscope.wipo.int/search/en/detail.jsf?docId=WO2023205279&_cid=P20-LOC0BH-06873-46"> PCT/US2023/019161</a>, 2023
</p>
    
