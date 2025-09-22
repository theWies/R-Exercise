---
title: "R Motel Exercise"
format: pdf
editor: visual
---

##############################################################################
##############################################################################
##############################################################################
##############################################################################

### Packages
```{r}
library(mosaic)
```

### Data
```{r}
rm(list=ls())
browseURL("http://www.principlesofeconometrics.com/poe5/data/def/motel.def")
load(url("http://www.principlesofeconometrics.com/poe5/data/rdata/motel.rdata"))

head(motel)
```

### Exercise
Our hotel has 100 units. Repair period of 7 months of around 14 rooms. 
Question: Did this affect occupancy rates and revenue.
Quantify losses. 

How much revenue did the motel lose due to construction?
Consider economic theory about hotel demand, role of pricing and competition,
and how to isolate the impact of the repairs from other market factors.

### Assumption:
- Occupancy rate is on the number of available rooms (100 and 86)

##############################################################################
##############################################################################

### Create variable revenue with the occupied rooms and rate per room

In times of no repair -> 100 rooms
In times of repair    -> 86 (100 - 14)
Revenue = Room rate * rooms

















