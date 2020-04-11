---
title: "Reinforcement Learning: Motivation"
date: 2020-04-11
excerpt: "Machine learning, 3 parts, recent successes, etc."
mathjax: "true"
---

## Motivation

As the name suggests, Reinforcement Learning(RL) is about learning to do a task with reinforcements. Imagine a kid learning to ride a bicycle. Nobody explicitly instructs the kid to apply say 5kN of force on the pedal, maintain your body balance on either sides of the centre of gravity, etc. Instead, he is made to ride it. While riding he may fall down and hurt himself(negative reinforcement) or he may ride it just fine and gain the appreciation(positive reinforcement) from his parents. Using these reinforcements he makes small changes in the way he rides and finally learns it.  

## H2 Heading

### H3 Heading

Here's some basic text.

And here's some *italics*

Here's some **bold** text.

What about a [link](https://github.com/dataoptimal)?

Here's a bulleted list:
* First item
+ Second item
- Third item

Here's a numbered list:
1. First
2. Second
3. Third

Python code block:
```python
    import numpy as np

    def test_function(x, y):
      z = np.sum(x,y)
      return z
```

R code block:
```r
library(tidyverse)
df <- read_csv("some_file.csv")
head(df)
```

Here's some inline code `x+y`.

Here's an image:
<img src="{{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg" alt="linearly separable data">

Here's another image using Kramdown:
![alt]({{ site.url }}{{ site.baseurl }}/images/perceptron/linsep.jpg)

Here's some math:

$$z=x+y$$

You can also put it inline $$z=x+y$$
