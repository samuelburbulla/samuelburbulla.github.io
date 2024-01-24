---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

You can find all of my articles on
<a href="https://scholar.google.com/citations?user=uUkxLGAAAAAJ">my Google Scholar profile</a>.

<h2>Selected Papers</h2>

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
