# usb-seal


this is a usb hub made using the SL2.1s chip. <br>
 **OSHW LAB link**:   https://oshwlab.com/subhisseal/project_uqmdgjyv

<br>

## about
usb-seal is a usb hub project i made following the macondo usb hub guide. its my first time making pcb tho. it has these **connectors**: <br>

1x input usb-c port <br>
1x usb-c output <br>
3x usb-a output

## how to use??
- replicate the project(see the "how to replicate" section below)
- once you have it assembled, plug in a usb-c to usb-c cable and the other end to whatever device yyoure connecting it to
- now connect whatever devices you want to the usb hub!

## how to replicate? 
- in `src/EDA` youll fing the gerbers, CPL and BOM files. These are the files that allow you to get the PCB manufactured from JLCPCB or - any other manufacturer.
- sign up on jlcpcb, go to the place orders page and upload the gerbers file.
- configure as you like and upload the BOM and CPL files.
- add to cart and order the pcb!!




## bill of materials

also available in .xlsx format in [BOM.xlsx](https://github.com/subhaintdead/usb-seal/blob/main/BOM.xlsx)

| No. | Quantity | Comment | Designator | Footprint | Value | Manufacturer Part | Manufacturer | Supplier Part | Supplier |
|---|---|---|---|---|---|---|---|---|---|
| 1 | 8 | 1uF | C1,C2,C3,C5,C7,C9,C10,C11 | C0603 | 1uF |  |  |  |  |
| 2 | 3 | 100nF | C4,C6,C8 | C0603 | 100nF |  |  |  |  |
| 3 | 2 | 5.1K | R1,R2 | R0603 | 5.1K |  |  |  |  |
| 4 | 2 | 56K | R3,R4 | R0603 | 56K |  |  |  |  |
| 5 | 1 | SL2.1s | U1 | SSOP-16_L4.6-W2.6-P0.53-LS4.0-BL |  | SL2.1s | CoreChips | C2684433 | LCSC |
| 6 | 2 | TYPE-C 16PIN 2MD(073) | USB1,USB_IN | USB-C-SMD_TYPE-C-16PIN-2MD-073 |  | TYPE-C 16PIN 2MD(073) | SHOU HAN | C2765186 | LCSC |
| 7 | 3 | 10.0 QHHTZB6.3 | USB2,USB3,USB4 | USB-A-TH_10.0QHHTZB6.3 |  | 10.0 QHHTZB6.3 | SHOU HAN | C668591 | LCSC |

