---
layout: docs
title: HfG infrastructure
permalink: /docs/
lang: en
version: 0.1
tags:
  - Getting-started
  - Account
---

# The HfG infrastructure

There are many digital services that the HfG offers to all the community.

The principal links and log-in data that you will need in a glance:

<div class="section-index">
    
    {% for post in site.docs  %}        
    <div class="entry">
    <h5><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h5>
    <p>{{ post.description }}</p>
    </div>{% endfor %}
</div>
