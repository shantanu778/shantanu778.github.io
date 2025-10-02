---
layout: page
title: "Offline Handwriting Recognition: Deep Neural Network Approaches"
description: 
img: assets/img/line-segmentation.png
importance: 4
category: work
---

Automatic Handwriting Recognition is a research field of AI which is yet to be solved. Due to the high inherent variability of hand-written text, a ‘one-fits-all approach’ is extremely complex to identify. However, in recent years the application and combination of statistical and neural network approaches have shown promising results. In this
paper, we, therefore, evaluate several approaches of digitizing offline handwritten text on two data sets, the Dead Sea Scrolls (DSS) and the IAM data set. With a focus on Deep Learning models which were used to segment line (ARU-net), detect characters (CNN & InceptionRes-NetV2) and digitize whole lines of text (encoder-decoder) we were able to achieve Character Error Rates (CER) as far as 5% for distinct tasks.

<div class="caption">
    Overview of the Line Segmentation Pipeline.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/line-segmentation.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


To read the whole Article <a href="https://drive.google.com/file/d/1ZLKMhI-aQS9EtKKoM961NYxakvSpPV6d/view?usp=sharing"> Click here.. </a>

<a href="https://github.com/shantanu778/hand_written_recognition_task_12"> Available Code </a>
