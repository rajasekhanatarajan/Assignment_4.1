# Assignment_4.1
#1. Histogram for all variables in a dataset mtcars. Write a program to create histograms for all columns.

mtcars hist(mtcars$cyl) hist(mtcars$disp) hist(mtcars$hp) hist(mtcars$drat) hist(mtcars$wt) hist(mtcars$qsec) hist(mtcaboxplots) hist(mtcboxplotam) hist(mtcboxplotgear) hist(mtcboxplotcarb)

#2. Check the probability distribution of all variables in mtcars

hist(mtcars$mpg)x <- rnorm(1000, mean=100, sd=20) hist(x, probability=TRUE) xx <- seq(min(x), max(x), length=100) lines(xx, dnorm(xx, mean=100, sd=20))

#3. Write a program to create boxplot for all variables.

boxplot(mtcars$mpg) boxplot(mtcars$cyl) boxplot(mtcars$disp) boxplot(mtcars$hp) boxplot(mtcars$drat) boxplot(mtcars$wt) boxplot(mtcars$qsec) boxplot(mtcars$vs) boxplot(mtcars$am) boxplot(mtcars$gear) boxplot(mtcars$carb)
