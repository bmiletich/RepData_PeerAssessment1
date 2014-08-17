---
title: "peer_assessment_1"
output: html_document
---

First, we will load the data.
```{r}
data<-read.csv("activity.csv")
```

Now, we will draw up a histogram of the total number of steps taken each day. We will ignore all NA values.

```{r fig.width=7, fig.height=6}
hist(data$steps[!is.na(dat$steps)])
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
