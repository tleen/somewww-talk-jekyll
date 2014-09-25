---
order: 2
group: jekyll-intro
group_order: 9
---

# Custom Types

* posts-style handling can be extended to arbitrary types: **slides**
* tell *_config.yml*:
```
collections:
    slides:
      output : false
```

Now you can put slides in the *_slides* directory. And get a list of them in liquid as: *site.slides*.
