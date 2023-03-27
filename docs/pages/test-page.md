---
layout: page
title: test-post
subtitle: Posts
menubar: docs_menu
show_sidebar: false
toc: true
---

## Series of Posts

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. 
## Blog Series Data File

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. 

## Sections

Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet.
If you just want one list without labels, then omit the label and just add the items.

```yaml
title: The series title
sections:
  - items:
      - title: Why use a static site generator
      - title: Getting started with Bulma Clean Theme for Jekyll
```

Here is a full example with multiple sections with labels.

```yaml
title: The series title
description: The series description text
sections:
  - label: The first section
    items:
      - title: Why use a static site generator
      - title: Getting started with Bulma Clean Theme for Jekyll
  - label: Another section
    items:
      - title: Introducing some new layouts to Bulma Clean Theme
      - title: Creating a docs site with Bulma Clean Theme
      - title: Creating a post series
```

## Update your posts

Finally, add the series setting to your front matter in each post you want the series to show in.

```yaml
series: my_blog_series
```
