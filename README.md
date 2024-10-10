# COLORado PXL Bar 16

## Software Versions

[V1.241009- COLORado PXL Bar 16](https://github.com/Chauvet-Pro/COLORADOPXLBAR16/blob/6d2c11078faeac670c3fb0fe28c1b19c4c4b9861/Firmware/V1.241009.zip)
- Fixed control channel range values

[V1.240830 - COLORado PXL Bar 16](https://github.com/Chauvet-Pro/COLORADOPXLBAR16/blob/0702f776a22141ea477cb06eded7a1f87d302c03/Firmware/V1.240830.zip)
- Added new PWM firmware update
- Fixed the issue with the Single Zoom

[V1.240719 - COLORado PXL Bar 16](https://github.com/Chauvet-Pro/COLORADOPXLBAR16/blob/c2d6aa5b92802effd7d762d71f7e72c9f2f99473/Firmware/V1.240719.zip)
- Fixed the thermistor error issue

[V1.240219 – COLORado PXL Bar 16](https://github.com/Chauvet-Pro/COLORADOPXLBAR16/blob/b841a2638263e37844e641929df6e749c1435c1e/Firmware/V1.240219.zip)
-	Fixed IGMP subscription issue

[V1.230522 – COLORado PXL Bar 16](https://github.com/Chauvet-Pro/COLORADOPXLBAR16/blob/b841a2638263e37844e641929df6e749c1435c1e/Firmware/V1.230522.zip)
-	Fixed pixel color calibration resetting with Factory Reset

[V1.230321 – COLORado PXL Bar 16](https://github.com/Chauvet-Pro/COLORADOPXLBAR16/blob/b841a2638263e37844e641929df6e749c1435c1e/Firmware/V1.230321.zip)
-	Fixed dimming issues and spelling errors

[V1.220627 – COLORado PXL Bar 16](https://github.com/Chauvet-Pro/COLORADOPXLBAR16/blob/b841a2638263e37844e641929df6e749c1435c1e/Firmware/V1.220627.zip)
-	Fixed issue with Red Shift and Web server display message

[V1.220411 – COLORado PXL Bar 16](https://github.com/Chauvet-Pro/COLORADOPXLBAR16/blob/b841a2638263e37844e641929df6e749c1435c1e/Firmware/V1.220411.zip)
-	Fixed strobe issue

[V1.211112 – COLORado PXL Bar 16](https://github.com/Chauvet-Pro/COLORADOPXLBAR16/blob/b841a2638263e37844e641929df6e749c1435c1e/Firmware/V1.211112.zip)
-	Improved the sensitivity for temperature changes for better control

[V1.211006 – COLORado PXL Bar 16](https://github.com/Chauvet-Pro/COLORADOPXLBAR16/blob/b841a2638263e37844e641929df6e749c1435c1e/Firmware/V1.211006.zip)
-	Released software version

&nbsp;

## USB Software Update Instructions
1. Power on the product and plug the flash drive into the USB port.
2.	Once the flash drive has been detected, the message "**USB UPDATE**" will be displayed. Select **<YES>**.  
3.	The next screen will show the software versions available for this fixture on the USB drive.  For multiple versions of the software for the same fixture, use **<UP>** or **<DOWN>** to select the desired version.  Press **<ENTER>**.
4.	The “**USB UPDATE**” screen will re-appear.  Press **<YES>**.
5.	The upgrade will start. **DO NOT** turn off the power or disconnect the USB while the USB LED is still blinking during the process. The screen display will read: “**USB Update Wait**”. USB update can take several minutes to complete.
   >When the USB firmware is done uploading, in some fixtures the display will change to: “**DO NOT UNPLUG, UPDATING**”.
6.	When the update is completed, the fixture will automatically reboot.
7.	Go to Fixture Information on the product’s menu map and confirm the firmware revision.
8.	When the boot-up process is finished, restart the product.

### Special Notes
* Place the .chl file in the root directory of the USB drive.
* The product's USB port supports up to 32GB capacity and only works with FAT32 file format.
* It is possible to update multiple units with the USB if they are daisy chained via DMX.
* Turning off the power or removing the USB while still blinking during the update will cause partial or total firmware failure in the targeted fixture(s). If this occurs, the user will need the UPLOAD 08 device to fix this.
