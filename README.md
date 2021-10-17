# surfs_up
## Overview

A weather analysis of the island of Oahu that shows temperatures through out the month of June 2017 and December 2016. This is designed to help potential Shake-n-Surf investors make decisions that are based on facts.
## Results
Sqlite was used as the database engine because of it is very easy to use and appropriate for the size of the project but SQLAchemy is also used along with the engine as a layer of abstration over the sql engine used just in case this project grows bigger in size and there is a need to migrate to another database.

(note: The unit of temperature used is Fahrenheit)
**June 2017**:
- A total of 199 temperature samples were taken in June
- The minimum temperature was 71
- The maximum temperature was 83
- The median temperature was 77 
- The mean temperature was 77.2
- The standard deviation was 2.6
- The 25th percentile was 75
- The 75th percentile was 79

**December 2016**:
- A total of 200 temperature samples were taken in December
- The minimum temperature was 60 
- The maximum temperature was 78 
- The median temperature was 71 
- The mean temperature was 71.1
- The standard deviation was 3.4
- The 25th percentile was 69
- The 75th percentile  was 74

## Summary
The data above show the range of temperatures during one of the coldest months (December) and one of the warmest months (June). 
- The small values of the standard deviation of both  months show that the weather was relatively stable during those (extreme) months
- The range between the 25th and the 75th percentile for June was between **75 and 79** meaning that the temperatures for most of that month were in this range
- The range between the 25th and the 75th percentile for December was between **69 and 74** meaning that the temperatures for most of that month were in this range

Oahu's temperature is generally stable based on this analysis and generally warm, making it an ideal location for tourism. The warm weather means that ice-cream can be sold all year round and the temperature is also safe for surfing even during extreme months.