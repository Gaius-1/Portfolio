---
title: Garbage Segregator
tags: [Python, Streamlit, Pytorch, Arduino]
image:
  src: /images/waste-segregator.png
  alt: ""
timestamp: 2022-08-06
description: AI Image Recognition App that automatically identifies any waste image into its respective category.
codeLink: https://github.com/squash-bit/Waste-Segregator
---

## Table of Content
  * [<span class="text-terminal-green">Overview</span>](#overview)
  * [<span class="text-terminal-green">Motivation</span>](#motivation)
  * [<span class="text-terminal-green">Procedure</span>](#procedure)
  * [<span class="text-terminal-green">Model</span>](#model)
  

## Overview
This is a Garbage Classification Web Application built using both Streamlit and PyTorch.

## Motivation
The present way of separating waste/garbage is the hand-picking method, whereby someone is
employed to separate out the different objects/materials. The person, who separate waste, is prone to diseases due to the harmful substances in the garbage. With this in mind, it motivated me to develop an automated system which is able to sort the waste in a more accurate way than the manual one. With the system in place, the beneficial separated waste can still be recycled and converted to energy and fuel for the growth of the economy. 


For people who are not experts at Django or Flask, Streamlit can be a good alternative to build custom Python web apps for data science. I chose image classification as the task here because computer vision is one of the most popular areas of AI currently, powered by the advancement of deep learning algorithms.

## Procedure
  * Install Streamlit
  * Build UI
  * Build Model
  * Test Results
  * Next Steps
  
## Model
I have chosen the pretrained ResNet50 model to perform classification. To figure out how the model was built, take a look at the jupyter notebook entitled `Waste_Segregator.ipynb`...