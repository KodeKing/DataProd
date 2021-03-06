---



title       : Developing Data Products Project
subtitle    : Doing Regression Analysis in your Head
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides



---

## The Project

1. Random points are generated and plotted as follows:

```r
set.seed(123); n=100 ;x = 1:n
y= rnorm(n,mean=.1*x,sd=1) *x +   rnorm(n,mean=1.8*x,sd=40)
plot(x,y)
```

![plot of chunk unnamed-chunk-1](assets/fig/unnamed-chunk-1.png) 

2. The user is invited to draw a regression line
3. Clicking the Submit button will show the true regression line

--- .class #id 

## Instructions

1.  Move the slider to change the slope of the line
2.  Click the up/down buttons to move the intercept of the line.

---

## Purpose

1.  Show the intuition behind linear regression
2.  Allow the user to play with the data

---

## Future Development

1.  Show points that are heavily skewed.
2.  Go to three dimensions






