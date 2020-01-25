Module 2 Assignment
================

For this assignment, we are looking at and evaluating the function called "myMean". This function takes the sum of a vector of numbers and divides it by the numeric length of another vector.

``` r
assignment <- c(16, 18, 14, 22, 27, 17, 19, 17, 17, 22, 20, 22)
lengthVector = c(1:12)
myMean <- function(myMean) {
  return(sum(assignment)/length(lengthVector))
}
round(myMean(), digits = 2)
```

    ## [1] 19.25

In the example above, the sum of our 'assignment' vector totals to 231 and the length of the divisor in this case is 12. We can now call the function to find that the mean of our assignment vector is 19.25.
