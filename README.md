SlimeVR PCB using ESP32-C3 and BMI 270
## Methodology
This design is intended to be assembled either completely by hand, or with some PCBA and finished by hand. Component selection is built around this, prioritizing larger form factor SMT components where possible, to ensure compatibility with and minimizing cost of the PCBA, while maintaining relatively simple assembly when done by hand.
## BOM
|    Component    |            Choice            | Amount | Cost per | Cost with Shipping |                                                                                                    Quick Link                                                                                                    |
|:---------------:|:----------------------------:|:------:|:--------:|:------------------:|:----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|
| Microcontroller | ESP32-C3 Supermini Dev Board | 4      | $4.60    | ~$24               | [AliExpress](https://www.aliexpress.com/item/1005005967641936.html), [Schematic](https://web.archive.org/web/20240114192237/https://www.tindie.com/products/adz1122/esp32-c3-development-board-esp32-supermini/) |
| IMU             | BMI270                       | 4      | $1.75    | ~$9                | [AliExpress](https://www.aliexpress.com/item/1005005001642144.html), [Datasheet](https://web.archive.org/web/20240114195617/https://www.mouser.ca/datasheet/2/783/bst_bmi270_ds000-2529306.pdf), [Schematic](https://web.archive.org/web/20240115041534/http://cdn.kouno.xyz/pKyF5w64.pdf)                  |
| Batteries       | TBD                          |        |          |                    |                                                                                                                                                                                                                  |
| Charging Board  | TP4056                       |        |          |                    |                                                                                                                                                                                                                  |
| Power Switches  | EG1270                       |        |          |                    | [Datasheet](https://www.snapeda.com/parts/EG1270/E-Switch/datasheet/)                                                                                                                                            |
| Diodes          | B5817W                       |        |          |                    | [AliExpress](https://www.aliexpress.com/item/1005005562043696.html), [Datasheet](https://jlcpcb.com/partdetail/Hongjiacheng-B5817W/C7420328)                                                                     |
| Resistors       | 1206 5% (See schematic)      |        |          |                    |                                                                                                                                                                                                                  |
| Capacitors      | 1206 5% (See schematic)      |        |          |                    |                                                                                                                                                                                                                  |

## Acknowledgement
EDA files are from various sources, since there is no point in reinventing the wheel. At this stage, they are assumed to be correct, but have not been tested for accuracy.
- [BMI270](https://www.snapeda.com/parts/BMI270/Bosch%20Sensortec/view-part/) from SnapEDA
- [ESP32 C2 SuperMini](https://www.snapeda.com/parts/ESP32-C3%20SuperMini/Espressif%20Systems/view-part/) from SnapEDA
- [TP4056 Charging Board](https://www.youtube.com/watch?v=d5fERUHO1Lw) footprint copied from YouTube, schematic by observation
- [EG1270](https://www.snapeda.com/parts/EG1270/E-Switch/view-part/) from SnapEDA

Assistance from various sources was used in this project, in addition to readily available datasheets. In particular, the following people and sources have contributed to this project:
- [SlimeVR Docs](https://docs.slimevr.dev/diy/index.html) for general SlimeVR schematics
- [SlimeVR Discord](https://discord.gg/SlimeVR) for general assisance
- [KounoLab](https://store.kouno.xyz/products/bmi270-breakout-board) for additional BMI270 schematics
- @simp_360 on Discord for diode and passive component selection
