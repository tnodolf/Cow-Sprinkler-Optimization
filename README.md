# SprinkerOptimization

## Cow Detection in Soaker Area:

### Background: 
In dairy farms cows are relieved during hot days by a system of sprayed water. Diamond J Dairy Farmoperates a system of equally spaced spouts on one side of the fence that all turn on at the same time and spray the respective adjacent area, which is abouta cow width. Cows move into the sprayed area to be relieved when the water is on. Conserving water is important to all farmers. Soaker lines above the feed area on modern dairies is a primary way to cool animals. The soaker line is automated at a central spot and is activated based on outside temperature. When the weather triggers water line to be activated,the soaker linewets groups of 140-160 cows at a time for 1 minute on and 4-10 minutes off.

### Problem(s):
When the water turns on, not all soakers havea cow in the respective soaking area, resulting in significant water waste. When there is no animal in reach of the soaker the water could be conserved.

### Objectives:
The final goal is a system that would detect if a cow was in position when the water soaker was set to come on. If the cow isnot in the area of reach of the water, then the water shouldnot come on for that space, however the water shouldcome on in other areas in the same water line where there are cows.The first step is to design a vision-basedsystem whereby one camera is positioned to view multiple soaker areas, and software that detects whether or not there is a cow in each of them. The software will later be used to activate each soaker valve.
