# SprinkerOptimization

## Cow Detection in Soaker Area:

### Background: 
In dairy farms, cows are cooled on hot days by a system called "evaporative cooling", which is the process of spraying water on the most heat-producing areas of the body and letting the evaporating water reduce the temperature of the surface it's on. This is the same principle as how you feel cold when you first get out of a pool. Diamond J Dairy operates a system of equally spaced sprinklers on one side of the fence that all turn on at the same time and spray the respective adjacent area, which is about a cow's width. The cows' food is positioned on the other side of the sprinklers so that when they eat, their bodies are right under the spraying water. Conserving water is important to all farmers, especially in drought-prone states like California. The soaker line is automated from a central thermometer and is activated based on outside temperature. When the weather triggers the water line to be activated, the sprinklers on the soaker line cool groups of 140-160 cows at a time for 1 minute on and 4-10 minutes off (based on variations in high temperature).

### Problem(s):
When the water turns on, not all sprinklerss have a cow in their respective soaking area, resulting in significant water waste. When there is no animal in reach of the soaker the water could be conserved.

### Objectives:
The final goal is a system that would detect if a cow was in position when the sprinklers were set to come on. If the cow is not in the area of reach of the water, then the water should not come on for that space, however the water should come on in other areas in the same water line where there are cows.The first step is to design a vision-based system whereby one camera is positioned to view multiple soaker areas, and software that detects whether or not there is a cow in each of them. The software will later be used to activate each soaker valve.
