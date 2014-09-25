---
order: 2
group: jekyll-intro
group_order: 10
---

# Layouts

* Uses [Liquid](http://liquidmarkup.org/)
* Gives you access to data to build the html

{% raw %}
```
{% for slides in site.slides %}
{{ slide.output }}
{% endfor %}
```
{% endraw %}


