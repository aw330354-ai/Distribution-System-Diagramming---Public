# Distribution-System-Diagramming---Public
This Distribution system diagramming tool is a basic diagram and simulation tool that shows a oneline diagram for each feeder, from substation to the endpoints. It shows where all of the switching devices are on the feeder, and the state of the elements (Normally Open/ Normally Closed). 
## Overview
The tool serves two main functions: To show the layout of the feeder, and how switching procedures can affect the state of the feeder. The layout shows each of the elements from the main recloser to the endpoints or any normally open points on the feeder where it is used to parallel with another feeder. By user actions, the state of the feeder can be changed, which is shown by changes in wire connections between elements, either by chnaging colour to indicate that it is now being fed from a new feeder, or indicating that it is now de-energized. 

The tool also has a number of other actions, such as an Event Log that can be used to record the switching steps that the user makes, for ease of recording switching procedures. This can be exported as a .pdf file for reference of switching steps. Additionally, the full diagram can be exported as a .png or a .pdf file.
## Introduction to the Distribution system elements
### Main Recloser, Feeder Recloser, LCB
The distribution system uses Main, feeder reclosers and LCB for switching. Each of these have a few main elements: The Circuit Breaker is used to interrupt current flow under load and fault condtions (fault analysis not possible with this tool). Isolators are used to physically break the circuit, ensuring that no current can flow under any conditions. A bypass is used to create a connection if the isolators and circuit breakers are open, if work needs to be done on the recloser without interrupting currnet flow. A ground trip is also present on the reclosers. If bypassed, this allows for paralleling of two feeders under load, using knife switches, without incorrect operation of the recloser, thinking that a ground fault has occured (NOTE: In this tool, Ground Trip may be toggled, but will not actually block the user from paralleling if they do not turn it off). 

<img width="742" height="224" alt="image" src="https://github.com/user-attachments/assets/ff056389-f5bb-45e6-bdb4-4ea35afc6c4d" />

The Main recloser is situated just after the transformer. The feeder recloser is situated at the start of each new feeder. You can change the colour of the feeder electrical connections for ease of reference. 
### LAB - Knife Switches, Load Busters

<img width="438" height="316" alt="image" src="https://github.com/user-attachments/assets/8a287f9b-acf1-4967-bbf7-0d39b77ced36" />

Knife Switches - These devices cannot be opened or closed on load. They must be de-energized from an upsteam device to be operated. Load Busters- They can be opened/closed on load. 
### Fuses, Tripsavers
Protective devices that are generally connected at T-offs. Can be opened on load.
### Load
Generally simply endpoints on a feeder.
## How to use this tool
### Moving around the canvas
To move around the canvas, hold the right mouse button and move the diagram around the canvas. Use the scroll wheel to zoom in and out of the diagram.
### System elements
<img width="1765" height="117" alt="image" src="https://github.com/user-attachments/assets/e47f5480-3f75-4fb3-8c51-928c812209ec" />




