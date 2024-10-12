---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


{% if author.googlescholar %}
  You can also find my articles on <a href="https://scholar.google.com/citations?hl=zh-CN&user=PgM9DT8AAAAJ" target="_blank">my Google Scholar profile</a>.
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
