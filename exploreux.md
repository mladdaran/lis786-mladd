---
title: Explore UX
layout: page
permalink: /exploreux/
description: LEARN. SHARE. CONNECT.
---
## **This section will cover the basic UX concepts and I will also share some resources about UX.**

### **UX Basics**
Topics that will be covered:
- What is UX?
[usability.gov](https://www.usability.gov/what-and-why/user-experience.html)
- What is UX design?
  - [UX Design Guide for 2021](https://careerfoundry.com/en/blog/ux-design/what-is-user-experience-ux-design-everything-you-need-to-know-to-get-started/)
- [What is UX Design Video Guide](https://www.youtube.com/watch?v=v6n1i0qojws)
- The 6 steps in the [UX design process](https://www.invisionapp.com/inside-design/6-stages-ux-process/)
- Learn the differences between: [UX Design vs. UI Design](https://www.youtube.com/watch?v=Vnz_JbjxKFQ&t=8s)

### **UX Concepts & Resources**
<h2>Browse the topics below:</h2>
<h3>User Research</h3>
{% for ux_resources in site.ux_resources %}
{% if ux_resources.category == 'user_research' %}
<h4>{{ ux_resources.title }}</h4>
<p>{{ ux_resources.content | strip_html | truncate: 900, '...' }}</p>
<a href="{{ ux_resources.source }}" target="_blank">Source</a>
{% endif %}
{% endfor %}
