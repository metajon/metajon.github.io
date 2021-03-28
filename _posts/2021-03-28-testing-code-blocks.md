---
layout: post
title: "Testing Code Blocks"
date: 2021-03-28
author: "metajon"
---

Here's an quick example for using the symbolic math package in MATLAB for doing quick calculations where you may not have values assigned.

{% highlight matlab %}
syms w a b
W = [0 0 w];
r = [a b 0];
Wab = cross(W,r);
{% endhighlight %}