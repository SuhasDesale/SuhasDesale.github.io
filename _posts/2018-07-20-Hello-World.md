---
published: true
publish: true
---
# Hello world  

 Hello world this is my first Blog.
 
# Kolhapur	
	

{% for image in site.static_files %}
  {% if image.path contains 'assets/images/Kolhapur' %}
![]({{ image.path }})
 {% endif %}
{% endfor %}
    
