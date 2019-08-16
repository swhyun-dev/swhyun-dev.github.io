---
title: "Web"
layout: archive
permalink: /post/web
author_profile: true
---

{% assign posts = site.categories.web | sort:"date" %}

{% for post in posts %}
  {% include archive-single.html type=page.entries_layout %}
{% endfor %}
