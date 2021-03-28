---
layout: post
title: "Testing Code Blocks"
date: 2021-03-28
author: "metajon"
---

{% highlight matlab %}
syms w a b
W = [0 0 w];
r = [a b 0];
Wab = cross(W,r);
{% endhighlight %}