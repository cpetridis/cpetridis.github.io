---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">Stay tuned for events that barely matter! :) Let’s break down some critically unimportant events. :) </div>
{% endif %}

{% include base_path %}

{% for post in site.news reversed %}
  {% include archive-single.html %}
{% endfor %}
