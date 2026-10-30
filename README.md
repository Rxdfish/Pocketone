# Pocketone
A compact midi board that fits into any pocket and still has a lot of features 
![Lunarbie](IMAGES/MIDI2.PNG)


Inspiration came from this Repo with brilliant tutorial: [have a look]([https://github.com/SharKingStudios/Starbie/tree/main](https://github.com/KaiPereira/MIDI-Keypad/blob/master/README.md))

# What is this

Pocketone is a project, made for the [Half life](https://halflife.hackclub.com) by Hackclub programm. It is an MIDI keyboard with compact design and lots of features. It can be used to create music inputs for a computer or laptop.

The Board features a Microcontroller, display, buttons, and capacitive sensors in a compact PCB design. It is USB powered and easy to build.

# Project status

The project is half finished but more features and maybe tutorial will come soon.

# Motivation

The main motivation is of course the Half Life (LINK) program by hackclub. It was designed in week three of the project where the task was to create a music PCB. Other than that, I really wanted to design a PCB for a long time now and it definitely won’t be my last one. It was quite som challenge to cook that midi board up and its not nearly finished but im proud of my result.

# Project journaling

Via the [Half life](https://halflife.hackclub.com) by Hackclub programm, several Journal entries have been made either in timelaps form or as written entry to track the project. 

# Assembly

![Lunarbie](IMAGES/MIDI_PCB.PNG)
The assembly should be quite beginnerfriendly. The board itself has not many part and is partly prefabricated. All remaining components are easy to be soldered by hand.

# Schematic and components

![Lunarbie](IMAGES/MIDI_SCHEMATIC.PNG)
The board is powered by the Waveshare ESP32-S3-ZERO. It provides the power and data connector with an onboard USB-receptacle. The board also features a keyboard in form of capacitive sensors and a small OLED display. Furthermore it has 3 fader sliders and 8 preassure sensor pads. Everything is made possible by an GPIO expander and a MUX.

# PCB

![Lunarbie](IMAGES/MIDI2.PNG)
The PCB is a simple 2 layer PCB. NOthing special about it 

# Firmware

Sadly there is no firmware yet.

# BOM

This is the funding BOM but there is another BOM for all parts and the PCB manufacturing, which is out of budget unfortuenately.

Item,Qty,Supplier,Cost/item,Total Cost,link
"Waveshare ESP32-S3-Zero","1","Waveshare","$5.16","$5.16","https://www.aliexpress.com/item/1005009890203011.html?spm=a2g0o.cart.0.0.5ee74ae45QOMi5&mp=1"
"MPR121","2","Realpoy Electronic","$3.46","$6.92","https://www.aliexpress.com/item/1005006960928952.html?spm=a2g0o.cart.0.0.5ee74ae45QOMi5&mp=1"
"0.96"" OLED",1,YouKeyi Store,$2.78,$2.78,https://de.aliexpress.com/item/1005006141235306.html?spm=a2g0o.cart.0.0.5ee74ae45QOMi5&mp=1&gatewayAdapt=glo2deu
MCP23017,1,Silicone Patterned Store,$5.42,$5.42,https://de.aliexpress.com/item/1005009034247985.html?spm=a2g0o.cart.0.0.5ee74ae45QOMi5&mp=1&gatewayAdapt=glo2deu
CD72HC467M96,1,EC-Buying Ali Store,$2.35,$2.35,https://de.aliexpress.com/item/1005009412625122.html?spm=a2g0o.cart.0.0.5ee74ae45QOMi5&mp=1&gatewayAdapt=glo2deu
74AHCT1G125 SOT-23-5,1,ITECH Electronic,$4.40,$4.40,https://de.aliexpress.com/item/1005005936926220.html?spm=a2g0o.cart.0.0.5ee74ae45QOMi5&mp=1&gatewayAdapt=glo2deu
SK6812 mini-E,1,Venuss 777 Store,$5.08,$5.08,https://de.aliexpress.com/item/1005007863635868.html?spm=a2g0o.cart.0.0.5ee74ae45QOMi5&mp=1&gatewayAdapt=glo2deu
Alps EC11E encoder (w. sw),1,DQLZV Official Store,$2.21,$2.21,https://de.aliexpress.com/item/1005007644083514.html?spm=a2g0o.cart.0.0.5ee74ae45QOMi5&mp=1&gatewayAdapt=glo2deu
kailh choc v1 sw,1,BQW Enterprise Store,$8.55,$8.55,https://de.aliexpress.com/item/1005006217606250.html?mp=1&gatewayAdapt=glo2deu
tactile switch 6x6,1,DNIGEF Electronices Store,$4.19,$4.19,https://de.aliexpress.com/item/1005005292705788.html?spm=a2g0o.cart.0.0.57104ae4sKWUUi&mp=1&gatewayAdapt=glo2deu
Estimated total shipping,1,,,$17.54,
