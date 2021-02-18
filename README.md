### Social Network analysis as a Risk Tool for Building Safety
The idea behind this project is that previous bad behavior is a good predictor of future bad behavior, and that network ties to bad actors will be a useful tool to categorize high risk construction permits for audit or inspection.

The Department of Buildings issues approximately 300,000 building permits a year, a number of these permits will result in illegal work. Each construction permit contains the names of the actors working on the project. These include the owner, architect or engineer, contractor and the filing representative. Each permit produces a network of actors working at a building in New York City.

A bad actor list is generated based on previous illegal work or dispositions. 

This project had two steps. 1) Among the list of known bad actors, creating a "bad actor" ranking system. 2) Rank the most recent permits as high or low risk based on the "badness" rank of the actors working on the project (see below measures)

### Risk Tool Measures: 
#### Transactional
Total number of ties: Total number of ties each actor has in the network \
Total number of bad ties: Total number of bad ties to each actor (are they working on a project with a known bad actor?) \
Bad tie density = Total number of bad ties/Total number of ties 

#### Bad Actor Work Relationships 
Total number of unique ties: Total number of ties each actor has in the network \
Total number of unique bad ties: Total number of bad ties to each actor \
Bad unique tie density = Total number of unique bad ties/Total number of unique ties 

#### Influence and power in the industry 
Betweeness Centrality: Measure of actors who are powerful in the industry by brokering relationships between groups \
Total Number of BINs: Total number of buildings they worked on \
Unique Number of BINs: Unique number of buildings they worked on, each BIN is counted only once 

#### Membership in “bad” community (community detection analysis) 
Community Membership: The name of the community in which they belong \
Community Bad Density Unique = # Bad Unique in Community/# Number Unique in Community

### Badness Risk Calculation
Three of the above measures were used to rank the level of "badness" among the bad actors (about 500 bad actors in all): previous DOB violations, total unique bad tie density and betweeness centrality. Total uniqe bad tie density is a measure of how many ties they have in their network that are bad, i.e. on average the people they do business with tend to engage in illegal activity. Betwneeness centrality is a measure of the actor as a key person in the network who is conducting bad behavior among several groups. The actor is therfore central in dissemnating bad behavior in the industry.


















