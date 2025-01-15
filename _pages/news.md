---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">Let's breakdown some of the less important events.</div>
{% endif %}

{% include base_path %}

{% for post in site.news reversed %}
  {% include archive-single.html %}
{% endfor %}
