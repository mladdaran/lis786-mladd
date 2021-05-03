---
title: Explore UX
layout: page
permalink: /exploreux/
description: LEARN. SHARE. CONNECT.
---
## **This section will cover UX concepts & tools.**

<h3>Browse the topics below:</h3>

{% for ux_resources in site.ux_resources %}
{% if ux_resources.category == 'ux_basics' %}
<h4>{{ ux_resources.title }}</h4>
<p>{{ ux_resources.content | strip_html | truncatewords: 800, '...' }}</p>
<a href="{{ ux_resources.source }}" target="_blank">Source</a>
{% endif %}
{% endfor %}

{% for ux_resources in site.ux_resources %}
{% if ux_resources.category == 'ux_design' %}
<h4>{{ ux_resources.title }}</h4>
<p>{{ ux_resources.content | strip_html | truncatewords: 800, '...' }}</p>
<a href="{{ ux_resources.source }}" target="_blank">Source</a>
{% endif %}
{% endfor %}

{% for ux_resources in site.ux_resources %}
{% if ux_resources.category == 'user_research' %}
<h4>{{ ux_resources.title }}</h4>
<p>{{ ux_resources.content | strip_html | truncatewords: 800, '...' }}</p>
<a href="{{ ux_resources.source }}" target="_blank">Source</a>
{% endif %}
{% endfor %}

{% for ux_resources in site.ux_resources %}
{% if ux_resources.category == 'ux_tools' %}
<h4>{{ ux_resources.title }}</h4>
<p>{{ ux_resources.content | strip_html | truncatewords: 800, '...' }}</p>
<a href="{{ ux_resources.source }}" target="_blank">Source</a>
{% endif %}
{% endfor %}
