---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<p><u>I am first author on all publications listed below.</u></p>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

<ol class="publication-list">
{% for post in site.publications reversed %}
  {% include archive-single.html type="publication" %}
{% endfor %}
</ol>
