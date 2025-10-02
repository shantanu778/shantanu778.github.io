---
layout: page
title: A comparison study of pre-trained and randomly initialized models on image and sequence data
description: 
img: /assets/img/RNN-CNN.png
importance: 3
category: work
---

In this paper, the effects of pre-training of deep learning models are investigated. A computer vision
task on the identification of leaf diseases on Casava plants is performed with a pre-trained ResNet-34
model, as well as with a ResNet-34 model using randomized weights. Additionally, a natural language
processing task is done with sentiment analysis on Coronavirus related tweets. The sentiment analysis
is done using a pre-trained BERT model and an untrained version of BERT. In addition to the deep
learning approaches, two baseline models are developed as a reference for performance. As the
baseline model, a simple CNN is used for the computer vision task and an LSTM model is used for
the natural language processing task. The experiments clearly showed the importance of pre-training,
with the pre-trained ResNet-34 model yielding 85.7% accuracy over the untrained 76.7%, and the
pre-trained BERT model yielding 86.0% accuracy over the untrained 25.0%.



<div class="caption">
   Figure 1 shows the Overview of Recurent Neural Netwrok(LSTM) - semantic analysis on tweet dataset regarding Coronavirus. Figure 2 shows the Overview of Convolution Neural Network (CNN) - Image Classification on Cassava Leaf Disease.
</div>
<div class="row">
    <div class="col-sm mt-6 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/rnn.webp" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-6 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/CNN-Cassava.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


To read the whole Article <a href="https://drive.google.com/file/d/1NdhCGbfKUkW89Cb9pLUtqeF7eQm8qYQW/view?usp=sharing"> Click here.. </a>


<a href="https://github.com/AbhishekRS4/Deep_Learning"> Available Code </a> 