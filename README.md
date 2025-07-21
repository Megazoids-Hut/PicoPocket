# PicoPocket

![instructables1s](https://github.com/user-attachments/assets/68e71f5b-aba1-48d3-aa38-4c6065e3b26e)

A Pi Pico (RP2350 or RP2040) DIY handheld based on the open source PicoPad schematic.

I wanted the PicoPocket project files accessable on GitHub. The project is posted on the following sites, which will have full build instructions :  
https://www.hackster.io/megazoid/picopocket-cb00f7  
https://www.instructables.com/PicoPocket  

> YouTube Demo : https://www.youtube.com/watch?v=SRJgQwf1tYU
  
________________________________________________________________  
  
# Supplies

![github2](https://github.com/user-attachments/assets/fc845ee8-5117-49df-b2e4-5d226432800c)


1 x Waveshare 2inch LCD Display [Waveshare](https://www.waveshare.com/2inch-lcd-module.htm)  
1 x 602550 Polymer Lithium Battery [AliExpress](https://vi.aliexpress.com/item/1005006898814536.html)  
1 x Pi Pico RP2040 or RP2350 [AliExpress](https://vi.aliexpress.com/w/wholesale-Pi-Pico-rp2350.html)  
1 x Ghxamp Mini Speaker 8Ohm 1W - 34.8mm\*11.2mm\*6.0mm [AliExpress](https://vi.aliexpress.com/item/33035261832.html)  
1 x Double Row Female 2x6Pin Right Angle Pin Header [AliExpress](https://vi.aliexpress.com/item/1005001340091287.html)  
1 x G-Switch Card Slot MicroSD - GT-TF003-H0185-01 [LCSC](https://lcsc.com/product-detail/SD-Card-Memory-Card-Connector_G-Switch-GT-TF003-H0185-01_C5155563.html)  
1 x MOLEX PicoBlade(MX 1.25) - Mfr. Part #532610271 [LCSC](https://lcsc.com/product-detail/Wire-To-Board-Connector_MOLEX-532610271_C177225.html)  
9 x Buttons - hanxia HX TS5220A 160gf [LCSC](https://lcsc.com/product-detail/Tactile-Switches_hanxia-HX-TS5220A-160gf_C5340185.html)  
1 x Slide Switch - Shenzhen Kinghelm Elec KH-SS12F23-G6 [LCSC](https://lcsc.com/product-detail/Slide-Switches_Shenzhen-Kinghelm-Elec-KH-SS12F23-G6_C5274466.html)  
1 x 0603 LEDs 4 colors [AliExpress](https://vi.aliexpress.com/item/1005005431944057.html)  
2 x Schottky diode 1N5817 [AliExpress](https://vi.aliexpress.com/item/1005001835967051.html)  
1 x TP4056 - SOP8 [AliExpress](https://vi.aliexpress.com/item/1005002806456248.html)  
1 x NPN Transistor MMBT2222A [AliExpress](https://www.aliexpress.com/w/wholesale-MMBT2222A.html?)  
3 x 0805 100nF SMD Ceramic Capacitor [AliExpress](https://vi.aliexpress.com/item/1005005690917856.html)  
1 x 0805 0.4 Ohm SMD Resistor [AliExpress](https://vi.aliexpress.com/item/1005002991938153.html)  
5 x 0603 SMD Resistors x 5 values [(See Schematic)](https://github.com/Megazoids-Hut/Picopocket/blob/main/schematic/schematic_picopocket_2024-10-22.png) [Aliexpress](https://vi.aliexpress.com/item/1005006301580629.html?)  
4 x M2 x 16mm Flat Head Hex Socket Screws [Amazon](https://www.amazon.co.uk/FandWay-Countersunk-Machine-Washers-Assortment/dp/B0B7JLDV6V/?th=1)  
1 x Silicone Rubber Sheet Thickness 0.5 [AliExpress](https://vi.aliexpress.com/item/1005006921978058.html)  
1 x Clear Grass Trimmer Line [Amazon](https://www.amazon.co.uk/Oregon-69-482-CL-Round-Strimmer-Trimmers/dp/B07SQKP6B3/)  
1 x Micro SD card 32gb [Amazon](https://www.amazon.com/dp/B0C1Y87VT3?th=1)  

Other bit needed :  
Kapton tape, Hot Glue, Sand Paper  
A Soldering iron + Solder Wire 40/60 + Solder Flux + Isopropyl  

The custom PCB can be ordered from a PCB fabrication manufacturer Like JLBPCB : [Gerber File Zip](https://github.com/Megazoids-Hut/Picopocket/blob/main/gerber/gerber_pcb_pcb_picopocket-v4_2024-10-24.zip) (Use default PCB board settings. 1.6mm thickness etc. Just upload the gerber zip and order)
Design files like the STL's, gerbers, schematic, etc. can be found on the GitHub Page for this project
  
________________________________________________________________  
  
# Story

PicoPocket is a handheld device that works on either the Raspberry Pi Pico (RP2040) or Raspberry Pi Pico 2 (RP2350). It's based on the [Picopad schematic](https://github.com/Pajenicko/Picopad/blob/main/hardware/schematics/picopad-v1.0.pdf)), and operates on the [PicoLibSDK](http://www.breatharian.eu/hw/picolibsdk/index_en.html) by Miroslav Nemecek.  

Before diving in, take a look at the bill of materials and asks yourself if you really want to get involved? You need to be adept at 3d printing and finishing, and soldering 0603 sized SMD components. If all of this looks like a doddle - crack on.  

Licensing: My PCB files and STLs are released under [The Unlicense](https://unlicense.org/). Everything else retains the licenses assigned by their creators. I take no responsibility for anything. I am not linked in any way with the open-source gaming console [Picopad.](https://picopad.eu/en/)
