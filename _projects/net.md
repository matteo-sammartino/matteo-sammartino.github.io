---
layout: page
title: Automated Black-box Verification of Networking Systems
description: 
img: /assets/img/net.png
---

Our society is increasingly reliant on **complex networking systems**, consisting of several components that operate in a distributed/concurrent fashion, exchange data that may be highly sensitive, and are implemented with a mix of open and closed-source code. Examples are Software Defined Networks, cloud computing systems, Internet of Things and others. 


As the complexity of these systems increases, there is a pressing need of methods and tools to automatically verify  security and privacy properties.
**High quality models** -- able to express all the behaviours of interest -- are of paramount importance to this aim. However, it is often the case that the task of building a model is performed by humans and in a short span of time -- if it is performed at all -- and as such can be error-prone and inaccurate.


The goal of this project is to develop techniques and tools to automate the modelling and verification of networking software systems. 
The novel idea is to rely on the **model learning** paradigm, originally proposed in artificial intelligence, to automatically build a state-based model of a running system in a **black-box fashion** -- purely via interactions with the running system. 
This approach can be very effective in taming complexity and achieving scalability: by treating the whole system, or some of its components, as black-boxes, one can fine-tune the level of detail of the model and focus the analysis on specific features.

In particular, the project will focus on learning models that capture two prominent features of modern networking systems, which play a key role in security and privacy: **concurrency** and **large data domains**. 

The proposed research is highly innovative: there are no existing techniques to automatically learn state-based models of networking behaviour, let alone ones dealing with concurrency and large data domains. It is also particularly timely, as networks now allow for an unprecedented control over their behaviour via software, which brings new challenges and new opportunities for analysis.

The research will be conducted in the context of the [CALF](http://www.calf-project.org/) research programme, aiming at developing a general foundational framework for the design and implementation of model learning algorithms. This will give a strong theoretical foundation to the endeavour, and a wide applicability to its results.