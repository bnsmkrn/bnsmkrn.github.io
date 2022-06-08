---
title: "categorypage 11번 이름바꿈"
layout: archive
permalink: categories/cat11
author_profile: true
sidebar_main: true
published: true
---

{% assign posts = site.categories.cat11 %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}
