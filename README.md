# MUSA508_LAB1
********

## This file is for MUSA 508 practice purpose

*******
Several things were covered in this lab session and Here is a list 
---------
1. blabla
2. blablabla



---
title: "README.md"
author: "Bingchu"
date: "9/11/2020"
output: html_document
---
## some analysis

here is the data

```{r}
str(mtcars)
```

plot the data

```{r}
plot(as.factor(mtcars$cyl), mtcars$mpg)
```

my findings

```{r}
tt <- t.test(mtcars$cyl, mtcars$mpg)
print(tt)
```
