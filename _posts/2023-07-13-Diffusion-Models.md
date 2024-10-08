---
title: 'Diffusion Models From Scratch'
date: 2023-07-13
permalink: /posts/2023/07/gene/
tags:
  - Generative models
  - From scratch
  - Diffusion models
---


In the ever-evolving landscape of artificial intelligence and machine learning, a new class of generative models has emerged, captivating researchers and practitioners alike: Diffusion Models. These powerful algorithms have taken the AI world by storm, producing results that push the boundaries of what we thought possible in computer-generated content. Diffusion Models represent a paradigm shift in how we approach generative tasks. Unlike their predecessors, such as Generative Adversarial Networks (GANs) or Variational Autoencoders (VAEs), Diffusion Models draw inspiration from thermodynamics and stochastic processes to create a unique approach to content generation. At their core, Diffusion Models work by gradually adding noise to data and then learning to reverse this process.
In this blog post, we'll embark on a journey to understand Diffusion Models from the ground up. We'll explore the underlying principles, dive into the mathematics that makes them work, and even implement a simple version to see these fascinating models in action.
Let's begin our journey into the world of Diffusion Models!

# Generative Models: Creating from Data

Generative models are a class of machine learning models that aim to generate new data samples that resemble a given dataset. In essence, these models learn the underlying distribution of the training data and can then produce new, previously unseen samples from this learned distribution.

Before Diffusion Models gained prominence, two main types of generative models dominated the field:

## 1. Generative Adversarial Networks (GANs)
