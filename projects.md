---
layout: page
title: Directory of Projects
permalink: /projects/
menu: true
menutext: Projects
---

Here is a current list of projects:

{% assign projects = site.projects | sort: 'priority' %} {% for project in projects %}* [{{ project.title }}]({{ project.permalink }}) 
{% endfor %}


