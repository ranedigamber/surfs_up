# Surfs_up
## Overview of the challenge
In this module we are woowing an investor W.Avy to secure his capital in a Surf-n-Shake shop that we are proposing to be located in Oahu, Hawaii. In order to convice W.Avy that the chosen location is ideal for the Surf-n-Shake shop we have to provide him with detailed analysis of the weather pattern of this location. Our initial analysis had a positive feed back for the investor who now wants to invest in additional locations for similar shops.  For this we have used sqlite, sqlalchemy and flask to generate the necessary analysis. 

## Results:
  * From the summary for the two month these are the observations:
	1. The average temperature in June (~75 degF) is higher than that in December (~71 degF) 
	2. The standard deviation for December (~3.75) is higher than June (~3.26)
	3. The variation in temperature collected from different stations in December (max=83 and min=56) is higher than that recorded in June (max=85 and min=64). This may indicate greater variabilty in temperature in December since the number of data points collected for June (1700) is quite higher than December (1517).

![June analysis](https://user-images.githubusercontent.com/107159218/184269997-02d10380-903f-4510-8c7a-68d9e0c1e94b.PNG)

![December analysis](https://user-images.githubusercontent.com/107159218/184270012-3620e524-bcbb-4c6f-bd0a-3bad9c7d352c.PNG)


  

## Summary 
  * As described in the result section, the month of June is hotter than December. However the temperature recorded from different stations show higher temperature variability in December than June. Despite the variation both the months are equally favorable for Surf-and-Shake shop. These are the additional queries that I would make in addition to those already covered; 
	1. Add more data points in December to temperature collect and match it more closely to June to make a more meaningful analysis 
	2. Add a query for precipitation as no one would like to surf when it's raining and this would reduce the number of customers to the shop
	
   
   
