---
layout: post
title: When Pytorch-transformers meets Fastai
subtitle: After the update of Pytorch-transformers
gh-repo: DavidykZhao/Pytorch_transformers_Fastai
gh-badge: [star, fork, follow]
bigimg: /img/bert.jpeg
tags: [Pytorch_transformers, fastai]
comments: true
---

This is a post I originially published in the famous data science blog Towards Data Science. It has been retweeted by the NLP giant Hugging Face. 

This post bridged the gap between the APIs of Fastai and Hugging Face's Pytorch-transformers. What it essentially does is to wrap the model object from Pytorch-transformers into the highly flexible Fastai training API. In this way, we could combine the state-of-the-art pretrained model from Pytorch-transformers, with the advanced deep learning tricks such as one cycle traning and infinite callback systems from Fastai.

This post introduces two ways to incorporate the Pytorch-transformers model into fastai framework. 
The post to the article is [here](https://towardsdatascience.com/best-of-two-worlds-pytorch-transformers-meets-fastai-5fd51ef34b0f){:target="_blank"}

You could find a Google Colab notebook in [here](https://colab.research.google.com/drive/1KFlyttLs7aAX35lMLiDw9Bb0s_74ILMy?source=post_page-----5fd51ef34b0f----------------------#scrollTo=NPgXRybJk2XN){:target="_blank"} if you want to dive in to interact with the code.


And the corresponding notebook could be found [here](https://github.com/DavidykZhao/Pytorch_transformers_Fastai/blob/master/Pytorch_transformers_Fastai.ipynb){:target="_blank"}.


Please feel free to let me know any questions you may encounter in incorporating the two frameworks. 