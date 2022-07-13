---
layout: single
title: Research
permalink: "/academic/"
---

I am an MSc student at McGill university under the supervision of Prof. [Zeljko Zilic](http://iml.ece.mcgill.ca/people/professors/zilic/) at the Integrated Microsystems Laboratory. I've been trying to convince my lab mates that assertions are not enough to verify circuits, and we've been working towards a Coq implementation for verifying Verilog programs (or a subset of programs).

When I'm stuck into some arbitrary Coq proof, I usually spend some time in my side projects. One of them is thinking about [better interfaces for proof assistants]({{ site.url }}/download/submission-hatra21.pdf), and, more generally, how to make them more accessible to people. 

Before that, I've worked with OCaml and with the [LearnOCaml platform](https://github.com/teaching-the-art-of-fp/learn-ocaml). You can check my recent poster at SIGCSE'21 [here](https://dl.acm.org/doi/10.1145/3408877.3439579).

In the past, I also did research in an intersection of Electrical Engineering and Computer Science! More specifically, I've been trying to convince engineers that there are alternatives to C and C++, in particular at domains like electromagnetic transient analysis. I started with Python (in [this paper](https://ieeexplore.ieee.org/document/8627346)), and then created some [fully functional, upgraded version in Haskell](https://github.com/hannelita/haskell-etrp-doc/blob/master/Report.pdf).


Check my [CV]({{ site.url }}/download/HanneliCVwithprojects-dld.pdf) for further details.

## Research Interests and Academic Goals

Given my background in Electrical Engineering and CS, combined with years of industry experience, I became particularly interested in the intersection of software and hardware formalization. I am currently working on a verified Hardware Description Language (HDL) built in Coq and inspired in Verilog. I am constantly asking questions about its typing system: how can I design a strongly typed language without getting rid of the comfort of writing Verilog? How can I take into account the needs for time and resource representation? More importantly, how could I properly verify the properties of this language? Is there a good semantic model for it? 

I want to make Proof Assistants more accessible to a broader audience. I personally think they are awesome, and more projects could benefit from them - if we could lower the entry bar to this particular PL branch. There are many ways in which we can do it, but improving the tooling around them sounds like a good path. I threw in some of ideas in the [publications]({{ site.url }}/academic/#publications-list) list below.

Besides proof assistants and HDL, I'm broadly interested in general aspects of verification, type theory, functional programming, effective teaching of Maths, CS and Engineering.

## Publications List

1. [Towards an Incremental Dataset of Proofs]({{ site.url }}/download/submission-hatra21.pdf) - [Human Aspects of Types and Reasoning Assistants](https://2021.splashcon.org/details/hatra-2021-papers/9/Towards-an-Incremental-Dataset-of-Proofs) (HATRA) 2021 (co-located with [SPLASH'21](https://2021.splashcon.org/) )

1. [A Data-centered User Study for jsCoq](https://icfp21.sigplan.org/details/mlfamilyworkshop-2021-papers/11/A-Data-centered-User-Study-for-jsCoq-short-talk-) - ML Workshop 2021 (co-located with [ICFP'21](https://icfp21.sigplan.org/) )

1. [A Data-Centered User Study for Proof Assistant Tools](https://www.ppig.org/workshops/2021-annual-workshop/programme/) - Psychology of Programming Interest Group ([PPIG](https://www.ppig.org/) ) - 2021 Edition 

1. [Data Collection for the Learn-OCaml Programming Platform: Modelling How Students Develop Typed Functional Programs](https://dl.acm.org/doi/10.1145/3408877.3439579) - [SIGCSE'21](https://sigcse2021.sigcse.org/)

1. [Open Source Implementations of Electromagnetic Transient Algorithms](https://ieeexplore.ieee.org/document/8627346) - IEEE International Conference on Industry Applications ([INDUSCON](http://induscon.org/2018/) )

1. [Web social networks meters and business usage analysis](https://ieeexplore.ieee.org/document/6085948) - 2011 International Conference on Computational Aspects of Social Networks ([CASoN](https://www.mirlabs.net/cason11/) )