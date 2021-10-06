---
layout: page
permalink: /student-projects/
title: "student projects"
---

A few ideas for BSc/MSc and MEng projects. Please contact me if you are interested and want to have a chat.

#### **Representing the correct ways of using a software library**

Functions in a software library sometimes need to be used in a specific order. For instance, in Python file.read() must be called after file = open(). However, in many cases patterns are not well-documented, and so developers often make mistakes. The goal of this project is to devise techniques to build an automaton representing those patterns, which can be used to check if a given piece of code follows the patterns. This can be done in several ways, for instance by "mining" online information. I am particularly interested in *learning* the pattern automaton in a black-box fashion, via interactions with the library. In fact, it is often the case that the source code of the library is not available, therefore one can only look at what happens when the library functions are called with certain parameters.

#### **Algorithms for (symbolic) register automata**

Finite-state automata can become very big when the alphabet is large, and cannot handle an infinite alphabet. To tackle these issues, richer types of automata have been introduced. 

[Symbolic automata](http://pages.cs.wisc.edu/~loris/papers/cav17-tutorial) have *predicates* on transitions, representing the fact that a (possibly infinite) class of symbols can be read by a transition. For instance, predicates can be regular expressions, e.g., `[0-9]`, meaning that a transition can read any character between 0 and 9.

[Register automata](https://doi.org/10.1016/0304-3975(94)90242-9) have *registers*, where they can store symbols they read, and compare them with those read later.

Recently, [symbolic register automata](https://arxiv.org/abs/1811.06968) have been introduced, combining the features of both automata.


Several questions remain open. Minimization algorithms for symbolic automata are available. How can we minimise a register automaton? And symbolic register automata? Can we do it via *partition refinement*? Can we exploit the structure of registers to give an efficient algorithm for checking language equivalence of two (deterministic) symbolic register automata?




