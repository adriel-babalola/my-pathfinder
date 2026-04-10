# My-pathfinder

## What is it?

its a modified version of the pathfinder starter project. i added an extra LED, an extra switch, and a buzzer. so now whenever you press a button it makes a sound.

## Why i made it

i originally wanted to make a pomodoro timer but honestly it was way too complex for where i was. i kept getting stuck on diagrams i didn't understand and i wasn't making any progress. so i thought, instead of going that deep, why not just take what i know and add something to it. i knew how the switches and LEDs worked from pathfinder already, and making a buzzer sound is literally just a digitalWrite so i added that. its my first time doing hardware so i kept it simple on purpose.

---

## Pictures

**3D Model**
<!-- Screenshot of full 3D model -->

**PCB**
<!-- Screenshot of PCB layout -->


---

## BOM

| Designator | Part | Quantity | Unit Price (USD) | Total (USD) | Supplier | Link |
|---|---|---|---|---|---|---|
| BZ1 | Passive Buzzer 9042 16ohm AC 3V/3.3V | 1 | $1.04 | $1.04 | AliExpress | [Link](https://www.aliexpress.com/item/1005008414603547.html) |
| U1 | RP2040-Zero (Raspberry Pi Pico-compatible) | 1 | $1.51 | $1.51 | AliExpress | [Link](https://www.aliexpress.com/item/1005003796360532.html) |
| SW1–SW4 | Gateron KS-9 Mechanical Switch (White) | 4 | — | $3.92 | AliExpress | [Link](https://www.aliexpress.com/item/1005007380739304.html) |
| D1–D4 | 10mm Round Top Super Bright White LED | 4 | — | $3.55 | AliExpress | [Link](https://www.aliexpress.com/item/1005007931873474.html) |
| R1–R4 | 220R Carbon Film Resistor 1/2W 5% | 4 | — | $1.04 | AliExpress | [Link](https://www.aliexpress.com/item/1005007551484723.html) |
| R5 | 100R Carbon Film Resistor 1/2W 5% | 1 | — | $0.97 | AliExpress | [Link](https://www.aliexpress.com/item/1005007551484723.html) |

**Total: $12.03**