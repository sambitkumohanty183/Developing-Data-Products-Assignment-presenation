---
title       : Developing Data Products Assignment
subtitle    : Wage Payment Calculator
author      : Sambit Kumar Mohanty
job         : Wage Calculator
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
logo        : logo.png
---

## Objective

Build an application to demonstrate:

1. use of various widgets of 'shiny' tool
2. understanding of the process of publishing application in shiny
3. interface with R using embeded R code.

---

## Project Details

A simple application to get the employee wages per week basis based on the hours worked and the wage rate.

---
## User Interface

The application takes following two inputs from the user:

1. Hours(per week)
2. Rate(in $ per hour)

---
## Calculation formula

The Calculation formula is simple multiplication of Hours work(per week) and the rate per hours.Example if a employee work for 40 hours and the wage rate is 10($ per hour).


```r
40 * 10
```

```
## [1] 400
```


## Thanks 
