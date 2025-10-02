---
layout: page
title: Explaining Machine Learning Models for Sentiment Analysis Using LIME
description: 
img: assets/img/brain-llm.png
importance: 2
category: work
giscus_comments: true
---

Explaining Machine Learning Models for Sentiment Analysis Using LIME

A significant improvement has been conducted in Sentiment Analysis over the years using machine learning. Despite their state-of-art performance, machine learning models remain mostly black boxes. Leveraging explainability ensures reliable and trustworthy models. In this study, we demonstrate an explainable technique to understand the outcome of the machine learning models. To achieve this, we train two machine learning classifiers on a review dataset and explain models by presenting representative individual predictions. We eliminate important words from the original text that provided by the explanation model to evaluate the efficiency of the explanation model. We observe that the important words selected by explainer model does not have any impact on the prediction which indicates the limitation of our proposed explanation model. 


Our code is available in <a href="https://github.com/shantanu778/semantic_explainable_analyzer">Github</a>.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/example.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Highlighting the most influential words for each prediction using LIME explanation model.
</div>


