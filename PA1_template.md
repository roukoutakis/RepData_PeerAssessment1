---
title: "Reproducible Research: Peer Assessment 1"
output: 
  html_document:
    keep_md: true
---


## Loading and preprocessing the data
Loading the data from csv

```r
activity<-read.csv("activity.csv")
```

## What is mean total number of steps taken per day?
The mean is

```r
mean(na.omit(activity$steps))
```

```
## [1] 37.3826
```
Plot of steps vs date

```r
plot(activity$date, activity$steps)
```

![plot of chunk unnamed-chunk-3](figure/unnamed-chunk-3-1.png) 

## What is the average daily activity pattern?



## Imputing missing values



## Are there differences in activity patterns between weekdays and weekends?
