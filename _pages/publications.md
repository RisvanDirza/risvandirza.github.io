---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

Journal Publications
======
[J1] Gusrialdi, A., <bold>Dirza, R.</bold>, Hatanaka, T., and Fujita, M., 2013. Improved distributed coverage control for robotic visual sensor network under limited energy storage. Int. J. Imaging Robot. Vol. 10(2). pp. 58-74.
* M.S. in Jekyll, GitHub University, 2014
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)

Peer-reviewed Conference Publications
======
* B.S. in GitHub, GitHub University, 2012
* M.S. in Jekyll, GitHub University, 2014
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
