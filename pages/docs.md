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

- Account Management System: Link | Documentation
- Webmail:  Link | Documentation
- Nextcloud: Link | Documentation
- Moodle: Link | Documentation
- BigBlueButton:  Link | Documentation
- His1: Link | Docuemntation

<div class="section-index">
    <hr class="panel-line">
    {% for post in site.docs  %}        
    <div class="entry">
    <h5><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h5>
    <p>{{ post.description }}</p>
    </div>{% endfor %}
</div>
