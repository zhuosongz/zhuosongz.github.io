---
layout: page
title: STA 203
description: Undergraduate course
img: assets/img/1.jpg
importance: 1
category: work
related_publications: true
---

# 本科生课程

### STA 203 概率论基础 (2023秋)

#### 课程简介

To introduce the basic concepts in probability theory which forms the basis for all applications of probability and statistics, and for further probability and statistical theory including, in particular, stochastic processes. Also, to introduce the basic probability methods and techniques with a strong emphasis on applying these standard methods and techniques appropriately and with clear interpretation. The emphasis is on applications. The basic teaching goal is to grasp the basic concepts regarding random variables, random vectors, functions of random variables, expectation, variances, covariance, and central limit theorems and the related important conclusions and theorems and to study their extensive applications in many fields. The basic aim is to teach students to handle the basic theory and fundamental methods and technologies for random phenomenon, to train students' scientific thinking and problem analysis and problem-solving skills, and to lay a good foundation for the subsequent courses in modern probability theory.

本课程介绍概率论的最基本概念，它们组成了概率和统计的应用基石。本课程也为进一步学习其他概率和统 计课程，例如随机过程，打下良好的基础。本课程还重点介绍了一些基本的概率方法和技巧，且强调它们的 实际应用及概率解释。基本教学目标是掌握关于随机变量、随机向量、随机变量的函数、期望、方差、协方 差和中心极限定理及相关重要结论和定理，研究他们在许多领域广泛应用。基本目标是教会学生处理随机现 象的基本理论和基本方法技巧，培养学生的科学思维和分析解决问题的能力，并为后续课程打下良好的现代 概率论基础。

#### 课件

1. [概率的定义](/assets/pdf/sta203/slides1.pdf)
2. [条件概率](/assets/pdf/sta203/slides2.pdf)

### MAT 308 统计计算与软件 (2022秋)

# 研究生课程

### STA 5006 高等随机过程 (2023春、2024春)

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
