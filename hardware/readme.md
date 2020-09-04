# TTN-Apeldoorn P1-Node board and housing
The P1-Node is designed with reproduction in mind. Therefore the PCB was desigened using <a href="https://kicad-pcb.org/" target="_blank">KiCad</a>. In addition the PCB was designed with an introduction to SMD soldering in mind. Components are chosen to be "big" so they can be hand-soldered or using reflow techniques. The housing can be finished using basic drill techniques and some parts are 3D-printed.

## repository content
The hardware part of the repository has 3 folders:

   1. Documentation
   2. Board (esp32-p1-node-board)
   3. Housing (esp32-p1-node-housing)

### Documentation
This ![folder](documentation/ "folder") contains relevant documentation, datasheets and links to topics that are relevant for the project.

### Board (esp32-p1-node-board)
This ![folder](esp32-p1-node-board/ "folder") contains the complete PCB design and libraries for the P1-Node for <a href="https://kicad-pcb.org/" target="_blank">KiCad</a>.

### Housing (esp32-p1-node-housing)
This ![folder](esp32-p1-node-housing/ "folder") contains both the source of the 3D printed frame as well as the .stl file for printing it. Also the measures for the holes that shall be made in the ABS housing are documented here.

File            | Note
----------------|--------------------------
Venster_003.skp | Source file of the frame in <a href="https://www.sketchup.com/" target="_blank">Sketchup</a> format.
Venster_003.stl | 3D file for printing in <a href="https://en.wikipedia.org/wiki/STL_(file_format)" target="_blank">STL</a> format.

# BOM

Ref | n | Value | Footprint | Shop | Datasheet
----|---|-------|-----------|------|-------------------------------------
C1 | 1 | 10n | SMD:1206_3216 |  RS-Components  | https://nl.rs-online.com/web/p/mlccs-multilayer-ceramic-capacitors/2989220/
D1 | 1 | BAT54S | SMD:SOT-23 |  RS-Components  | https://nl.rs-online.com/web/p/rectifier-diodes-schottky-diodes/5444584/
J1 | 1 | RJ11-6 | RJ12_Amphenol_54601 |  RS-Components  | https://nl.rs-online.com/web/p/ethernet-connectors/1370999/
Q1 | 1 | BC547 (BC847) | SMD:SOT-323_SC-70 (SOT23) |  RS-Components  | https://nl.rs-online.com/web/p/bjt-bipolar-transistors/6900091/
R1,  | 1 | 10K | SMD:R_1206_3216 |  RS-Components  | https://nl.rs-online.com/web/p/surface-mount-fixed-resistors/7219908/
R2, R3, R4, R8 | 1 | 1K | SMD:R_1206_3216 |  RS-Components  | https://nl.rs-online.com/web/p/surface-mount-fixed-resistors/9013724/
R5, R6, R7 | 3 | 180 | SMD:R_1206_3216 |  RS-Components  | https://nl.rs-online.com/web/p/surface-mount-fixed-resistors/7219762/
Housing | 1 |  | Hammond 1591 ABS Enclosure, Flanged |  RS-Components  | https://nl.rs-online.com/web/p/general-purpose-enclosures/8180514/
PCB | 1 |  | Aisler, PCB & Stencil |  Aisler  | http://www.aisler.net
header | 2 | FemalePCBHeader | 1 Row Straight PCB Socket |  RS-Components  | https://nl.rs-online.com/web/p/pcb-sockets/0252399/
U1 | 1 | TTGO_LoRa32_V11 | TTGO LoRa32 |  Tinytronics  | https://www.tinytronics.nl/shop/nl/platforms/ttgo/lilygo-ttgo-lora32-868mhz-esp32
Cable | 1 | RJ11 | InLine Modularkabel RJ12, Male/Male, 6adrig, 6P6C, 1m |  Netwerkwinkel.com  | https://www.netwerkwinkel.com/Verleng--en-aansluitkabels/Telefoonkabels/RJ10---RJ11---RJ12-kabels/InLine/InLine-Modularkabel-RJ12-Male-Male-6adrig-6P6C-2m-18842-p_12802.html
PSU | 1 | 5V-miniUSB-Adapter | 5W Plug In Power Supply 5V dc, 1A |  RS-Components  | https://nl.rs-online.com/web/p/ac-dc-adapters/1217116/
miniUSB | 1 | Type B Mini USB Connector | Through Hole Mount Receptacle  |  RS-Components  | https://nl.rs-online.com/web/p/usb-connectors/6741350/


# License
The TTN-Apeldoorn P1-Node node is free soft- and hardware:
you can redistribute and/or modify it under the terms of a Creative Commons Attribution-NonCommercial 4.0 International License (http://creativecommons.org/licenses/by-nc/4.0/) by TTN-Apeldoorn (https://www.thethingsnetwork.org/community/apeldoorn/) E-mail: ttnapeldoorncoreteam@rfsee.nl

<a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/">Creative Commons Attribution-NonCommercial 4.0 International License</a>.