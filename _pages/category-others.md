--- 
title: "Others"
layout: archive
permalink: /others
author_profile: true
sidebar: 
    nav: "sidebar-category"
---
{% assign posts = site.categories.others %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
