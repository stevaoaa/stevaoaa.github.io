---
layout: page
title: Research
sitemap:
    priority: 1.0
    changefreq: weekly
    lastmod: 2014-09-07T16:31:30+05:30
---
# Research

This section will provide some userful information about the projects that i'm involved. Fell free to enter in contact if you want to help.

>stevao.andrade@gmail.com


## Parallel Execution of programs was suport to mutation testing

###Goal

> The goal of this project is to apply workload balance algorithms in the context of mutation testing in order to reduce the response time in application of mutation testing. 


###Gap

> One of the biggest problems for the application of mutation test is related to the high computational cost involved in its execution. This cost is related to the time required for the implementation and evaluation of the large number of mutants generated.


###Null Hypothesis

> The use of parallel algorithms for load balancing and distribution can not improve the efficiency of the application of mutation testing.


###Justification/Motivation

> Software testing is an essential and critical activity during the process of
development and thus research to improve their application are important. The mutation testing has been considered one of the most effective criteria to reveal defects however the high cost of implementation restricts its use. These reasons motivated the development of this project. 


To suport the experiments in this project we use a collection of 39 programs developed in C language. The core of this project was developed using Python language and [PyZMQ](http://zeromq.org/) framework. All the source is available to download at my [GitHub repository](https://github.com/stevao-andrade/parallel_proteum).

[![Proteum Parallel Execution](/img/pproteum.jpg)](https://www.youtube.com/watch?v=0cPcyZBNBio "Proof of Concept - Proteum Parallel Execution ")


## Proteum new user interface

The goal of this project is provide a new interface to Proteum tool. Proteum is a mutation testing tool for C programs at unit and integration phases. It's an integrated testing environment composed of a serie of modules that provides to the tester all the necessary resources for evaluating or generating test sets based on the mutation testing criterion. It's allow the execution of the following operations: 1) define the test cases; 2) execute the program under testing; 3) select mutation operators used to generate the mutants; 4) generate mutants; 5) execute mutants; 6) analyse alive mutants; and 7) compute the mutation score.

The project is under development and uses [PyGTK](www.pygtk.org) to suport the use of  the GTK+ toolkit in the creation of the user interface. All the source is available to download at my [GitHub repository](https://github.com/stevao-andrade/interface).

![Interface](/img/interface.png)