# Predict Bike-Sharing need in Metropolitan Area

<img src="https://i.imgur.com/Q59tXx6.png" width="500">

In this part we implement different machine learning models to find the best one. How bike could be predict needed in Metro area.
## Installation

Use the function `install.packages()`to install needed packages.

```R
install.packages("gridExtra")
install.packages("rattle")
install.packages("xgboost")
install.packages("caTools")
install.packages("caret")
install.packages("rattle")
install.packages("MLmetrics")
install.packages("kernlab")
install.packages('e1071', dependencies=TRUE)
install.packages("PerformanceAnalytics")
```

## Usage

```R
library(tidyverse)
library(reshape2)
library(PerformanceAnalytics)
library(gridExtra)
library(corrplot)
require(gridExtra) # also loads grid
require(lattice)
library(glmnet)
library(rpart)
library(rattle)
library(rpart.plot)
library(mlr)       # ML package (also some data manipulation)
library(knitr)     # just using this for kable() to make pretty tables)
library(xgboost)
library(Metrics)
library(RColorBrewer)
library(rattle)
```

## Contributing

Thanh Chung Nguyen - Data scientist
