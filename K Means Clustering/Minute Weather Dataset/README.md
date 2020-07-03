# Identify Weather Pattern using k-means algorithm.

Find dataset here: https://www.kaggle.com/ktochylin/san-diego-every-minute-weather-indicators-201114

This activity guides through the process of performing cluster analysis on a dataset using k-means using Apache Spark. 
The cluster analysis was performed on the minute-weather.csv dataset using the k-means algorithm. 
The minute-weather.csv dataset contains weather measurements such as temperature, relative humidity, etc., from a weather station in San Diego, California
, collected at one-minute intervals. The goal of cluster analysis on this data is to identify different weather patterns for this weather station.

From elbow-plot, it was clear that the elbow in the curve is between 10 and 15, so for this analysis k = 12 was choosen.
