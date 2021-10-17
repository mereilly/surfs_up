# Surf's Up


## Overview of the Statistical Analysis:

### Background

Because of a passion for surfing, a collegue has decided she wants to move back to Hawaii and make that more accessible in her life. In fact, she feels so serious about this that she builds a proposal to start a surf and shake shop.  She was able to attract W. Avy to the table, an investor who does want to invest but based on past experience with a surf shop asks for analysis on Weather Dataset he had from the area of the proposal before committing. Our collegue reached out to us to support in wow'ing the investor and proving the feasibility and potential of her plan.

### Purpose
The purpose is to provide data and  a business she really believes will be sustainable year-round and evaluate if we could expand to other islands, and how conditions would vary for bussiness.

## Results:

We received W. Avy's data on Hawaii weather collections as a sqllite file, which can be found in this repository. We were able to quickly and succinctly compare values for June and December, meaning we could do this for other months using different queires and mayde for other locations if W. Avy has other datasets for the other islands he's thinking about of if we could find one ourselves.

#### Here we just focus on Hawaii in June and in Decemeber.
Here are the basic statistics for the two months in comparison: 
*June (F°)*                  *December (F°)* 
![Screen Shot 2021-10-17 at 11 40 27 AM](https://user-images.githubusercontent.com/82982952/137634557-6a7eed0a-062a-4d32-93c8-ed8f9df84c17.png)

Let's focus on three ponts: 
The following three differences are noted between June and December temperatures:
While the June temp is hotter by a few degress, this isn't too significant to make a big difference. Meaning that probably between them for those 6 months we can tell investors that we could capitalize on people fleeing colder temps from the northern hemisphere or US mainland: that means good tourism = consistent potential revenue at least with regard to stable parameters.  
We get to this conclusion looking at either the averages or even the max temps above:
    Avgs: 
    -June: 74.9° F 
    -December: 71.0° F
    Max Temp:
    -June: 85.0° F
    -December: 83.0° F

Also worth saying, the max temps aren't excessive either, otherwise the heat would be a problem if it were consistently in the 90-100° F range. 

Most different is our basic stats is the minimum temperature, where in June (winter) it is 64.0° F, almost 10°s more than the minimmum temp recorded in December at 56° F

There is a bulleted list that addresses the three key differences in weather between June and December. (6 pt)

## Summary:

There is a high-level summary of the results and there are two additional queries to perform to gather more weather data for June and December. (5 pt) 

Heat and good temp is great to consider for a surf shop, but W. Avy mentioned the last surf shop he invested in went under because it got "rained out." We'd want to go above this and also gather data on wave patterns near the specific location we are looking at to attract more of the surfer crowd and also explore the data set with more queries on the weather at large. 

Also, as noted above, the temps for the minimum / lowest temp are what are most different between June and December. I would run queries to determine what time of the day is colder, and how long that cold temp in June lasts. 
