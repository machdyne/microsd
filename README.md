# High-Speed MicroSD Pmod&trade; compatible module

This is a 12-pin Pmod™ compatible module with a MicroSD slot and optional 3.3V<->1.8V level translation.

![MicroSD PMOD](https://github.com/machdyne/microsd/blob/c2a3cda8b9c9b648bf7af32a0b943eedce42f0b5/microsd.png)

**This has not yet been tested and may not work.**

This repo contains pinouts, schematics and PCB layouts.

## Pinout

| Pin | Signal|
| --- | ----- |
| 1 | SD\_SS |
| 2 | SD\_MOSI |
| 3 | SD\_MISO |
| 4 | SD\_SCK |
| 5 | GND |
| 6 | 3V3 |
| 7 | SD\_DAT1 |
| 8 | SD\_DAT2 |
| 9 | SD\_CD |
| 10 | SD\_VSEL18 |
| 11 | GND |
| 12 | 3V3 |

Note: 1.8V signals are used when SD\_VSEL18 is high, or 3.3V when low (default).

Note: When SD\_CD is asserted high, power is shut off to the MicroSD card, allowing reset.

## Revisions

| Revision | Stackup | Notes |
| -------- | ------- | ----- |
| V0 | Aisler 4L | Initial prototype |

## License

The contents of this repo are released under the [Lone Dynamics Open License](LICENSE.md).
