---
title: "App"
layout: archive
permalink: categories/app
author_profile: true
---

{% assign posts = site.categories.app %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}