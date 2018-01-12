# RacecarController
Working on a supplemental controller for my racecar
I'm using a stand a lone ecu but it lacks some capeabilities that I'm wanting.  I'm going to write some basic code for a raspberry Pi that will control some additional functions.
First will be fuel pump control off of the throlle position sensor.  
1)   When at idle (throttle not being pressed), only the main pump will run but at a lower voltage to create less pump speed and pressure      as it is not necessary.  This may involve some physical wiring upgrades.
1a)  When throttle is below 45%, the main fuel pump only will run at full voltage.
1b)  When throttle is above 55%%, the main fuel pump and the supplemental fuel pump will both run with full voltage.
