# ProbeMaster Breakout Board 
This board is to make my life easier when measuring/probing unknown hardware.  Often I want to hook up a logic probe or DMM in to the crcuit and manipulate the outputs- hence the dipswitches so I can turn things on or off

Buy a DIY kit in my store here: https://store.mkme.org/?product_cat=custom

<p align="center">
<br>
 <img src="https://github.com/MKme/probemaster/blob/main/photos/3D.PNG" width="700"/>
 <br>

<br>
<br>
🐦 <a href="https://twitter.com/mkmeorg">Twitter</a>
| 📺 <a href="https://www.youtube.com/mkmeorg">YouTube</a>
| 🌍 <a href="http://www.mkme.org">mkme.org</a><br>
Support this project and become a patron on <a href="http://mkme.org/patreon">Eric's Patreon</a>.<br>
Website, Forum and store are at http://mkme.org <br>
Chat with Me: <a href="https://discord.gg/j9S4Fgv">Discord</a></b>
</p>




The protoyping area will allow me to add any components INSIDE the working crcuit while measuring on the DUT- Handy eh?

You can add capacitance, resistance, switches LED indicators easily by putting them right in series or parell with the circuit

While the DIPswitch conenctions allow probing the lower connections are not joined in the center- this allows the user to either connect them or conenct with more components as mentioned above

<img src="https://github.com/MKme/probemaster/blob/main/photos/Schematic%20Fig.PNG" width="500"/>

Forum Thread HERE - https://forum.mkme.org 

My Videos HERE: https://www.youtube.com/mkmeorg


# Hardware:

### Parts can be found in the KiCad BOM 

Buy the PCB in my store: https://store.mkme.org/?product_cat=custom

Buy DIP switches on Amazon: https://amzn.to/2UbDWsz

Header pins colored : https://amzn.to/3euvvPY

Header pins black only https://amzn.to/3z3T4Xy 

<img src="https://github.com/MKme/probemaster/blob/main/photos/PCB%20Fig.PNG" width="700"/>

# Project:

###  Base/Enclosure

While the initial design is off at PCBWay for board fab I decided to make a base to set the unit on.  

To do this I used Kicad Plot and exported the Drill file as SVG see file ProbeMaster-PTH-drl_map:

<img src="https://github.com/MKme/probemaster/blob/main/PCB/ProbeMaster/gerbers/svgs/ProbeMaster-PTH-drl_map.svg" width="500"/>

I pulled this in to Inkscape and just traced the outline and plotted 4 3mm mounting holes aligning them with the PCB holes

<img src="https://github.com/MKme/probemaster/blob/main/PCB/ProbeMaster/gerbers/svgs/Erics%20ottom%20plate%20final%20v0.1.svg" width="300"/>

This I can use easily in my K40 laser cutter to cut a nice acrylic base.  

