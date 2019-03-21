---
layout: page
title: Wiki
description: Best China IPTV Service Provider
keywords: Support, Wiki
comments: false
menu: Wiki
permalink: /wiki/
---

> How should I set the TV Box up？

<ul class="listing">
{% for wiki in site.wiki %}
{% if wiki.title != "Wiki Template" %}
<li class="listing-item"><a href="{{ wiki.url }}">{{ wiki.title }}</a></li>
{% endif %}
{% endfor %}
</ul>
