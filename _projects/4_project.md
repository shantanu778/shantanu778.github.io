---
layout: page
title: Offline Handwriting Recognition: Deep Neural Network Approaches
description: 
img: assets/img/line-segmentation.png
importance: 4
category: work
---

Automatic Handwriting Recognition is a research field of AI which is yet to be solved. Due to the high inherent variability of hand-written text, a ‘one-fits-all approach’ is extremely complex to identify. However, in recent years the application and combination of statistical and neural network approaches have shown promising results. In this
paper, we, therefore, evaluate several approaches of digitizing offline handwritten text on two data sets, the Dead Sea Scrolls (DSS) and the IAM data set. With a focus on Deep Learning models which were used to segment line (ARU-net), detect characters (CNN & InceptionRes-NetV2) and digitize whole lines of text (encoder-decoder) we were able to achieve Character Error Rates (CER) as far as 5% for distinct tasks.

<!-- 
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
</div> -->\

<div class="caption">
    Overview of the Line Segmentation Pipeline.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/line-segmentation.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


<!-- <div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div> -->


<!-- The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above: -->

<!-- 
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
-->
To read the whole Article <a href="https://drive.google.com/file/d/1ZLKMhI-aQS9EtKKoM961NYxakvSpPV6d/view?usp=sharing"> Click here.. </a>

<a href="https://github.com/shantanu778/hand_written_recognition_task_12"> Available Code </a>
