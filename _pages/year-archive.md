---
layout: archive
permalink: /year-archive/
title: "News"
author_profile: true
redirect_from:
  - /wordpress/blog-posts/
---

{% include base_path %}

News
======
* **26.11.2021:** Our Abstract, "Generalized Primal-dual Feedback-optimizing Control with Direct Constraint Control" is accepted in [The 23rd Nordic Process Control Workshop](https://www.ltu.se/research/subjects/control/NPCW-konferens?l=en), and will be presented on 13rd of January 2022 in Luleå, Sweden.


<!--{% include base_path %}
{% capture written_year %}'None'{% endcapture %}
{% for post in site.posts %}
  {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
  {% if year != written_year %}
    <h2 id="{{ year | slugify }}" class="archive__subtitle">{{ year }}</h2>
    {% capture written_year %}{{ year }}{% endcapture %}
  {% endif %}
  {% include archive-single.html %}
{% endfor %}-->
