# Flashforge-for-Cura
This profile is able to be used with the Flashforge Creator Pro The lack of heating gcodes in the start script is BY design! If you put the temps into the gcode then both will heat up everytime you use the printer not just the side being used.

PLEASE NOTE AS OF RIGHT NOW THE MAX DOESNT WORK

# What's different from Toylerrr's version?
Toylerrr's version used the wrong metadata for the X3gwriter plugin, causing it to export X3G for a Makerbot Replicator 1.
# What'd you change?
Quite literally, 3 characters.

> Before:
> `"machine_x3g_variant": "r1d",`

> After:
> `"machine_x3g_variant": "fcp",`
## How to install
* Install a cura plugin called [`X3GWriter`](https://marketplace.ultimaker.com/app/cura/plugins/Ghostkeeper/X3GWriter)
* Close Cura
* Download the most recent release of this profile
* Unzip the file
* Copy the 4 files to their respective folders
* Open cura, and enjoy!

# What does all of this do?
This profile interacts with the X3GWriter plugin, which is a translation software to convert from GCODE to X3G. It also puts in information about the printer like the X,Y, and Z of the bed, and that the origin is in the center.
# Recommendation
Always make sure that you have a skirt around your print because this profile doesnt have a purge of the nozzle. 
![Cura 4.6.1](https://i.imgur.com/vwvsd38.png)
Tested on Cura 4.11.0 and Sailfish `TBD`
