---
title       : Finding mu!
subtitle    : 
author      : Yuha Hwang
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [mathjax]            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---


## Purpose of Finding mu!

This application tries to find how to find mu of a child's height on galton's data.

By using the slider a user can simply find the lowest MSE value which finds the mu of the data in a given parameter.

We can confirm the result with the formula at the conclusion.




--- .class #id



## What is mu

"??" is the lower case of greek letter mu.

It is a mean of a probability distribution in statistics.

Often used to describe the population mean!


--- .class #id


## What is MSE

In statistics, the mean squared error (MSE) of an estimator measures the average of the squares of the "errors", 

that is, the difference between the estimator and what is estimated.(Wikipedia)

Therefore, smallest MSE given the mu should provide the most accurate mu.

--- .class#id

## Conclusion


```
## Loading required package: MASS
```

```
## [1] 68
```

Mean calculated above should equal to graphically found mu.


```
## Initializing Git Repo
```

```
## Warning: running command 'git init' had status 127
## Warning: running command 'git commit --allow-empty -m 'Initial Commit'' had status 127
```

```
## Checking out gh-pages branch...
```

```
## Warning: running command 'git checkout -b gh-pages' had status 127
```

```
## Adding .nojekyll to repo
## Publishing deck to monggul/slidify
```

```
## Warning: running command 'git add .' had status 127
## Warning: running command 'git commit -a -m "publishing deck"' had status 127
## Warning: running command 'git push git@github.com:monggul/slidify gh-pages' had status 127
```

```
## You can now view your slide deck at http://monggul.github.com/slidify
```
