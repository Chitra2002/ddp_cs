---
title       : Developing Data Product APP
subtitle    : Histogram for Geyser Eruption Duration
author      : Chitra Shukla
job         : Consultant
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Title

Developing Data Product APP
Histogram for Geyser Eruption Duration Dataset

By - Chitra Shukla

--- .class #id

## Introduction

The perpose of this project is to prepare a moving histogram. The data used was obtained 
from R dataset. The analysis and illustration is for Geyser eruptions. The visual comparision
is by the way of the histogram wih slider.

--- .class #id 

## Project Overview

This shiny application is created for the Coursera Developing Data Product Project.
The aim of this excercise is to anyalise data that has been gathered to show the
waiting time between the eruptions and the duration of the erupton of the Old Faithful
Geyser in Yellow stone National Park, WY, USA.
There are 272 observations on two variables.

--- .class #id

## Aplication and Function

The Aplication is created with the Standard Ui.R and Server.R codes using shiny packages
to prepare panels and sidebars as needed.
the hist function is shown below

```r
?hist
hist
```

```
## function (x, ...) 
## UseMethod("hist")
## <bytecode: 0x000000000953ed18>
## <environment: namespace:graphics>
```
The above code shows what histogram does.

--- .class #id

## Summary and Publication

The project was completed to meet the assignment goal and is published on R pubs.




