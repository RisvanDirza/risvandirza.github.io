---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

Journal Publications
======
* [J1] Gusrialdi, A., **Dirza, R.**, Hatanaka, T., and Fujita, M., 2013. Improved distributed coverage control for robotic visual sensor network under limited energy storage. Int. J. Imaging Robot. Vol. 10(2). pp. 58-74.

Peer-reviewed Conference Publications
======
* [C7] <bold>Dirza, R.</bold>, Skogestad, S., and Krishnamoorthy, D., 2021. Real-Time Optimal Resource Allocation and Constraint Negotiation Applied to A Subsea Oil Production Network. SPE ATCE 2021. Dubai, UAE.
* [C6] <bold>Dirza, R.</bold>, Skogestad, S., and Krishnamoorthy, D., 2021. Optimal Resource Allocation using Distributed Feedback-based Real-time Optimization. IFAC ADCHEM 2021 (Keynote Paper), IFAC-PapersOnLine, 54(3), pp.706-711. Venice, Italy.
* [C5] <bold>Dirza, R.</bold>, Marquez-Ruiz, A., Ozkan, L., and Mendez-Blanco, C.S., 2019. Integration of Max-plus-linear scheduling and control. ESCAPE 29. Eindhoven, the Netherlands.
* [C4] <bold>Dirza, R.</bold>, and Gusrialdi, A., 2011. Performance-guaranteed distributed coverage control for robotic visual sensor network with limited energy storage. IEEE Proceedings of the 2nd International Conference on Instrumentation Control and Automation. Bandung, Indonesia.
* [C3] Pradini, A., Roffi, T.M., <bold>Dirza, R.</bold>, and Adiono, T., 2011. VLSI design of a high-throughput discrete cosine transform for image compression systems. IEEE Proceedings of the International Conference on Electrical Engineering and Informatics. Bandung, Indonesia.
* [C2] Gusrialdi, A., <bold>Dirza, R.</bold>, and Hirche, S., 2011. Information-driven distributed coverage algorithms for mobile sensor networks. IEEE Proceedings of the International Conference on Networking, Sensing and Control. Delft, the Netherlands.
* [C1] <bold>Dirza, R.</bold>, Fujita, M., and Riyanto, B., 2010. Finite Energy Coverage Control with Limited Range Anisotropic Sensor for Mobile Sensor Networks. Proceedings of the 6th International Conference on Intelligent Unmanned Systems. Bali, Indonesia.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
