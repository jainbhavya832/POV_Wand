# POV_Wand
Persistence of Vision Project
# POV Wand

## About this project

POV (Persistence of Vision) is a kind of optical illusion in which a visual image seems to persist even when the light from it ceases to enter our eyes. This can be used to make POV displays where we can display text, images, gifs, etc.

[Project Demo](:/ef42631c2a8f4524a4dd4e3e53ea3574)

## Components and tools

1.  (1x) Arduino Uno
2.  (20x) Red LEDs
3.  (20x) 220 $\Omega$ Resistors
4.  (1x) Perf Board
5.  (1x) Toggle Switch
6.  M-M and M-F jumper wires

### Tools

1.  Soldering iron

## Construction

1.  Take a perf board and cut it to the required size for 20 LEDs.
    
2.  Solder the LEDs in a single line with all Anode on the same side.
    
3.  Attach 220 $\Omega$ resistors beside each LED and solder them.
    
4.  Add toggle switch to turn on the display whenever the the switch is turned on.
    
5.  Solder wires to anode of each LED and common Gnd.
    
    <img src=":/293b47d487f74945a585ea3b205589ef" alt="img5.jpg" width="385" height="513" class="jop-noMdConv">
6.  Make the connections, connect wires to Arduino in the following manner.
    Pin connections:
    Top of wand
    1 -----> Digital Pin 13
    2 -----> Digital Pin 12
    3 -----> Digital Pin 11
    4 -----> Digital Pin 10
    5 -----> Digital Pin 9
    6 -----> Digital Pin 8
    7 -----> Digital Pin 7
    8 -----> Digital Pin 6
    9 -----> Digital Pin 5
    10 -----> Digital Pin 4
    11 -----> Digital Pin 3
    12 -----> Digital Pin 2
    13 -----> Digital Pin 1
    14 -----> Digital Pin 0
    15 -----> Analog Pin A5
    16 -----> Analog Pin A4
    17 -----> Analog Pin A3
    18 -----> Analog Pin A2
    19 -----> Analog Pin A1
    20 -----> Analog Pin 0
    Bottom of wand
    
7.  Upload the code and you are good to go.
    

<img src=":/58e6de162e97456ab8cd0aa1d1fb6e80" alt="img1.jpg" width="581" height="436" class="jop-noMdConv"> 

<img src=":/edd5a0cb81cf4d369120f21e58743277" alt="img4.jpg" width="581" height="775" class="jop-noMdConv">
