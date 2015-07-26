---
title       : Developing data products
subtitle    : mtcars dataset
author      : ljuba80
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
--- 

## mtcars dataset

- mpg	  - Miles/(US) gallon
- cyl	  - Number of cylinders
-	disp	- Displacement (cu.in.)
- hp	  - Gross horsepower
- drat	- Rear axle ratio
- wt	  - Weight (lb/1000)
- qsec	- 1/4 mile time
- vs	  - V/S
- am	  - Transmission (0 = automatic, 1 = manual)
- gear	- Number of forward gears
- carb	- Number of carburetors

Is there correlation between consumption (mpg) and Transmission type?

--- .class #id 

## Analysis


- First step is analysis of mpg ~ am variable

- Analysis showed that average value for mpg is17.1473684  
  when transmission type is  automatic and 24.3923077 for manual transmission

- Results shows that, in average, cars with manual transmission type have smaller consumption (higher mpg value) than cars with automatic consumption


- Hypothesis analysis confirmed previous results. With 95% probability we can state that difference between average mpg for cars with automatic and manual transmission will be between -11.2801944 and -3.2096842

- As interval doesn't contain zero value, we reject hypothesis that average consumption for two types of care is the same.

- Interval sign tells that manual transmission cars  have higher mpg value (lesser consumption)

- However, this is fairy simple one dimensional model 

--- .class #id

## 

- Box plots can give initial insight of data dependency

- We see that average value  of consumption is higher (mpg is lower) for cars with automatic transmission

![plot of chunk unnamed-chunk-3](assets/fig/unnamed-chunk-3-1.png) 

--- .class #id 

## Presentation


- For presentation go  to shinyapps.io [(mtcars presentation)](http://ljuba80.shinyapps.io/mtcars)

- This presentation contains reports based from simple analysis mpg ~ single variable
---
