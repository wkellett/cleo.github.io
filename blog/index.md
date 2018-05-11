---
layout: default
title: Cleo Technical Blog
---
# {{ page.title }}
	
         {% for post in site.posts %}
	    {{ post.date | date_to_string }} » [{{post.title}}]({{ post.url }})
	 {% endfor %}
	
