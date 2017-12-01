---
layout: page
title: Directory of Projects
permalink: /projects/
menu: true
menutext: Projects
---

{% assign projects = site.projects | sort: 'title' %} {% for project in site.projects %}* [{{ project.title }}]({{ project.permalink }}) 
{% endfor %}

Here is a current list of projects:

* Memetics Standard Model document
* Guild Dynamics Model document
* Ceptr Holochain
* Holoculture Database (HCDB) Project
* Holoculture Superconductor (HCSC) Project
* The Human Memone Project
* The Commodity Specs Project
