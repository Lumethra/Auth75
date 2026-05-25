# Auth 75

## What is this? 

This is a 75% keyboard with a fingerprint sensor. What? A fingerprint sensor in a keyboard? Yes, you've heard it right! This keyboard includes a working fingerprint sensor. But how does it work? Aren't fingerprint sensors tied to motherboards? Continue reading, to get an answer to this question. 

### Features: 
  - Keycool84 layout (modified)
  - Raspberry Pi Pico 2W
    - ZMK (not tested)
    - LiPo battery
    - Battery charger
  - Rotary Encoder Switch (EC11)
  - USB Hub (SL2.1)
    - 1 USB-C upstream
    - 2 USB-C downstreams
    - 1 notched FPC-connector (fingerprint sensor)
    - 1 USB-C to connect to the Pico

---

## Why? 

I always wanted a good keyboard with a working fingerprint sensor, because my password is always too long and I am used to the one on my laptop. Why not just use the one on my laptop? Because I want to close my laptop lid while using

---

## How? 

---

## Renders

| PCB with Components | 
| --- |
| <img alt="Auth75 Front with Components" src="https://github.com/Lumethra/Auth75/blob/main/Images/PCB-Front.png" /> |
| <img alt="Auth75 Back with Components" src="https://github.com/Lumethra/Auth75/blob/main/Images/PCB-Back.png" /> |

| PCB without Components |
| --- |
| <img alt="Auth75 Front without Components" src="https://github.com/Lumethra/Auth75/blob/main/Images/PCB-Front-No-Components.png" /> |
| <img alt="Auth75 Back without Compoenents" src="https://github.com/Lumethra/Auth75/blob/main/Images/PCB-Back-No-Components.png" /> |

---

## PCB + Schematics

| Schematics |
| --- |
| <img alt="Auth75-PCB" src="https://github.com/Lumethra/Auth75/blob/main/Images/Auth75-Schematics.png" /> |

| PCB |
| --- |
| <img alt="Auth75-Schematics" src="https://github.com/Lumethra/Auth75/blob/main/Images/Auth75-PCB.png" /> |

---

## BOM

| Part | Purpose | Cost | Quantity | Total Cost | LCSC/JLCPCB Number | Link |
| --- | --- | --- | --- | --- | --- | --- |
| PCB | connecting every component | ~ | 1 (5) | $22.60 | ~ | [JLCPCB](https://jlcpcb.com/) |
| Pico 2W | main MCU (handeling software) | ~$7 | 1 | $7 | C42394205 (JLCPCB) | [Raspberry Pi](https://www.raspberrypi.com/products/raspberry-pi-pico-2/) |
| Kailh Hotswap Sockets | holding the switches to the PCB without soldering | $0.1183 | 78 | ~$9 | C2803348 | [JLCPCB](https://jlcpcb.com/) |
| Kailh (Cocoa) Switches | the switches you can press | $0 (comes with a Rainy75) | 78 | $0 (already owned) | ~ | ~ |
| Keycaps | goes onto the switches for better look and feel | $0 (3d printing ABS) | 78 | $0 (3d printed) | ~ | ~ |
| EC11 Rotary Encoder Switch | goes uii and click click | $2.22 | 1 | $2.22 | C370970 | [JLCPCB](https://jlcpcb.com/) / [Amazon](https://www.amazon.de/-/en/RUNCCI-YUN-Potentiometer-Automotive-Electronics-Multimedia/dp/B09SG3HF9N) |
| Fingerprint Reader Kit | recognize your finger | $29.00 | 1 | $29.00 | ~ | [Framework](https://frame.work/products/fingerprint-reader-kit?v=FRANTD0001) |
| KYOCERA AVX FPC Connector | connect the fingerprint sensor | $0.3775 | 1 | $0.3775 | C5464531 | [JLCPCB](https://jlcpcb.com/) |
| USB-C connector | connect to laptop | $0.0740 | 4 | $0.296 | C2765186 | [JLCPCB](https://jlcpcb.com/) |
| PCA9536DGKR | I2C GPIO expander (more GPIO pins, yeeee) | $1.2053 | 1 | $1.2053 | C2649389 | [JLCPCB](https://jlcpcb.com/) |
| SL2.1s | USB Hub core component | $0.2258 | 1 | $0.2258 | C2684433 | [JLCPCB](https://jlcpcb.com/) |
| MMBT3904 | letting the Pi control the LEDs on the sensor | $0.0095 | 3 | $0.0285 | C20526 | [JLCPCB](https://jlcpcb.com/) |
| SS8550 Y2 | implementing the sensor switch into the matrix | $0.0134 | 1 | $0.0134 | C8542 | [JLCPCB](https://jlcpcb.com/) |
| MCP73831T-2ACI/OT | battery charger | $0.7585 | 1 | $0.7585 | C424093 | [JLCPCB](https://jlcpcb.com/) |
| DW01A | battery protector | $0.0426 | 1 | $0.0426 | C351410 | [JLCPCB](https://jlcpcb.com/) |
| FS8205A | mosfet for protector | $0.0470 | 1 | $0.0470 | C2830320 | [JLCPCB](https://jlcpcb.com/) |
| S2B-PH-SM4-TB | connector for battery | $0.2014 | 1 | $0.2014 | C295747 | [JLCPCB](https://jlcpcb.com/) |
| Resistors | prevent things go boom | ~$0.0016 | 19 | ~$0.0304 | C23186, C21190, C22775, C23162 | [JLCPCB](https://jlcpcb.com/) |
| Diodes | prevent voltage from backflowing | $0.0117 | 82 | ~$0.9594 | C81598 | [JLCPCB](https://jlcpcb.com/) |
| Capacitors | smooth out the power | $0.0032 - $0.0110 | 14 | ~$0.0956 | C15849, C19666, C14663 | [JLCPCB](https://jlcpcb.com/) |

> the prices can vary depending on the provider <br>
> you can find the JLCPCB parts on [LCSC](https://lcsc.com/) too (exept the PCB and the Pico)

---

## Contribute

---

## Thank you
