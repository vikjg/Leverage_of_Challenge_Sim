# Leverage_of_Challenge_Sim

With the advent of ABS in the minor leagues, let's assume close calls were challenged in the MLB this past year. 
Goal is to take called strike threes that are on edge of plate, assign challenge successes or failures, and calculate the resulting WPA swing from initial call to new game state. 
Serves as a rough proof of concept for assigning a value to a challenge.
Next steps to mess with: 
- apply Leverage Index normalization. 
- test expected outcome of overturned-challenge at bat, currently only using WPA of new count and situation. 