# DC-to-DC-Converter
## Overview
This is a DC-to-DC Converter Design for Walla Walla University's Power Electronics Course. The goal of this project was to create a 12-15V to 5V DC converter in order to be able to charge a phone from a voltage source ranging from 12-15V.
## Design Specifications
1. Takes a 12-15V input and outputs a 5V
2. Is able to charge both Android Devices as well as Iphones
3. []


## Schematic
![Schematic Version2](/images/schematicV2.png)
Shown above is ou final schematic for our project. Our input is delived from a 12-15V source to the screw terminal. For our final version we used a set of 8 AA batteries to generate 12V into the screw terminal. The input then passes a ferrite bead in order to limit noise coming from the input. It then passes into a LM25765-5 Buck Converter. The LM25765 works as a simple switcher in conjuction with our inductor and schottky diode in order to create an average duty cyle of 5V. This 5V is then passed into a voltage divider, to get 2 and 2.5 V in order to use the data pins on the USB output. From the USB 5V are generated with a current ranging from about 20-30mA.
## PCB Design
![PCB Version2](/images/PCBV2.png)
Shown above is the PCB design. For our design we choose to make all our components through hole in order to make building, testing, and debugging easily approachable.
## Simulations
![LTSpiceSim](/images/LTSpiceSim.png)
Shown above is the simulation of the voltage response of our DC-to-DC converter. 
