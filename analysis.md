# Consequences of Severe Weather Events
Thomas Bell  
31 juli 2017  



## Synopsis

## Data Processing


```r
df <- read.csv("repdata%2Fdata%2FStormData.csv.bz2") 

## downloaded from https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2FStormData.csv.bz2 on 31-7-2017 16:00 CET

library(xlsx)
```

```
## Loading required package: rJava
```

```
## Loading required package: xlsxjars
```

```r
fips <- read.xlsx("fips_codes_website.xls", sheetIndex=1, header=TRUE) 

## downloaded from http://www.census.gov/2010census/xls/fips_codes_website.xls on 2-8-2017 12:50 CET
```







## Results

