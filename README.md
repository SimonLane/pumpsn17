# Compact, Inexpensive, USB-Powered Magnetic Stirrer Device

**This page describes how to build a simple magnetic actuator for stirring the contents of a syringe. Applications are numerous, including the continuous delivery of cells and particles into droplets for single cell transcriptome profiling.**

This project is a fork of the original [DropletKitchen](https://DropletKitchen.github.io) project. Original source code of the project is provided under MIT License. The source may contain code under a different license, if this is the case it is stated in the LICENSE file.
The designs and documentation in this repository is Copyright (c) 2018 Simon Lane and made available under a [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) License.


## Introduction

![Stirrer](/images/Stirrer.JPG) ![controller](/images/controller.JPG) ![Fan](/images/Fan.JPG)

Maintaining cells and particles in a suspended state within a fluid medium is essential for efficient processes spanning academic research to industrial settings. A major problem is the sedimentation of cells and particles to the bottom of the vessel, effectively removing them from the process. For example, settling in a syringe prevents the delivery to devices for microfluidic processing. This results in a large proportion of cells and particles not entering the microfluidic device, and even over short, minute periods can deplete the delivery of cells and particles to zero. Where samples are precious and reagents are expensive methods to overcome sedimentation are needed. 
Existing approaches include costly magnetic actuators that can be cumbersome for interfacing with syringes in a standard lab. Here we present an inexpensive and easy to build device with a compact footprint that can be used to greatly improve syringe-pump driven cell and particle delivery. We repurpose a small fan with pulse width modulation (PWM) control and a built-in tachometer. A feedback loop is established using an Arduino so that the RPM can be set via a simple controller. A small screen (optional) can display the RPM. Here we attach two fans to a single controller, but potentially 4 could be added. The fan motor has a low power requirement and so the whole device can be powered over USB, either from a nearby computer or a mains powered USB adapter.
To prevent sedimentation inside a syringe a pair of two neodymium disc magnet pairs (Ø4 mm, 2 mm thick) are attached to the fan using a 3D printed push-fit adapter. Small (e.g. 7x2 mm) magnetic stirrer bars are placed with the cell and particle suspension in the barrel of the syringe and are periodically actuated as the disc magnets rotate in close proximity. This prevents the sedimentation and ensures steady-state cell and particle delivery to the microfluidic device.

## Bill of Materials

This list assumes two stirrers running from a single controller. Costs are approximate as of July 2018.

Part | Number | Product Code | Company | Cost (Aprox. GBP)
—|—|—|—|—
Fan | 2 | 108-ASB0305HP-00CP4 | Mouser | 6.44 ea.













