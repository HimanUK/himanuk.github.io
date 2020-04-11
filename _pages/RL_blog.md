---
layout: archive
title: "RL Blog"
permalink: /rlblog/
author_profile: true
excerpt: "Blog on Reinforcement Learning"
---

I intend to write at least one blog post every week wherein I cover some aspect of RL. I wish to stress on building a strong intuition before delving deep into the mathematics of the subject.

{% include group-by-array collection=site.posts field="tags" %}

{% for tag in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ tag | slugify }}" class="archive__subtitle">{{ tag }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}
