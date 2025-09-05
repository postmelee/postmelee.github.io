---
title: "App"
layout: archive
permalink: categories/app
author_profile: true
---


{% assign posts = site.categories.app %}
{% for post in posts %} {% include archive-taxonomy.html type=page.entries_layout %} {% endfor %}