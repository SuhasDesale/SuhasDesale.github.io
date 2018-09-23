---
published: true
---
## Some unpublished work 

### Yellow
![Yellow]({{site.baseurl}}/       SuhasDesale.github.io/assets/images/24Sep/_68C3298.jpg     )


### Sliver
![Sliver]({{site.baseurl}}/       SuhasDesale.github.io/assets/images/24Sep/_68C2197.jpg     )

### Dusk

{% for image in site.static_files %}
  {% if image.path contains 'assets/images/24sep' %}
![]({{ image.path }})
 {% endif %}
{% endfor %}
