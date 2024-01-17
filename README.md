SlimeVR PCB using ESP32-C3 and BMI 270
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

## EDA Files
EDA files are from a variety of sources, since there is no point in reinventing the wheel. At this current stage, they are assumed correct but have not been tested for accuracy.
- [BMI270](https://www.snapeda.com/parts/BMI270/Bosch%20Sensortec/view-part/) from SnapEDA
- [ESP32 C2 SuperMini](https://www.snapeda.com/parts/ESP32-C3%20SuperMini/Espressif%20Systems/view-part/) from SnapEDA
- [TP4056 Charging Board](https://www.youtube.com/watch?v=d5fERUHO1Lw) footprint copied from YouTube, schematic by observation
- [EG1270](https://www.snapeda.com/parts/EG1270/E-Switch/view-part/)
