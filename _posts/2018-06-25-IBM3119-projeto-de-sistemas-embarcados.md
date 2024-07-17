---
title: IBM3119 - Design of Embedded Systems
author: Rigel Fernandes
date: 2018-06-25
category: Jekyll
layout: post
mermaid: true
---

The jekyll-gitbook theme leverages [jekyll-toc][1] to generate the *Contents* for the page.
The TOC feature is not enabled by default. To use the TOC feature, modify the TOC
configuration in `_config.yml`:

```Matlab
clear; close all; clc;
    [x,fs] = audioread('file.wav')
```

# Chapter 1: Requirements, specifications, and modeling
-------------

## Continuous dynamics

### Newtonian Mechanics

### Actor models

### Properties of systems

### Feedback control

## Discrete dynamics

### The notion of state

### Finite-state machines

Example of a state diagram:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

Sequence diagram:

```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```

### Extended state machines

### Nondeterminism

### Behaviors and traces

## Hybrid systems

## Composition of state machines

## Concurrent models of computation

## Conclusions

long contents .....

1. a
2. b

# Chapter 2: Analysis, verification, and optimization
-------------

## Invariants and temporal logic

## Equivalence and refinement

## Quantitative Analysis

## Security and privacy

## Conclusion

[1]: https://github.com/allejo/jekyll-toc
