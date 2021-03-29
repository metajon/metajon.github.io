---
layout: post
usemathjax: true
title: "Testing Code Blocks"
date: 2021-03-28
author: "metajon"
---
{% include mathjax.html %}
Here's an quick example for using the symbolic math package in MATLAB for doing quick calculations where you may not have values assigned.

In the below example, I am showing how $r = <a\hat{i} + b\hat{j}>$ relates to $\omega\hat{k}$ in general plane motion.

~~~ matlab
syms w a b
W = [0 0 w];
r = [a b 0];
Wab = cross(W,r);

ans =
 
[ -b*w, a*w, 0]
~~~