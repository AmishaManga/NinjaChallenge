## NinjaChallenge

### Problem Description:

An attacker threw a shuriken (ninja throwing star) at some people in the village.

Police were unable to recover the weapon, but they happened to have a 24 GHz CW radar pointing in the direction of the attacker, and they managed to capture some mixed-down IF data from a single channel, with a sample rate of 10 kHz. 

From the spectrogram, it looks like we may be able to gain some information about the shuriken that was thrown!
Police have confiscated the shuriken of all the known ninjas in the village area, and given us a schematic (ShurikenSchematic.png) with their shape and size. 

Can you use this along with the radar data to identify which suspect attacked the village?
Or even better, provide some source code that we can use to identify any shuriken from radar data, in case they attack the village again?

### Solution: 

**Suspect #2**

The source code lives in MicroDopplerSignatureOfShuriken.m (matlab 2021a). Contact me for Radar Data in order to run it. 

### Why Suspect 2?
* The micro-doppler spectrogram image labelled SpectrogramOfMysteryShuriken tells us that there are 3 blades. 
* And also that the blades are asymmetrical. 
* The calculations done in the excel spreadsheet labeled 'BladeLengthCalculation.xlsx' tell us that the blade length is approximately 50mm.   

### References: 
Chapter 3 of The Micro-Doppler Effect in Radar, Second Edition by Victor C. Chen. Publishered by Artech House Radar Library.
The book has some matlab source code accompanying it -> Chapter 3 -> Helicopter Rotor Blades ->  MicroDopplerSignatureOfRotatingRotorBlades.m
