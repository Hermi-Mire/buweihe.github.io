---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<h1 style="margin-bottom:0px;padding-top:20px;">2022</h1>

  <li >
  <b>Buwei He</b>, Yuhang Gao, Yi Sun. &ldquo;Colour Coherence Entropy for Ceramic Fragment Analysis.&rdquo; APWeb-WAIM 2022 Workshops. Oral.
  <a href="https://link.springer.com/chapter/10.1007/978-981-99-1354-1_21">[LINK]</a>


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
