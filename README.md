# BeagleBone_LCD16X2
Interfacing of normal 16x2 LCD with Beaglebone Black Using Device Tree Overlay
*********************************************************************************************************************
A diy electronics project is incomplete without a display.16x2 Lcd available in the market is the most apt as well as accessible for this task.
Interfacing 16x2 LCD with general microcontrollers(Including Arduino) is quite simple as lot of material related to this is available on the net,You just need to find the right code! ...No problems arise from uC side!

WhereAs while Interfacing LCD with Beaglebone you do need a working code along with that you have to setup the Beaglebone Pins for the task.

For configuring the GPIO pins in Output Pullup mode , go through Derek Molloy's Device Tree Overlay tutorial:http://derekmolloy.ie/gpios-on-the-beaglebone-black-using-device-tree-overlays/

Also go through the Derek Molloy's github repository for Device Tree Overlays https://github.com/derekmolloy/boneDeviceTree

After setting up the Overlays, compile the LCD code using python for printing thestring on the LCD 
