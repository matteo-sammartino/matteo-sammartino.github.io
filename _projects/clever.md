---
layout: page
title: Verification of Hardware Concurency via Model Learning (CLeVer)
description: 
img: /assets/img/hw.jpg
---

Our society is increasingly reliant on digital devices that are capable of performing several tasks at the same time: tablets, smartphones, our personal computers, they all contain processors capable of executing multiple instructions concurrently. Bugs in these processors, such as the recently discovered [Meltdown and Spectre](https://meltdownattack.com/), can seriously compromise the security and safety of their users. As the complexity of these systems increases, there is a pressing need to automate the assessment of their correctness, especially with respect to concurrency-related aspects. 



Formal verification provides highly effective techniques to automatically check important properties of systems. 
It relies on a machine-readable abstraction of the actual system---a **model**.
A key strength of formal verification is that, when the model is accurate enough, it is able to find bugs that would be hard to find and reproduce using traditional testing alone.
However, these models are usually built by humans, and as such can be error-prone and inaccurate.
Moreover, sophisticated concurrent behaviours such as weak-memory concurrency make modelling even more challenging.

>The overall goal of this project is to develop a verification framework for hardware systems that uses artificial intelligence to automatically build and verify better models. Ultimately, this will lead to lower production costs and more reliable hardware.

This is particularly important for companies that design hardware units destined to large-scale production, such as ARM: a bug in the design may lead to millions of faulty units being manufactured.


The novel idea behind this project is to rely on the **model learning** paradigm, originally proposed in AI, to automatically build a model of a running system in a **black-box fashion**---from a series of observations of the behaviour of the system. 
This approach can be very effective in taming complexity and achieving scalability: by treating the whole system, or some of its components, as black-boxes, one can fine-tune the level of detail of the model and focus the analysis on specific features.


In recent years model learning has started to be successfully applied in a variety of academic and industrial contexts. However, the models developed using this approach are all inherently **sequential**. The verification of **concurrent** behaviour in hardware systems is an unexplored, challenging, and potentially rewarding application that this project proposes to explore.
