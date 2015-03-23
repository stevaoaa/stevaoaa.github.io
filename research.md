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


## Proteum new user interface

The goal of this project is provide a new interface to Proteum tool. Proteum is a mutation testing tool for C programs at unit and integration phases. It's an integrated testing environment composed of a serie of modules that provides to the tester all the necessary resources for evaluating or generating test sets based on the mutation testing criterion. It's allow the execution of the following operations: 1) define the test cases; 2) execute the program under testing; 3) select mutation operators used to generate the mutants; 4) generate mutants; 5) execute mutants; 6) analyse alive mutants; and 7) compute the mutation score.

The project is under development and uses [PyGTK](www.pygtk.org) to suport the use of  the GTK+ toolkit in the creation of the user interface. All the source is available to download at my [GitHub repository](https://github.com/stevao-andrade/interface).

![Interface](/img/interface.png)

## Parallel Execution of programs was suport to mutation testing

The goals of this project is to apply workload balance algorithms in the context of mutation testing in order to reduce the response time in application of mutation testing. To suport the experiments in this project we use a collection of 39 programs developed in C language. The core of this project was developed using Python language and [PyZMQ](http://zeromq.org/) framework. All the source is available to download at my [GitHub repository](https://github.com/stevao-andrade/parallel_proteum).

![Proteum](/img/pproteum.jpg)