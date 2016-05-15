---
layout: default
title: Project site
tagline: Go for it 
description: This is GitHub Pages
v1: abcd
v2: efgh
---


### Github front matter with liquid tags

Github jekyll support liquid tag using double curly braces with object "page".

I have created the following front matters with custom variables such as tagline, description, v1 and v2

```
 ---
 layout: page
 title: Project site
 tagline: Go for it 
 description: This is GitHub Pages
 v1: abcd
 v2: efgh
 ---
```

### Using the variables via liquid tag**

To get the values of the custom variables from the front matters, use liquid tags.
Jekyll liquid tags consist of double curly braces like so.

```
  {% raw %}  {{page.v1}} {% endraw %}
  {% raw %}  {{page.v2}}  {% endraw %}
```

**The result**

**tagline value is:** {{page.tagline}}

**description value is:** {{page.description}}

**v1 value is:** {{page.v1}}
**v2 value is:** {{page.v2}}

 

---

Others


