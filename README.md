# Jqseph's USB Hub

## Does not need firmware or cad according to the guide.

<img width="3300" height="5100" alt="ZINE USB HUB" src="https://github.com/user-attachments/assets/e75cb867-6c34-47a9-85dc-e1e7e8426400" />


I built it in 3 days. it is almost an exact ripoff of the guide but thats ok. it's in easyEDA so sorry kicad users.
if u somehow don't know what a usb hub is it basically takes 1 usb port and turns it into 4. i chose this because it had a guide and i need to learn pcb design.

it uses usb 2.0 like the guide because it's easier to implement by a longshot. it passed erc and drc so it's good.

<img width="748" height="473" alt="image" src="https://github.com/user-attachments/assets/7e141d71-11a9-4c31-ae37-23e3b247dddd" />
<img width="740" height="514" alt="image" src="https://github.com/user-attachments/assets/8cdb1c0c-a857-4c35-a87f-501ce53aaeb8" />

I don't have it yet because shipping so no assembly photos.

the guide told me to get pcb assembly, i kinda want to solder the parts bc i got a hotplate from hack club blueprint, but i suck at soldering 
so im not gonna. this means there sadly is no soldering instructions except for if you for some reason want to make this you have to look at the components on the pcb and order them
and then solder them yourself.

## Bill of Materials (BOM)

| # | Qty | Description | Designators | Footprint | Value | Manufacturer Part | Manufacturer | Supplier Part | Supplier | JLCPCB Price |
|---|-----|-------------|-------------|-----------|-------|-------------------|--------------|---------------|----------|--------------|
| 1 | 8 | 1µF Capacitor | C1, C2, C3, C4, C5, C7, C9, C11 | C0603 | 1µF | — | — | — | — | — |
| 2 | 3 | 100nF Capacitor | C6, C8, C10 | C0603 | 100nF | — | — | — | — | — |
| 3 | 3 | USB-C Receptacle (16-pin) | Plugin, USB4, USB5 | USB-C-SMD_TYPE-C-6PIN-2MD-073 | — | TYPE-C 16PIN 2MD(073) | SHOU HAN (首韩) | [C2765186](https://www.lcsc.com/product-detail/C2765186.html) | LCSC | $0.0097 |
| 4 | 6 | 5.1KΩ Resistor | R1, R2, R3, R4, R5, R6 | R0603 | 5.1K | — | — | — | — | — |
| 5 | 1 | USB Hub Controller | U1 | SSOP-16_L4.6-W2.6-P0.53-LS4.0-BL | — | SL2.1s | CoreChips (和芯润德) | [C2684433](https://www.lcsc.com/product-detail/C2684433.html) | LCSC | $0.0343 |
| 6 | 2 | USB-A Connector (THT) | USB2, USB3 | USB-A-TH_10.0QHHTZB6.3 | — | 10.0 QHHTZB6.3 | SHOU HAN (首韩) | [C668591](https://www.lcsc.com/product-detail/C668591.html) | LCSC | $0.0098 |

I'm not gonna pretend like i didnt follow the guide to a tee, but i did make a different shape, keyring, orientation, and writing all the journals. i belive that qualifies as different cause i didn't copy and paste directly and I LEARNED STUFF


## Usage

1. plug it in to your computer
2. plug in other things you want connected to said computer
3. you did it :D
