---
title: Explore UX
layout: page
permalink: /exploreux/
description: LEARN. SHARE. CONNECT.
---
## **This section will cover the basic UX concepts and I will also share some resources about UX.**

## **UX Concepts & Resources**
<h3>Browse the topics below:</h3>
<h4>User Research</h4>
{% for ux_resources in site.ux_resources %}
{% if ux_resources.category == 'user_research' %}
<h5>{{ ux_resources.title }}</h5>
<p>{{ ux_resources.content | strip_html | truncate: 900, '...' }}</p>
<a href="{{ ux_resources.source }}" target="_blank">Source</a>
{% endif %}
{% endfor %}
