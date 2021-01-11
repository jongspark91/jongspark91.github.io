---
title: "[CS231n] 1. Data-Driven Approach"
excerpt: "Data-Driven Approach"

categories:
    - MLDL
tags:
    - Machine Learning
    - Deep Learning
---

*This post has been written based on CS231n lecture.*

# Data-Driven Approach
To simply explain Data-Driven Approach, it is an approach to train a model with abundant data.

Before this, there were many attempts to create classifier models.

![cs231n](https://user-images.githubusercontent.com/74899925/104215314-ebe07b00-547b-11eb-89c9-07b71deefd56.png)
*http://cs231n.stanford.edu/slides/2017/cs231n_2017_lecture2.pdf*

The picture above well explains what was attempted:
>1. Specify the appearance of a cat ("Has two ears, two eyes, how the nose looks like... etc)
>2. Implement those characters as edges.
>3. Implement the edges as algorithms.
>4. Test

This sounds quite grinding. This edge method have several problems.

>1. Different classes that has similar edges might also be classified as cats.
>2. If the class changes, you need to implement the whole new algorithms.

To supplement these issues, the data-driven approach is adopted.
It enables the model to train itself by data, making it needless to implement unnecessary-grinding works. 



