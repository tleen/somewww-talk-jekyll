---
order: 2
group: jekyll-intro
group_order: 11
---

# Useful Additions

Jekyll populates liquid with useful data:


* [Data files](http://jekyllrb.com/docs/datafiles/)
 YAML, JSON, CSV, in *_data/*

* [Permalinks](http://jekyllrb.com/docs/permalinks/)
change format of post urls. WordPressy.

* [Pagination](http://jekyllrb.com/docs/pagination/)
{% raw %}
```
Page: {{ paginator.page }} of {{ paginator.total_pages }}
```

{% endraw %}
