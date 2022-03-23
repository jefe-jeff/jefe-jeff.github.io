---
layout: post
title:  "Thoughts on Deep Generative Methods"
date:   2021-03-27 15:05:22 -0500
categories: jekyll update
---

Over the last couple of days, I've looked over the class notes for CS 236: Deep Generative Methods. This post is a review of what I learned, as well as a place to clarify some of the philosophical questions I have.

Feynman (supposedly) said "What I cannot create, I do not understand." This remark, along with its contrapositive "What I do understand, I can create", sounds about right. However, generative methods do not pursue the contrapositive; they pursue the ever fallacious yet sometimes useful negation, "What I can create, I do understand." It is this choice that makes them interesting to me but also inspires plenty of questions.

In the following, I will outline the approaches given by four general approaches to generative models: autoregressive models, variational autoencoders, normalized flow models, and generative adversarial networks. Mostly, this is for me to solidify my own understanding and practice using concise and cogent language to describe technical ideas. In addition, I will outline some of the philosophical questions I have regarding this field's approach to problem solving. Hopefully, it will serve as a record for myself in the future. 
