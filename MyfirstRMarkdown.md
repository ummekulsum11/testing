---
title: "My first R Markdown"
author: "Umme Kulsum"
date: "2024-03-01"
output: pdf_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## R Markdown

This is an R Markdown document. Markdown is a simple formatting syntax for authoring HTML, PDF, and MS Word documents. For more details on using R Markdown see <http://rmarkdown.rstudio.com>.

When you click the **Knit** **hello** button a document will be generated that includes both content as well as the output of any embedded R code chunks within the document. You can embed an R code chunk like this: - try - creating - your - own - bullet - list

**hello** *kulsum* [links](https://www.google.com) bullets - try \### Today's shopping list \* Milk \* Break \* Eggs \# Time to learn some markdown! \## Time to learn some markdown! \### Time to learn some markdown! \#### Time to learn some markdown! \# Time to learn more \# Lets create a list \* ruler \* Milk \* Eggs \* Cereal \* Fruit

```{r cars}
summary(cars)
```

```{r}
print("hello world from kulsum")
```

```{python}
for i in name=("umme kulsum"):
  print(i)
```

## Including Plots

You can also embed plots, for example:

```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
