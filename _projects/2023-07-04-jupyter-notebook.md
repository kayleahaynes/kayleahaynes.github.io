---
layout: page
title: Coffee Barchart
date: 2024-07-04 08:57:00-0400
description: an example of a blog post with jupyter notebook
tags: formatting jupyter
category: data visualisation
giscus_comments: true
related_posts: false
img: /assets/img/coffeeplot.png
---

{::nomarkdown}
{% assign jupyter_path = "assets/jupyter/2024-05-14.ipynb" | relative_url %}
{% capture notebook_exists %}{% file_exists assets/jupyter/2024-05-14.ipynb %}{% endcapture %}
{% if notebook_exists == "true" %}
{% jupyter_notebook jupyter_path %}
{% else %}

<p>Sorry, the notebook you are looking for does not exist.</p>
{% endif %}
{:/nomarkdown}

Note that the jupyter notebook supports both light and dark themes.