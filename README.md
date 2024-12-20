﻿# Temperature Sensor
- Question: How long of a power cutoff can your refridgerator tolerate before your milk gets spoiled?
- This is the exact question we are trying to answer using the program written in this repository.
- According to the American Dairy Association of the Northeast, ideal temperature for Storing Milk is 30-40 degrees F.
- The idea is to use a Temparature sensor and measure the slope of increase in Temperature for 15 minutes. 
- Then we extrapolate the curve to find out the amount of time after which fridge temperature crosses 40 degrees Fahrenheit.

## Newton's Law of Cooling
- According to Newton's Law of Cooling, for an object with Temperature cooler than the ambient/enviornment/room temperature the change in Temperature as a function of time can be given by:

```math
T(t) = T_a - Ce^{-kt}
```
- where Ta is the ambient/room temperature
- C, k and e are constants and
- t is time
