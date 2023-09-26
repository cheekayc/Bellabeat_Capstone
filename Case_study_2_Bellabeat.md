Bellabeat Data Analysis Case Study
================
Chee Kay Cheong
2023-09-26

# Introduction

Bellabeat, a leading high-tech manufacturer specializing in
health-centric products for women, has made significant strides as a
successful small enterprise. However, the company aspires to carve a
more substantial presence in the global smart device market. Recognizing
this opportunity, Urška Sršen, the co-founder and Chief Creative Officer
of Bellabeat, is keen on exploring the untapped potential within the
realm of smart device fitness data analysis. Among Bellabeat’s diverse
product range, this case study will center on their flagship product -
the Leaf.

The *Leaf*, a timeless wellness tracker, offers versatility as it can be
worn as a bracelet, necklace, or clip. Seamlessly integrated with the
Bellabeat app, the Leaf tracker serves as a comprehensive health
companion, diligently monitoring users’ activity levels, sleep patterns,
and stress levels. In this data analysis endeavor, we aim to unlock
valuable insights derived from smart device data, providing Bellabeat
with actionable strategies to fuel its growth and influence within the
global smart device market.

# Business Task

The primary goal of this project is to analyze the daily habits of smart
device consumers using Fitbit Fitness Tracker data to inform our
marketing strategies. Specifically, we will categorize Fitbit users into
distinct user types and examine their usage patterns. These insights
will be leveraged to support Bellabeat’s marketing team in crafting
effective strategies to promote our product, the Leaf. The final outcome
will consist of three key recommendations aimed at enhancing the Leaf’s
appeal to a broader customer base.

## Data Sources

``` r
knitr::opts_chunk$set(warning = FALSE, message = FALSE)

library(tidyverse)
library(lubridate)
library(skimr)
library(janitor)
```
