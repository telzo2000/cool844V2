# cool844V2 buildguide（ver.2.1対応)

※This is a translation of the Japanese version of the build guide using DeepL or Google Translater, so the wording may not be appropriate.


### <Features>
cool844V2 (ver.2.1) is a self-made keyboard designed by m.ki.
<br>
To use it in a generic case for a 60% homemade keyboard,
It is the same as the previous cool844.
It can also be used by itself without being housed in a general-purpose case,
The acrylic bottom plate and other accessories are included in the package.
Depending on the mood of the day, it can be used in a general-purpose case of your choice,
You can use it in your favorite general-purpose case or in a sealed case made of acrylic laminate, depending on your mood.
<br>

cool844V2　Acrylic laminate sealed case
![](img/img00021.jpg)
cool844V2　Optional 60% general purpose case (with wooden case)
![](img/img00022.jpg)
cool844V2　Before case storage
![](img/img00024.jpg)
NOTE <br>
The transparent switch plate used in the finished image above is the one enclosed in the luxury set.
In the basic set, the switch plate is black, giving a subdued look.
<br>
<br>
# 0　reference
cool844V2 is basically the same as cool844. If you have trouble assembling, please refer to the cool844 [Build Guide](https://github.com/telzo2000/cool844/blob/main/buildguideforcool844.md).<br>
Be sure to read the instructions before assembling.
<br>

# 1　Parts Identification
This product includes a switch plate, middle plate (2 types, 3 pieces), PCB, large bottom plate, small bottom plate (3 pieces),
1 acrylic plate for "geta" conversion,
It consists of a cable with micro USB terminal (male), 7 M2 spacers 5.5 mm, 7 M2 screws 8 mm, 3 M2 screws 4 mm, and 4 M2 screws 12 mm.。<br>
<br>
The following items are to be provided by you
44 diodes, 44 switch sockets, 1 reset switch, 1 pro micro, 2 spring pin headers (Mac Eight con through), 3 stabilizers 2U, 1 USB type C board, and your favorite keycap set.
When converting to a 60% general purpose case, 7 M2 spacers 3mm and 12 M2 screws 4mm will be required.
<br>

<br>

# 2　Soldering of diodes
On the bottom side of the PCB board (the side with "cool844V2" printed on the right corner of the board is the top side), "diode" is printed. Insert the PCB from the printed side and solder from the top side. Solder carefully in the right direction.<br>
![](img/img00003.jpg)
![](img/img00004.jpg)
<br>

# 3　Soldering of switch sockets
Socket" is printed on the underside of the PCB board. Place the switch socket so that the printing is not visible, and solder it in place. The switch socket has an orientation. If the orientation is wrong, the key switch will not turn on.
<br>
When placed in the correct orientation
![](img/img00008.jpg)
If placed in the wrong orientation ("Socket" print is visible)
![間違った向き](img/img00005.jpg)
<br>
# 4　Reset switch soldering
RESET" is printed on the underside of the PCB. Place the reset switch on the PCB and solder it from the top surface so that the printing is not visible.<br>
<br>
# ５　Soldering pro micro
Insert two spring pin headers into the underside of the PCB.
The spring headers have small holes on their sides.
The direction of the holes must be aligned.
![](img/img00027.jpg)
Insert the pro micro into the spring pin header and solder the pro micro to the spring pin header.
Note the orientation of the pro micro.<br>
![](img/img00028.jpg)
![](img/img00029.jpg)
<br>
# ６ Daughter Board Creation
Cut the supplied cable with micro USB terminal (male) to the required length.<br>
![](img/img00030.jpg)
First, cut about 19 cm from the terminal side.
After that, leave about 16 cm of black film and about 3 cm beyond that. <br>
Peel off the film of the cable divided into four colors and solder each to the terminal of the USB type C board.
Connect red to VBUS, white to D-, green to D+, and black to GND.
![](img/img00031.jpg)
![](img/img00032.jpg)
Then solder the USB type C board to the PCB. <br>
Please attach the pin header to the USB type C board side first.
Please refer to the following image.
![](img/img00033.jpg)
![](img/img00034.jpg)
![](img/img00035.jpg)
![](img/img00036.jpg)
Next, solder to the PCB side, but before that,
2 lower middle plates, large bottom plate, 1 small bottom plate
Temporarily assemble and check the soldering position of the USB type C board.
At this time, due to individual differences in the USB type C board, if the width is large and interferes under the middle plate, file both ends of the board. <br>
Please refer to the following image.

![](img/img00037.jpg)
![](img/img00038.jpg)
![](img/img00039.jpg)
![](img/img00040.jpg)
![](img/img00041.jpg)
If you can do it like the image below, please solder the PCB side.
![](img/img00026.jpg)
After soldering, remove the temporarily assembled middle plate and bottom plate.
![](img/img00042.jpg)



# 7　Attaching the stabilizer
Attach 3 stabilizers of 2U size to the top of the PCB board.<br>
![](img/img00009.jpg)
<br>

# 8 Installation on switch plate and middle plate
Mount the middle plate on the PCB, then the switch plate, in that order. <br>
Note: The image is the transparent switch plate that comes with the deluxe set.
![](img/img00043.jpg)
Remove the acrylic protective paper before use.
Since acrylic has delicate molding parts,
Be slow and gentle when removing the protective paper.
![](img/img00044.jpg)
PCBの上面にミドルプレート上１枚を重ねます。
Place one middle plate on top of the PCB.
![](img/img00046.jpg)
In addition, stack one switch plate.
![](img/img00047.jpg)
Next, use screws or spacers to secure the switch plate and middle plate.
Fixed. <br>
Insert the M2 screw 8mm from the top from the switch plate side and fix it to the PCB side with the M2 spacer.
![](img/img00048.jpg)
![](img/img00049.jpg)
<br>

# 9 Installation of key switch
Attach a key switch to each key socket. When installing, the terminal of the key switch may be bent and may not fit properly. If you cannot input, please check the terminal first. If it still doesn't work, the solder on the key socket may be peeling off. <br>
![](img/img00050.jpg)
![](img/img00051.jpg)
<br>

# 10 Installation of bottom plate and middle plate
Place the bottom two middle plates in order on the bottom of the PCB.
The image below is under the middle plate. Please peel off the protective paper.
![](img/img00052.jpg)
When stacking, arrange the cables so that the cables with USB type C terminals do not interfere.
![](img/img00053.jpg)
![](img/img00054.jpg)
Due to the accuracy of the acrylic, the thickness of the two under the middle plate is 6mm,
With a 6mm spacer, the edge of the spacer protrudes slightly. <br>
If possible, 5.5mm spacers are preferable, but 5mm is fine. For 5mm, remember to tighten the screws from the top first. <br>
Overlap the bottom plate on top of the two lower middle plates, and tighten only 3 places with 4mm M2 screws.
![](img/img00055.jpg)
![](img/img00056.jpg)
Next, stack 3 small bottom plates and tighten them with M2 screws 12mm.
![](img/img00057.jpg)
![](img/img00058.jpg)
![](img/img00059.jpg)
After this, optionally attach rubber feet to the bottom plate to prevent slippage. <br>
![](img/img00060.jpg)
<br>
# 11 Mounting the key cap
Complete with your favorite keycap. <br>
![](img/img00061.jpg)
![](img/img00062.jpg)
Note: The image above is an example of using the transparent switch plate that comes with the deluxe set.
The basic set has a black switch plate, and you can connect the pro micro from the top of the keyboard.
never see.
<br>

# 12 Firmware
You can use the same one as cool844. <br>
[REMAP](https://remap-keys.app/configure) is supported.
[REMAP](https://remap-keys.app/configure) shows it as cool844, which is fine. <br>
You can use [REMAP](https://remap-keys.app/) developed by [Yoichiro Tanaka@yoichiro](https://twitter.com/yoichiro).
<br>
<br>

**Firmware Burn**
<br>
Connect the pro micro and PC with a USB cable, and access the [REMAP](https://remap-keys.app/) site with google chrome. <br>

![](img/img00079.jpg)

Click "KEYBOARD CATALOG" in the center of the screen. <br>
When the screen changes, put "cool" in "Keyboard Name" on the upper left
Please enter and click "SEARCH" at the bottom.
<br>
Cool series keyboard will appear.
![](img/img00080.jpg)
From this list, select the appropriate keyboard and click on it.
<br>
For example, if it is cool844, it will change to the following screen.
Then click the "FIRMWARE" tab,
![](img/img00081.jpg)
In this way, the hex file for via is displayed.
Click "FLASH"
![](img/img00082.jpg)
Flash Firmware will start and you can write to the pro micro.
<br>
This completes writing the firmware to the pro micro.
<br>
<br>

**Edit Key Layout**
<br>
Connect a computer running google chrome and cool847 with a USB cable. <br>
After that, access [REMAP](https://remap-keys.app/configure),


![](img/remap001.png)
Click "+KEYBOARD" in the center of the screen. <br>
<br>
![](img/remap002.png)
If the keyboard is connected to the computer, the following display will appear.
![](img/img00083.jpg)
Select cool844 and click "Connect". <br>


![](img/img00084.jpg)


Then you can edit the cool844 key layout on the REMAP site.

Thanks to REMAP, writing the firmware for your own keyboard and changing the key layout has become very easy.
<br>

# 13 Converting to 60% general-purpose case
Like the cool844, the case is based on the assumption that a GH60 series 60% keyboard case will be used.
You can find similar cases by material at Yusha Kobo, Talp Keyboard, etc. in Japan, and at Ali Expresse, etc. overseas.
Making sure the cool844V2 works for all cases is beyond personal discretion. Buyer's own responsibility, please. <br>
As of September 18, 2021, I have confirmed its use in five cases that I personally own. <br>
However, there seems to be some individual differences for each case, the height of the terminal insertion port,
The screw hole position inside the main body is slightly different. <br>
In that case, please reduce the fixing position with the screw of the geta and correct the height at which the USB type C board is installed. <br>
Alternatively, it will be handled individually, such as by expanding the screw hole. <br>
In the following conversion example, we did not expand the screw holes and reduced the number of fixing screws, but there was no problem in use.

## Conversion example 1 Wooden case (purchased at Talp Keyboard)　
![](img/img00063.jpg)
![](img/img00067.jpg)
![](img/img00068.jpg)
## Conversion example 2 Plastic case (purchased at Yusha Kobo)
![](img/img00064.jpg)
![](img/img00065.jpg)
![](img/img00066.jpg)
## Conversion example 3 TOFU case (purchased at Yusha Kobo)
![](img/img00069.jpg)
![](img/img00070.jpg)
![](img/img00072.jpg)

## Conversion example 4 MelGeek Mojo60 case (purchased from Talp Keyboard)
![](img/img00077.jpg)
![](img/img00078.jpg)

## Conversion example 4 Light Edge case (purchased from Talp Keyboard)
![](img/img00075.jpg)
![](img/img00076.jpg)
## How to convert
In seven screw holes of the acrylic plate named geta
Fix M2 spacer 3mm with M2 screw 4mm. <br>
Please refer to the image below for the location.
![](img/img00073.jpg)
After this, put the geta in the general-purpose case and fix it with M2 screws 3mm. <br>
Before that, once cool844V2 loosen the screw on its top and separate it into upper and lower parts. <br>
The top consists of a switch plate, a middle plate, and a PCB. Align the top with the geta you made earlier.
This work is to check if the cable with USB type C terminal crawling on the bottom of the PCB does not interfere with the fixation of the geta.
Adjust the routing of the cables if they are in the way.
Also, if the cable and switch socket overlap, there is a problem that the geta cannot be fixed well.
When routing the cable, be careful not to overload the terminal of the pro micro and break it.
<br>
Once you have confirmed that there is no problem with the fitting of the geta, remove the geta once, put it back in the general-purpose case, and fix it with screws. <br>
![](img/img00074.jpg)
After fixing the screws, place the upper part on the general-purpose case and fix it with the 7 screws on the upper part.
<br>Completed. <br>
![](img/img00065.jpg)

# 14 About LEDs
Optionally, you can attach an LED to make it glow. <br>
The cool844V2 is
Compatible with LED tape (full color serial LED tape) or SK6812MINI-E. <br>
If you are not confident about soldering, we recommend LED tape. <br>
There are GND, VCC, and LED terminals for mounting the LED tape in the center on the back of the PCB.
Solder the LED tape so that it connects the terminal of the tape to the terminal of the tape. <br>
For the SK6812MINI-E, place the required number of 10 in the square frame that spreads left and right from the center and solder each. <br>
When soldering the SK6812MINI-E, please keep the temperature of the soldering iron at about 220°C. High temperatures may cause damage. <br>
Mounting the LED will not work unless the acrylic laminated sealed case (standalone version) or the 60% universal case is transparent. <br>