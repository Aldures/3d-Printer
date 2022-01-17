# my Tronxy X5SA Pro

The x5sa pro is a really cheap core-xy 3d printer which is really not that bad on its own. This printer can be improved by changing some parts that were included with the kit. Most parts are clones such as the print head and extruder. This was done to reduce the overall cost of the printer. I really like how they made their linear rails however it makes it more diffcult to use Voron or RatRig print heads without some design changes which most people cannot do on their own.

There are many things which need to be upraded in order to make this a better printer. I will list all changes I have made to my printer as well as all cad/stl files I made to improve printing.

|Problem Areas                                                                                      |
|---------------------------------------------------------------------------------------------------|
|clone extruder|
|clone hot end|
|24v print bed|
|no removable print surface|
|inducter auto leveling|
|not real linear rails|
|cannot drive more than 4 motors main printer board|
|raspberry pi 4 - needed for klipper |
|cheap power supply|
|mosfets/solid state switches are needed for saftey and boards protection|
|frame re-inforcements are needed to dull vibrations|
|electrical box is not bad, but power supply and computer shouldn't be in same box|
|din rails are needed to hang all electronics unders the frame|
|legs are needed to increase the height of the frame so you can hide electronics under frame|
|skirt is needed to make things pretty|
|bottom panel to hang eletronics from|
|no enclosure|


# Mods
extra parts needed to improve your printer

## Electronics
| Qte | Parts                                         |      Overview                                                                       |
|-----|-----------------------------------------------|-------------------------------------------------------------------------------------|
|1| btt octopus v1.1 | You need a board with no less than 5 drivers. You need atleast 2 drivers for Z-axis|
|1| tmc2209 drivers | I like the ability to use sensorless endstops. |
|1| 24v Power supply | The power supply shipped with the X5SA Pro is not really good. |
|1| Raspberry Pi 4 | This is used for Klipper |


## Print head / Extruder
| Qte | Parts                                         |      Overview                                                                       |
|-----|-----------------------------------------------|-------------------------------------------------------------------------------------|
|1| bondtech bmg extruder | I like non cloned extruders, they function better |
|1| phaetus bms print head | any hot end can be used however I tried this one and was impressed |
|1| solid state switch for hotend heater ||
|1| bltouch v3.1 | I do not like intductive probes. This gives you the choice of using any print surface. |


## Print Bed
| Qte | Parts                                         |      Overview                                                                       |
|-----|-----------------------------------------------|-------------------------------------------------------------------------------------|
|1| 8mm mic6 Aluminum 330mm x 330mm print bed | The stock print bed on the X5SA is really thin and mine was not really flat. |
|1| 310mm x 310mm magnetic print surface | I like flexible steel PEI print surfaces |
|1| 110v 750w 310mmx310mm silicone heat pad | Since I needed a new heater for print bed I decided to get something that heats fast.|
|1| solid state switch for 110v heat pad||
|3| 450mm mgn12c linear rails | I am using the RATRIG trident configuration. It's overkill, but very sweet.|

---------------------------------------------------------------------------------------------------------------------------------------------
---------------------------------------------------------------------------------------------------------------------------------------------






