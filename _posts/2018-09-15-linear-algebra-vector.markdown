---
layout: post
title:  "线性代数笔记-向量"
date:   2018-09-15 15:01:30 +0800
categories: jekyll update
---
<script type="text/javascript" src="http://cdn.mathjax.org/mathjax/latest/MathJax.js?config=default"></script>

![avatar](https://raw.githubusercontent.com/bladeralien/bladeralien.github.io/master/_posts/2018-09-15-linear-algebra-vector-PICTURE-0.PNG)

如图中所示，根据 [cosine rule](https://en.wikipedia.org/wiki/Law_of_cosines)，我们有

$$c^2 = a^2 + b^2 - 2{\times}a{\times}b{\times}cos{\theta}$$

若我们假设\\(a\\)对应的向量为\\(r\\)，\\(b\\)对应的向量为\\(s\\)，则\\(c\\)对应的向量为\\(r-s\\)，那么我们有

$$(r-s){\cdot}(r-s) = r{\cdot}r + s{\cdot}s - 2{\times}|r|{\times}|s|{\times}cos{\theta}$$

经过化简后，可以得到

$$cos{\theta} = \frac{r{\cdot}s}{|r|{\times}|s|}$$

那么，显然，\\(s\\)在\\(r\\)的投影的长度为

$$\frac{r{\cdot}s}{|r|}$$

那么，\\(s\\)在\\(r\\)上投影出来的向量为

$$\frac{r{\cdot}s}{|r|{\times}|r|}{\cdot}r$$

显然，上述公式亦可以写为

$$\frac{r{\cdot}s}{r{\cdot}r}{\cdot}r$$
