---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Please find the complete list of my publications <a href="https://researchmap.jp/ohkawatks/?lang=english">here</a>.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
