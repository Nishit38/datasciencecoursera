---
title: "Data Read"
author: "Nishit Prajapati"
date: "01/07/2020"
output: pdf_document
---


```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## This is a markdown file

## R markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:


## Data read in R 
In this we creat data frame using different values.

```{r}
id=c(100:103)
name=c("preet","ram","ravi","srv")
marks=c(10,20,30,40)
dataframe=data.frame(id,name,marks)
dataframe
```
