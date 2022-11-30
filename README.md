# Performing-Analysis-of-Meteorological-Data
Using Scikit-Learn

One type of data that’s easier to find on the net is Weather data. Many sites provide historical
data on many meteorological parameters such as pressure, temperature, humidity,
wind_speed, visibility, etc. 
(Source URL: https://www.kaggle.com/muthuj7/weather-dataset) 

The dataset has hourly temperature recorded for last 10 years starting from 2006-04-01
00:00:00.000 +0200 to 2016-09-09 23:00:00.000 +0200. It corresponds to Finland, a country in
the Northern Europe. You can download the dataset from this Google drive link:
https://drive.google.com/open?id=1ScF_1a-bkHi1qe8Rn78uxK6_5QwUD9Bu

My goal in this Internship (of data analysis) was to transform the raw data into information and
then convert it into knowledge.
In this Internship assignment, I was responsible for performing data cleaning, performing
analysis for testing the (given) Hypothesis and finally concluding this by writing a blog article.

    The Null Hypothesis H0 is "Has the Apparent temperature and humidity compared monthly
across 10 years of the data indicate an increase due to Global warming"

The H0 means we need to find whether the average Apparent temperature for the
month of a month say April starting from 2006 to 2016 and the average humidity for
the same period have increased or not. This monthly analysis has to be done for all 12
months over the 10 year period. So basically we are resampling the data from hourly
to monthly, then comparing the same month over the 10 year period. Supporting the
analysis by appropriate visualizations using matplotlib and / or seaborn library.
 
Conclusion:
  Global warming is no doubt deteriorating the climate and is affecting various parameters of the environment.Hence from this analysis we infer that there are either sharp rise in temperatures or sharp falls over the 10 yrs. Hence we can conclude that Global Warming has caused a major difference and unreliability in temperature predictability also taking humidity into consideration we can say that it has almost remained same throughout the past years.
