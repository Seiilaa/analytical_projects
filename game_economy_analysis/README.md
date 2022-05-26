# Mobile game economy analysis

- Analyzed a mobile game (title hidden due to NDA) in-game resource economy.
- Restructured the logs data to extract valuable information about player behaviour.
- Determined the categories of the players and the level progression system in the game.
- Found the necessary amount of each resource required to progress in the game.
- Calculated relative cost of the resources using the time players need to mine the amount of resource determined in the previous step. 
- Visualized the findings, made a conclusion and recommendations for the in-game economy.
  
## Code and resources used

**Python Version:** 3.9.12\
**Packages:** pandas, numpy, scipy, statistics, matplotlib, seaborn

## Data description
Dataset contains user logs with information when the player receives a certain amount of any in-game resource.

- level - player level
- user_tier - тир игрplayer tier. This parameter is calculated using level — for each 20 levels players get 1 tier. \
Thus, players at level 1-20 are considered to be tier 1 users, 21-40 — tier 2 etc. The max tier is 5.
- gain_count - the amount of resource received by the user.
- resource_tier - tier of the resource. Most resources received by the player are of the same tier as the player's tier
- resource - resource name. Resources of the same type but different tires will have unique names.\
    For example, wls2_resource_primary_wood_1 and wls2_resource_primary_wood_2 are two tree type resources of different tires. Thus they will have different names.
- playtime - how much time the player spent in the game in seconds since the beginning of the first session.

## Task description

Using player resource mining logs, estimate the relative cost of resources compared to each other.\
Summarize all findings in a table with the cost of resources relative to one selected as a benchmark.\
These findings will be used by the game designers to recalculate the in-game economy.

## Data cleaning
- Checked the data for duplicates, anomalies and missing values.
- Made sure that the data is ready for further analysis.

## Data analysis
- Initial data exploration, .info(), .describe(), get the number of unique players. 
- Explored the players data:
  - Distribution based on user tiers, playtime
  - Calculated the time necessary for the players to upgrade their user_tier
- Explored resources:
  - Checked unique resources, renamed them for better readability.
  - Compared the resources by the number of logs
  - Studied how many resources usually drop per log
  - Examined the time interval when the resource remains relevant.
  - Checked how many resources are collected by the players on average
  - Calculated the number of units of each resource that players mine before they switch to a higher tier.
  - Estimated the relative "cost" of the resources using time that players spent mining them.
- Visualized the final resource cost table

## Results
- Found out that the players need to mine approximately 300+-50 resources before they switch to a similar resource of a higher tier.
- The fasterst to lose it's relevancy resource is fiber_1. I used it as a measure unit to calculate the relative cost of other resources.
- The dataset contained three atypical resources: these resources had different tier structure and players in general collected less units of these resources.
- The final relative cost table was sorted and visualized.
