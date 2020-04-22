# Analysis of COVID-19 County Data from The New York Times

*Author: Mark Bauer*  
*Date Updated: April 12, 2020*  
*Date Updated: April 22, 2020*

The New York Times Github Data Repository: https://github.com/nytimes/covid-19-data.   
The New York Times News Article: https://www.nytimes.com/article/coronavirus-county-data-us.html.  
The New York Times COVID-19 US Map: https://www.nytimes.com/interactive/2020/us/coronavirus-us-cases.html.   
The New York Times COVID-19 Global Map: https://www.nytimes.com/interactive/2020/world/coronavirus-maps.html.  


# Tables

**Table 1. Coronavirus (COVID-19) Cases in the United States by County (Top 10 Counties)**

|    | date       | county        | state      | cases   | deaths   |
|---:|:-----------|:--------------|:-----------|--------:|---------:|
|  0 | 2020-04-21 | New York City | New York   | 139,335 | 10,301   |
|  1 | 2020-04-21 | Nassau        | New York   | 31,079  | 1,717    |
|  2 | 2020-04-21 | Suffolk       | New York   | 28,154  | 918      |
|  3 | 2020-04-21 | Westchester   | New York   | 24,655  | 904      |
|  4 | 2020-04-21 | Cook          | Illinois   | 23,181  | 1,002    |
|  5 | 2020-04-21 | Los Angeles   | California | 15,140  | 663      |
|  6 | 2020-04-21 | Wayne         | Michigan   | 14,255  | 1,278    |
|  7 | 2020-04-21 | Bergen        | New Jersey | 13,356  | 835      |
|  8 | 2020-04-21 | Hudson        | New Jersey | 11,636  | 525      |
|  9 | 2020-04-21 | Essex         | New Jersey | 11,128  | 849      | 


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



