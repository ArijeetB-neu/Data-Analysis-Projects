# UdacityProject_Communicate Data Findings
## Udacity Data Analytics Nanodegree P5 - Communicate Data Findings (Ford GoBike Data)

### Data Source - (https://www.fordgobike.com/system-data)

### Overview
The data consist of about 3.3M bike rides from FY2017 to April, 2019. The attributes include the trip start/end time, start/end station, duration in seconds as well as additional information such as user type, gender, and birth date. Ages in dataset from 18 to 56 takes 95% of the users in dataset. There were users more than 100 years old. So, we removed users more than 60 years old. I generated new fields such as age group, added several tie related features in order to make grouping and analyze the data. Also, I decided to focus on San Francisco area alone since change is demographics can cause certain fluctuations in our analysis which any additional features might not justify.

### Conclusion
- Of the 3.3 million rides. 20 to 40 years old people took more than 70% share of bike rides, with dominance of 30-40 years old users accounting for about 40% of all bike rides.
- Male took around %76 of all bike rides, and female took around %24 of them.
- More focus was given on trip duration since it is closely linked to the bike share company’s revenue.
- In San Francisco Bay Area weather does not have a big impact on the trip duration. But user type seems to have a significant impact on the trip duration. With subscribers tending to rent the bikes for longer trips. So since subscription based users represent a very small portion of the bike share, I think the company should promote its subscription based user model more.
