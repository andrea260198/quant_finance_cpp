# Quantitative Finance C\+\+ Project

![image](Img/Stocks.png)


## Introduction

The goal of this project is to replicate the **quant_finance** repository 
previously created using Python language. We want to assess the differences between 
writing a quantitative finance repository in C\+\+ rather than Python.

The projects will also have a **GUI** built using the **Qt Framework**.


## DataFrame Library

I created my own version of the Pandas DataFrame class to use it in C\+\+.


## CMake

The project uses CMake as build system. The choice was made to be able to build 
the code both on Windows and Linux.


## CTest and GoogleTest

Testing is performed using **GoogleTest** and **CTest**.
Unit tests are defined using the GoogleTest framework, then built and run using
`ctest` commands.


## CERN Root

The goal would be to create plots using **CERN Root** framwork, which was
developed to plot the results from the experiments at CERN in Geneva.

This is still a work in progress.