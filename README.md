# Team_3_Project_1
Github for Team_3
Analysis

---
We used a csv dataset from Bureau of Transportation Statistics (bts.gov) to investigate how weather impacted the arrival flights delays from 2003 to 2022 in the US. 

Hypothesis 1:
Recent weather changes have caused an increase in the number of delays of arrival flights in all regions across the US.
Insights:
Delays for all reasons are same or lower vs prior years
Weather delays in aggregate have decreased in all US regions (33-58%)

Hypothesis 2:
The West and East Coast regions have experienced the highest increase in delayed flights.
INsights:
Based on % delays due to weather, delays have decreased back to the rate seen in 2018 (~3.45%)
Total number of delayed flights due to weather is less than in 2018 (11.5K vs 27.1K)

Hypothesis 3:
Of the top 5 airlines in the US, American Airlines experienced the most delays, cancellations and diversions.
Insights:
Southwest has highest number of delays for any reason
SkyWest has the highest number of delays due to weather
Delta most frequently has weather delays (most months)
American Airlines has weather delays in the highest number of airports

THe team reduced the scope from our initial questions to investigate all flights (arriving and departing), motnhs with the most delays and the customer satisfaction data.  The decision to reduce scope was based on the size of the arriving flights dataset (over 300,000 rows), time issues for collecting and analyzing the satisfaction data in addition to the flight data, and the time considerations to code the primary flight delay analysis. Scope reduced from 20 years to 5 years, weather impact (number, %, delays per year and month, and time of delays) reduced to number and % only.  Team added regions for analysis to crossreference with airports after the primary code was written in Pandas for airport data.  This allowed for a more robust analysis, but took additional time since it was not merged with the inital dataset when coding began.

Additional analyses can be conducted to investigate the impact of weather on the delays of arriving flights in the US.

=======

Team Members:  Calogera McCormick, Jamie Cid, Minta Burke, Sana Azubzai, Tawn Scotton
