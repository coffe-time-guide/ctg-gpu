---
description: >-
  Before going into details, let us be clear why we need GPUs! And how they fit
  into a general computer hardware.
---

# Introduction

* GPUs are co-processors, which will always require a host CPU for control.
* GPUs are de-facto accelerators for graphics.
  * Before the AI explosion, many traditional computer vision algorithms used GPUs. However, they were no match for vector processors like [DSPs ](https://pages.cs.wisc.edu/\~danav/pubs/qcom/hexagon\_hotchips2013.pdf)in terms of power efficiency. The introduction of [vector extensions](https://en.wikipedia.org/wiki/Advanced\_Vector\_Extensions) into the CPU meant very few use cases for GPU for performing CV tasks.
  * They are now popular for DNN training/inference. However, that may change based on the success of other accelerators. ( In fact, widely used Deep learning models like Recommendation models. Graph networks, Language models, etc still use CPUs for inference ).
  * However, due to monetary reasons, it makes more sense for companies like NVIDIA/AMD/Apple/Samsung to invest in improving GPU architecture as they already have a killer app (Gaming !)
