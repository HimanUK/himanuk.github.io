---
layout: archive
title: "RL Blog"
permalink: /rlblog/
author_profile: true
excerpt: "Blog on Reinforcement Learning"
---

I intend to write at least one blog post every week wherein I cover some aspect of RL. I wish to stress on building a strong intuition before delving deep into the mathematics of the subject.

Also, I've majorly learned about RL from [Dr. L.A. Prashanth](http://www.cse.iitm.ac.in/~prashla/). He happens to be my Masters guide as well. It is probably due to his style of teaching that I'm personally inclinced to the theoretical RL. 

For now, I am designing it in a way that people with a basic understanding undergraduate level mathematics shouldnt face a hard time. Such subjects include calculus, linear algebra, probability and statistics, set theory, etc. As and when I get time, I'll add posts explaining these basics concepts. However, a lot of better resources exist wherein mathematics required for RL is succintly explained.


{% include group-by-array collection=site.posts field="tags" %}
{% for tag in group_names %}
  {% assign posts = group_items[forloop.index0] %}
  <h2 id="{{ tag | slugify }}" class="archive__subtitle">{{ tag }}</h2>
  {% for post in posts %}
    {% include archive-single.html %}
  {% endfor %}
{% endfor %}

