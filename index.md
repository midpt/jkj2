---
layout: default
title: Project site
tagline: Go for it 
description: This is GitHub Pages
v1: abcd
v2: efgh
---

###Github front matter with liquid tags

Github jekyll support liquid tag using double curly braces with object "page".

I have created the following front matter with custom variables such as v1 and v2

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

**Using the variables via liquid tag**

To get the values of the custom variables from the front matter, use liquid tag like so. 

``` 
 {{page.v1}}
 {{page.v2}}
```


**The result**

tagline value is: {{page.tagline}}

description value is: {{page.description}}

v1 value is: {{page.v1}}
v2 value is: {{page.v2}}


Visit other pages on this site

- [Overview](pages/overview.html)
- [Page 1](pages/page1.html)
- [Page 2](pages/page2.html)


---

Others


