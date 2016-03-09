---
title: "Getting and Cleaning Data - Course Project"
author: "siva"
date: "March 8, 2016"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this:

```{r cars}
summary(cars)
```

## Including Plots

You can also embed plots, for example:

```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.


## Getting and Cleaning Data - Course Project

This is the course project for the Getting and Cleaning Data Coursera course. The R script, run_analysis.R, does the following:

    1.Download the dataset if it does not already exist in the working directory
    2.Load the activity and feature info
    3.Loads both the training and test datasets, keeping only those columns which reflect a mean
      or standard deviation
    4.Loads the activity and subject data for each dataset, and merges those columns with the
      dataset
    5.Merges the two datasets
    6.Converts the activity and subject columns into factors
    7.Creates a tidy dataset that consists of the average (mean) value of each variable for each
      subject and activity pair.

    The end result is shown in the file tidy.txt.
