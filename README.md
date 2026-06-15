# Jqseph's USB Hub

This is a usb hub. It takes one Usb slot on your computer (or other device) and turns it into 4 more. requires a usb-c cable.
Made in 3 days over 6 hours during vacation

## Does not need firmware according to [this guide](https://fallout.hackclub.com/docs/guided-projects/usb-hub)

<img width="3300" height="5100" alt="ZINE USB HUB" src="https://github.com/user-attachments/assets/e75cb867-6c34-47a9-85dc-e1e7e8426400" />


[Zine.pdf](https://github.com/user-attachments/files/28595145/585077817-e75cb867-6c34-47a9-85dc-e1e7e8426400.pdf)
[Onshape Link](https://cad.onshape.com/documents/7dec381850385a70d28e42b0/w/3f5c1213f9f020c166704397/e/de968b44981793906c8fd906?renderMode=0&uiState=6a216cce2373db4f38114b34)


---

## Assembly - 
Solder usb connectors, Capacitors, and the usb splitter chip. It's all SMD so reflow soldering is recommended. It should just work out of the box.

## Why?
i did this project to learn pcb design, and i genuinely learned so much from this project alone.

<img width="506" height="301" alt="image" src="https://github.com/user-attachments/assets/c4a17a09-e822-4661-a094-cb5ee555fbf2" />
<img width="748" height="473" alt="image" src="https://github.com/user-attachments/assets/7e141d71-11a9-4c31-ae37-23e3b247dddd" />
<img width="740" height="514" alt="image" src="https://github.com/user-attachments/assets/8cdb1c0c-a857-4c35-a87f-501ce53aaeb8" />

I don't have it yet because shipping so no assembly photos.

the guide told me to get pcb assembly, i kinda want to solder the parts bc i got a hotplate from hack club blueprint, but i suck at soldering 
so im not gonna. this means there sadly is no soldering instructions except for if you for some reason want to make this you have to look at the components on the pcb and order them
and then solder them yourself.

## Bill of Materials (BOM)

|Name           |Quantity|Designator                                          |Price |Note                 |Link                                             |
|---------------|--------|----------------------------------------------------|------|---------------------|-------------------------------------------------|
|0603 Capacitors|17      |C1,C2,C3,C4,C5,C6,C7,C8,C9,C10,C11,R1,R2,R3,R4,R5,R6|      |1µF,5.1K,100nF       |https://www.lcsc.com/product-image/C1591.html    |
|C268443 Chip   |1       |U1                                                  |0.0375|SL2.1s               |https://www.lcsc.com/product-detail/C2684433.html|
|Type-C Port    |3       |USB1,USB4,USB5                                      |0.011 |TYPE-C 16PIN 2MD(073)|https://www.lcsc.com/product-detail/C2765186.html|
|USB-A Port     |2       |USB2,USB3                                           |0.0099|10.0 QHHTZB6.3       |https://www.lcsc.com/product-detail/C668591.html |
|PCB            |1       |N/A                                                 |$4    |Download from repo   |https://jlcpcb.com                               |

I'm not gonna pretend like i didnt follow the guide to a tee, but i did make a different shape, keyring, orientation, and writing all the journals. i belive that qualifies as different cause i didn't copy and paste directly and I LEARNED STUFF


## Usage

1. plug it in to your computer
2. plug in other things you want connected into the awesome incredible usb hub of truth and justice
3. you did it :D
