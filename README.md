# DataMiningandHealthcare

This is the Veteran's Administration Lung Cancer Trial data set (Kalbfeisch and Prentice).This data set shows the what treatment was and the effectiveness depending on a variety of factors.

There are 8 attributes:

stime: Survival time; days since treatment

status: 1(dead) and 0(alive)

treat: 1(standard treatment) and 2(test drug treatment)

age: in years

Karn: Karnofsky score
diag.time: time since diagnosis (months)

cell: type of cell; 1(squamous cell), 2(small cell), 3(adeno cell), 4(large cell)

prior: prior therapy (0=none and 10=yes) 

# Using DB-SCAN (Density-Based Spatial Clustering of Applications with Noise) algorithm to measure distance between the nearest points

```{r}
library(readxl)
CancerResearch <- read_excel("~/INFO 523/CancerResearch.xlsx")
View(CancerResearch)
library(fpc)
```

