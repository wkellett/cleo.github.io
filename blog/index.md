---
layout: default
title: Cleo Technical Blog
---
# {{ page.title }}
	
         {% for post in site.posts %}
	    - {{ post.date | date_to_string }} » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}
	  {% endfor %}
	
