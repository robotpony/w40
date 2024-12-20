---
slug: the-evolution-of-thinking-in-software-design
title: The evolution of thinking in software design
date: 2011-05-10T23:00:13Z
draft: false
tags:
- software-design
---

I know a few generations of developers. I find they tend toward different ways of thinking about software design, based on the
languages and decomposition tools that were available at the time they formed their thinking. Their tendencies shift over time
too, but often their imaginations are limited by whichever mode of thought they're working in at the time.

By design I mean the approach to solving a problem with software, including software architecture and low level design (not
product, visual, or UX design). These are another universe around how we think about solving people's problems with software,
a topic for another set of posts.

I realized the other day that design thinking follows an evolutionary path. It progresses to solve larger problems in better
ways, and is based on layering and combining the various tools and techniques available.

### A maze of twisted pathways

1. Flowcharts and pseudo code
2. Data diagrams and relational algebra
3. Eventing and state diagrams
4. Object diagrams and trees
5. Layered architectures and approaches
6. Partitions and service maps

The thinking moves from direct low level constructs toward more abstract solutions, based on less obvious symmetries and
fissures. A flowchart, for example, is a direct mapping of instructions. A set of services and domain partitions is far less
direct, and often maps to important constrains like scaling, performance, and cost.

### Well, duh

It's obvious that our thinking has changed as software becomes more complex. What's interesting is how we get stuck in
particular ways of thinking, and how difficult it is to translate between the various design approaches. A procedural
solution is a very different beast than one based on intersecting data, and is very different again from a set of disjoint
services for the same concepts.

To talk about design intelligently, we need to lay the groundwork for how we plan to cast the approach. More than one
design tool can be used, but it's important that everyone participating in the design understands how to think and
discuss things cast using that particular approach.
