---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

- [Home]({{ base_path }}/)
{% for item in site.data.navigation.main %}
- [{{ item.title }}]({{ base_path }}{{ item.url }})
{% endfor %}
