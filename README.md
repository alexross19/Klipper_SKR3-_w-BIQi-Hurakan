My SKR/Klipper build is a non-standard build
The original was a Trony Xy-2 Pro V3 MCU  printer from Dec 2019



https://www.tronxy3d.com/collections/xy-2-pro-series/products/tronxy-xy-2-pro-3-structure-3d-printer-255mm-255mm-260mm

Features
TRONXY Y-2 Pro
Print Size 255X 255X260MM,
Prusa I3 Structure,
Automatic Leveling,
Quick Installation of Beginner 3D Printer,
Resume Printing Function After Power Off,
Intelligent Broken Material Detection Function
Slicing software: 	Tronxy slicer
File format: 		G-Code
Operation software:  	Repetier-Host/Cura
Operation system: 	Windows
Connection: 		USB cable, TF card
Power input: 		110V/220V
Power output： 	24V/360W
Machine weight: 	8.5kg
Package weight: 	12kg


Print size: 	
Print Area:			255×255×260mm(10.1×10.1×10.24in)
Print speed: 			20-100mm/s (60mm/s is preferred)
Print thickness: 		0.1-0.3mm (Optional)
Positioning accuracy: 		X/Y: S0.00625mm,  Z：S0.00125mm
Nozzle size: 			0.4 mm
Materials support:		1.75mm, PLA/ABS/PETG
Nozzle temp: 			Max 275℃ (Max 527°F)
Heat bed temp: 		Max 120℃ (Max 248°F)
Machine size:			478×455×520mm （18.82×17.92×20.48 in）
Packing size: 			520x290x250mm
Package weight:		12KG
Environmental temperature:	8°C-40°C(46.4°F-104°F)
Environmental humidity:	20-80%
Power Input:	 		110V/220V
Power Output: 		24V 360W


Why the upgrades:
Out of the Box, everything works. But the print quality was not excellent &  the original controller worked but had a LOT of glitches it made sense to upgrade:

All the Glitches tracked back to:
Cheap, dangerous power supply,
Odd Trony  MCU Firmware( although it was based on a branch of Marlin)  
Magnetic proximity centers 
Cheap filament run-out sensor
No web-based management
Cheap end-stop switches

What I have replaced/added:

MCU  BTT SMR3
Steppers:  BTT EX 29022
Display:  BTT FTF35-v3  ** Dec 2023 Firmware, Jan 2024 Firware does not work
Power supply New Power supply
Power supply ICE outlet. The original one was Dangerous with exposed 120V wire!! 
Bed Probe: BTT MicroProb
Filament runout Detector:  BTT Smart Filament Runout Sensor V2
Pi 3B  - to run Klipper & provide a web interface
End stops 
All fans!
Cables  stepping motor cable
New Endstop cables
New Power supply cables 
New Cable Power  Jack
I removed the Trony  Ribin motor to PCB due to ground issues. 
Added LED lights
2 USB webcams

 Trony parts that are left ( for the moment) 
2020  frame,
X,Y,Z stepping motors
Z lead screw system
X&Y Belts system
Bed & Heater
HotEnd 
Y gantry system.


Software: 
Pi Mainsail Image w/ updates
BTT Hurakan MainSail/Klipper configs Modded for the SKR3 Board & Accessories
Hurakan MainSail/Klipper  Skin that I have modded for the SKR3

At this point, the Printer is 90%  BTT then Trony!

Now the Trony BED is a bit bigger then BTT Hurakan. But just to get it up and running that dose not matter.

Once it's running, we can optimize it to a new version with just a configuration file update.
