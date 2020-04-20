# COVID_19_Impact_on_Different_Counties
## Background
COVID-19 is rapidly spreading across the United States, and as the pandemic becomes more severe, it is important to ask: which US counties are the most vulnerable to the pandemic based on population characteristics and hospital bed availability?

## Data
Looking at data from the [US Census](https://www.census.gov/geographies/reference-files/2018/demo/popest/2018-fips.html), [New York Times](https://github.com/nytimes/covid-19-data), [American Community Survey](https://data.census.gov/cedsci/table?q=United%20States&g=0100000US.050000&tid=ACSST5Y2018.S0101&hidePreview=false&vintage=2018&layer=VT_2018_050_00_PY_D1&cid=DP05_0001E&t=Populations%20and%20People), [Johns Hopkins University](https://github.com/CSSEGISandData/COVID-19), and the [Department of Homeland Security](https://hifld-geoplatform.opendata.arcgis.com/datasets/hospitals), we can determine how counties can implement the most effective policies against COVID-19 based on their characteristics. 

![alt_text](https://github.com/AndrealZhang/COVID_19_Impact_on_Different_Counties/blob/master/COVID-19%20correlation%20heat%20map.png)
Looking at this correlation table, we see that the correlation between the number of hospital beds per 1,000 people and number of COVID-19 cases per 1,000 is around 0.04, and the correlation between the number of hospital beds per 1,000 people and number of deaths per 1,000 people is around 0.05. There is almost zero correlation, meaning that a county's vulnerability to the pandemic is not related to hospital bed availability. 

However, as we know that COVID-19 affects those who are over 60 more gravely then middle aged and younger people, we can further investigate this. From the correlation chart, we see that the correlation between the number of deaths per 1,000 and the total number of people who are 60 years and over is around 0.17. Although this is still a small number, it’s significant because it shows that the greater number of people over 60 there are in a county, the greater number of deaths there will be. 

Let’s look at counties with the greatest number of people over 60:
![alt_text](https://github.com/AndrealZhang/COVID_19_Impact_on_Different_Counties/blob/master/Over%2060%20bar%20chart.png)

## Summary and Implications
1. Number of hospital beds does not have an impact on the number of deaths due to COVID-19.
2. The greater number of people over 60 there are in a county, the greater number of deaths there will be. 
3. Counties with a greater number of people over 60, such as Los Angeles, should implement stricter social distancing policies to prevent the spread of COVID-19.

