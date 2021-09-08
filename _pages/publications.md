---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can also find my papers on <a href="https://www.researchgate.net/profile/Simon-Liebl">ResearchGate</a>.

Click on the title to get more information.
{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
