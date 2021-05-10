# Activator - simple high-impedance buffer for passive instruments

## Introduction

This circuit allows for impedance matching between instruments with passive pickups and amplifiers (also sound cards, mixing boards,...) that only have low impedance inputs. 

Low impedance input amplifiers degrade the sound of passive instruments and lower effectiveness of their volume and tone controls. Without the high impedance input (sometimes called High-Z input) the instrument will also lose its high frequency range.

The __Activator__ is based on a circuit called a __"buffer"__ - a device that has a high enough input impedance (typically 500 KOhm or more) and low enough output impedance (order of single Ohms) that will match well a typical low impedance amplifier with its input impedance situated around 1 K to 10 K range.

To illustrate

["Guitar" -  high impedance output] -> [high impedance input  - "Activator" - low impedance output] -> [low impedance input  -  "Amplifier"] 

Just for fun, I'm using here old outdated (you may call it "vintage") and fairly low spec germanium transistors but these work fairly well. I have a ton of germanium transistors from ex-URSS so why not use them! The circuit will work with modern transistors with litlle to no modifications. While we're here showeling electrons right and left, why not throw in some aplification and a volume control too, this can be useful in some cases, like where you only have a line input but cannot drive it with a normal signal level available from your instrument. 

## Theory

Most modern circuits where a high input impedance is required, use the field effect transistors (FET) wich allow simple high impedance designs very easily, FETs themselves having "naturally" a high impedance inputs. This however isn't the case for vintage germanium Bipolar Junction Transistors (BJTs), or modern silicon BJTs either by the way. When using those, some schematics tricks are required. 

In the olden days where FETs weren't common and cheap record players were often built around high-impedance ceramic "crystal" pickup heads, such circuits could be often found, and I "stole" mine from one old schematics file. It's almost exactly the input stage of a 60's record player with very few modifications. 

Electronic theory would call it an "amplifier with bootstraped bias network", a nice explanation on how this input impedance increase is achieved can be found here: https://electronics.stackexchange.com/questions/268944/effect-of-bootstrapping-in-amplifier-circuit 
