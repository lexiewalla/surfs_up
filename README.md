# surfs_up
module 9 SQLite

## Overview

In this module we used python, pandas, SQLite, and SQLAlchemy to determine the weather in Oahu. We are building a database to store the weather from the previous years to determine the best spot for an ice cream/surf shop. We used SQLite to import the weather data set through SQLAlchemy’s create_engine function that holds the location of the SQLite database file, shown in the image below. Once we have imported the data we wrote two separate queries to retrieve all of the temperatures for the months of June and December. Once we received all the June and December data, we used python pandas to convert the data into lists and created dataframes for each month of data. After all the data was converted to a dataframe, we used the .describe() method to retrieve the stats of the data. 

<img width="385" alt="dbfile" src="https://user-images.githubusercontent.com/45208773/138363900-49888f4e-ae89-42e2-9ac6-dcbddb5b40f3.PNG">

 

## Results

•	Between the two months there were 3,217 temperatures recorded from 2010-2016 June and December. This is a large amount of data and is beneficial because it gives you a good idea of what these months typically look like each year.

•	The average temperature for June was 75 degrees and 71 degrees in December, overall averaging at 73 degrees. This is showing that the temperature is pretty steady year-round with desirable temperatures for a surf and ice cream shop. 

<img width="173" alt="junestats" src="https://user-images.githubusercontent.com/45208773/138362323-07714938-a6e7-4e47-aff7-40df2410ee0e.PNG">\\



•	The minimum temperatures for these months were 64 degrees in June and 56 degrees in December with the highs being 85 degrees in June and 83 degrees in December. I would imagine the shop would not get as much business during these cooler temperature days, but it is inevitable that not all days will be as warm as others. Based on the standard deviation of both months, these lower cooler temperatures are far and few between.

<img width="173" alt="junestats" src="https://user-images.githubusercontent.com/45208773/138362426-799adcc0-f088-4c06-a508-da03ef000ee3.PNG">


## Summary

Overall, I believe Oahu would be a wonderful place for an ice cream/surf shop location. With desirable temperatures most of the time, not too hot and not too cool. The dataframes organized the data very nicely but I think it would be beneficial to further organize the data into histograms so you can really see the distribution of the temperatures of each month for each year and how it varies from year to year. The temperature data is telling me that this is a good spot to put the shop, however, rain is a huge factor in the shop’s business. I think further investigation is needed to determine what the stats are with rain in these two months. To find the rain data we would use these queries in the image below. I would use these two queries to pull oall of the rain data for both months and put them in a dataframe and then find the stats on the months. This will be extremely beneficial because people will be less likely to go to the shop in the rain than in cooler weather.

<img width="677" alt="rain query" src="https://user-images.githubusercontent.com/45208773/138362692-ee5cd269-f94b-4b10-90ee-b563541ff7b9.PNG">
