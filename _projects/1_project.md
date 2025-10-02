---
layout: page
title: Brain-LLM alignment 
description: Investigating Correlation between Brain Activation and Lanagugae Models Representation
img: assets/img/brain-llm.png
importance: 1
category: work
related_publications: true
---



In recent years, Large Language Models (LLMs) have achieved state-of-the-art performance in various NLP tasks. Despite their success, their internal processing remain an open question. Their complex architectures make interpretation challenging. Similarly, the human brain is a highly sophisticated computational system for processing language, and neuroscientist have long sought to understand its underlying mechanisms. Studies suggest that linguistic information is localized to specific brain regions. This raises a fundamental question: Do language models represent language in a way similar to the human brain? 

In this study, we examine how removing different linguistic properties affects the alignment between language models and brain responses. To achieve this, we first create multiple version of our corpus by removing syntactic or semantic information. For example, we replace all the nouns with a tag "NNOUN", transforming "Mary was a beautiful woman" into "NNOUN was a beautiful NNOUN". We then train two different language models LSTM and GPT2-small on the different distorted corpus where syntax or semantic information are replaced by corresponding tags. After that, we extract language representation of spoken narrative stories that contain fMRI responses while participants are listening to these stories. Then, we calculate the alignment by learning an encoding model to map two representations. Finally, we compare the alignments before and after removing the linguistic information.