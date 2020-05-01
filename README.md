# Analysis of COVID-19 County Data from The New York Times

*Author: Mark Bauer*  
*Date Updated: April 12, 2020*  
*Date Updated: May 1, 2020*

The New York Times Github Data Repository: https://github.com/nytimes/covid-19-data.   
The New York Times News Article: https://www.nytimes.com/article/coronavirus-county-data-us.html.  
The New York Times COVID-19 US Map: https://www.nytimes.com/interactive/2020/us/coronavirus-us-cases.html.   
The New York Times COVID-19 Global Map: https://www.nytimes.com/interactive/2020/world/coronavirus-maps.html.  


# Tables

**Table 1. Coronavirus (COVID-19) Cases in the United States by County (Top 10 Counties)**

|    | date       | county        | state      | cases   | deaths   |
|---:|:-----------|:--------------|:-----------|--------:|---------:|
|  0 | 2020-04-30 | New York City | New York     | 167,489 | 12,514   |
|  1 | 2020-04-30 | Cook          | Illinois     | 36,513  | 1,607    |
|  2 | 2020-04-30 | Nassau        | New York     | 35,854  | 2,111    |
|  3 | 2020-04-30 | Suffolk       | New York     | 33,664  | 1,228    |
|  4 | 2020-04-30 | Westchester   | New York     | 28,969  | 1,144    |
|  5 | 2020-04-30 | Los Angeles   | California   | 23,182  | 1,111    |
|  6 | 2020-04-30 | Wayne         | Michigan     | 16,729  | 1,782    |
|  7 | 2020-04-30 | Bergen        | New Jersey   | 15,610  | 1,136    |
|  8 | 2020-04-30 | Hudson        | New Jersey   | 14,916  | 798      |
|  9 | 2020-04-30 | Philadelphia  | Pennsylvania | 14,468  | 607      | 


# Bar Charts

![numer of cases county horizontal](figures/counties-barh.png)  

![epi curve](figures/epi_curve.png)  


# Figures

##  Number of Positives Per Day

### Weekly Average

![days since 10 daily cases top 10 weekly](figures/10-cases-timeseries-by-county-top-10-weekly.png)

![days since 10 daily cases top 10 weekly log](figures/10-cases-timeseries-by-county-top-10-weekly-log.png) 

### Daily

![days since 10 daily cases top 10 daily](figures/10-cases-timeseries-by-county-top-10-daily.png)

![days since 10 daily cases top 10 daily log](figures/10-cases-timeseries-by-county-top-10-daily-log.png)


##  Growth Factor of Number of Positives per Day

### Weekly Average

![growth factor daily cases top 10 weekly](figures/growth-factor-top-10-weekly.png)

### Daily 

![growth factor daily cases top 10 daily](figures/growth-factor-top-10-daily.png)


## Cumulative Number of Positive Cases  

### Top 10 Counties
![number of cases timeseries tenth case](figures/county-timeseries-tenth-case.png)

![number of cases timeseries tenth case log](figures/county-timeseries-tenth-case-log.png)  

### All Counties
![days since 10 cases](figures/10-cases-timeseries-all-counties.png)

![days since 10 cases log](figures/10-cases-timeseries-all-counties-log.png)


## Trajectory of Number of Positive Cases

![number of cases trajectory weekly average](figures/county-trajectory-weekly-plot.png)   

![number of cases trajectory county weekly average 900 case min](figures/all-counties-trajectory-weekly-plot-labels.png)

![number of cases trajectory county weekly average](figures/all-counties-trajectory-weekly-plot.png) 

![number of cases trajectory usa weekly average](figures/usa-counties-trajectory-weekly-plot.png)


## Time Series

### Top 10 Counties
![number of cases timeseries](figures/county-timeseries-top10.png)

![number of cases timeseries log](figures/county-timeseries-top10-log.png)  



