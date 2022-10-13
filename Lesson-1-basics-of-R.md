---
title: "Lesson1: The basics of R"
author: "Mohammad Shamim Hasan Mandal"
date: "2022-10-13"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE, eval = FALSE)
```

## Interacting with the R console

Simple commands can be be passed interactively using the R console.


## Printing in the console

Use the R console to type the codes and follow along.

To print a message on the console use the print function. In the below code, a message "Hello world!" was passed inside the print() function. Notice the brackets!

```{r print1}
print("Hello world!")
```


> Note: Notice that because we are passing a texts therefore we need to use either single quotation or double quotation. Either one will be fine. But it is better to stick to one style throughtout your code.


The below code will produce an error. R will notify it by printing an error message on the console. Error messages are always helpful as we can check where we make mistakes and correct them. But it is sometimes not clear! We won't think about it for the moment. 

```{r error_print}
print(Hello world!)
```

To print numbers in the console, just simply pass them inside the print function

```{r number_print}
print(2022) # printing 2022
```

> Note: If you copy the line and paste it to the console, R will only print 2022. However, it will ingore the text after. The text "# printing 2022" begines with a hash (#) sign, this is a special symbol to tell R to ingore anything after this symbole in a line. This is called commenting, and is useful to write useful notes throught our program codes.



