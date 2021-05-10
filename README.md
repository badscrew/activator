# Activator - simple high-impedance buffer for passive instruments

## Introduction

This circuit allows for impedance matching between instruments with passive pickups and amplifiers (also sound cards, mixing boards,...) that only have low impedance inputs. 

Low impedance input amplifiers degrade the sound of passive instruments and lower effectiveness of their volume and tone controls. Without the high impedance input (sometimes called High-Z input) the instrument will also lose its high frequency range.

The __Activator__ is based on a circuit called a __"buffer"__ - a device that has a high enough input impedance (typically 500 KOhm or more) and low enough output impedance (order of single Ohms) that will match well a typical low impedance amplifier with its input impedance situated around 1 K to 10 K range.

To illustrate

["Guitar" -  high impedance output] -> [high impedance input  - "Activator" - low impedance output] -> [low impedance input  -  "Amplifier"] 

Just for fun, I'm using here old outdated (you may call it "vintage") and fairly low spec germanium transistors but these work fairly well. I have a ton of germanium transistors from ex-URSS so why not use them! The circuit will work with modern transistors with litlle to no modifications. While we're here showeling electrons right and left, why not throw in some aplification and a volume control too, this can be useful in some cases, like where you only have a line input but cannot drive it with a normal signal level available from your instrument. 

## Theory

Most modern circuits where a high input impedance is required 
