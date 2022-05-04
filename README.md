# Evermore-Chamber-Filter
My spin on a Nevermore Duo Chamber Filter:

![https://i.imgur.com/EaD1NIT.jpeg](https://i.imgur.com/EaD1NIT.jpeg)

Evermore is a play on words, intended to convey pseudo-immortality (when contrasted with the short but glorious life of my Nevermore :) ).

Props and special thanks to Discord User 0ndsk4#5933 for his work in developing the wickedly popular Nevermore series. Kudos, kind sir.

I run a 350 Voron v2.4 with a 650W bed heater. The Nevermore Duo (v5.v2) was my version of choice for a Filter and Chamber Air Stirring setup.

For me, with the bed heater sitting just above the dual 5015s, when positioned as originally intended, I ended up destroying 4 fans in as many months and had uber warping over time with the ABS Nevermore parts. I posit that it is simply too hot thereunder the bed/heater. So, I decided to tackle this problem via redesigning the implementation into a split context, with elongated cartridges, with the two units sitting along the sides of the bed. Hopefully this approach will serve to provide ample filtering and stirring of the chamber air while not exposing the blower motors to extreme temperatures that inevitably lead to their early demise.

There is plenty of clearance when positioned as such:

![https://i.imgur.com/ci1TwO6.jpeg](https://i.imgur.com/ci1TwO6.jpeg)

Unit Dimensions are approximately 77mmx197mmx21mm:

![https://i.imgur.com/PBGDGnb.png](https://i.imgur.com/PBGDGnb.png)
![https://i.imgur.com/DgXHlhj.jpeg](https://i.imgur.com/DgXHlhj.jpeg)
![https://i.imgur.com/EUYT1mo.png](https://i.imgur.com/EUYT1mo.png)

I am not 3D CAD skilled (read as 'I AM a hack'), so I did this all in Prusa Slicer. I've attached the project file if others wish to spin up a similar setup. The 3mf was crafted in PS 2.4.2, in case that matters…

Fan tolerances are tight, might need to file a bit on the nubbins when assembling them.?.  Being a hack, I just turned into the hulk for a sec and forced them into place - Bob's yer uncle...

## 04May22 Update

Generated gcode and then, using Voxelizer (an interesting slicer w/ a unique UI), imported the gcode and generated meshes (stl files) from same - conceptually, deslicing... (lol).  Anyways, this should ease the pain in printing these items by avoiding slicer drama when using the original .3mf project files.

Also created an UNTESTED version targeted at the Trident (for mounting under the bed on the 2020 extrusions arranged like a 'T').  This version has members that are intended to be inserted into the extrusion slots.  The motor housing should be mounted on the inside corner of the 'T' with the back slotted and affixed with a M3/tnut through either side (laterally, just behind the magnets, as on the original Nevermore).  The cartridge has members on both sides enabling use on either side of the 'T'.  Further, on the outlet end of the cartridge, on each side, blocks were added with fastener recess  provisions allowing one to affx one side of the end to the extrusion if needed (if they are not needed, one can just cut them off, if so desired).  Due to these additions, it is recommended to add support enforcers on these elements (green depicted in the following image).  If you end up employing the Trident version, please do provide feedback.

![https://i.imgur.com/dLxEBEp.png](https://i.imgur.com/dLxEBEp.png)

Enjoy.  Happy printing!

~MHz
